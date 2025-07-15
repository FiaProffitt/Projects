# Land-Use Classification with Deep Neural Networks 

## Project Overview

This project, completed as part of **COMP534: Machine Learning Pipeline - Assessment 2**, focuses on building and training deep neural networks to solve an image classification problem. The goal is to accurately classify aerial scene images into various land-use categories, addressing the critical task of effectively creating and training neural networks for optimal performance.

---

## Dataset

This project utilizes the **UCMerced Land-use Dataset**, which comprises:
* **2100 aerial scene images**
* **256 x 256 pixels** resolution
* Categorized into **21 distinct land-use classes**

Detailed information and download links for the dataset are available on Canvas.

---

## Features

* **Data Management & Preprocessing:**
    * Definition of a robust experimental protocol (e.g., k-fold cross-validation) for data splitting.
    * Creation of a custom DataLoader for efficient data loading.
    * Implementation of essential preprocessing techniques, including **normalization** and **data augmentation** strategies, to enhance model generalization.
* **Neural Network Architectures:**
    * **Custom CNN Development:** Design and implementation of a custom Convolutional Neural Network (CNN) architecture from scratch to address the classification task.
    * **Pre-trained CNN Utilization:** Integration and evaluation of at least one well-known existing CNN architecture (e.g., AlexNet, VGG, ResNet, DenseNet).
* **Training Strategies:**
    * Comprehensive training procedures, including **training from scratch**, **fine-tuning**, and **feature extraction**, for the selected existing CNN architecture.
    * Definition of critical training components: **loss functions** (e.g., Cross-Entropy Loss) and **optimizers** (e.g., Adam, SGD).
    * Visualization of training progress through **loss and accuracy plots** over epochs/iterations.
* **Model Evaluation:**
    * Evaluation of the best-performing model on a dedicated **testing dataset**.
    * Reporting of at least three relevant evaluation metrics (e.g., Accuracy, Precision, Recall, F1-score) for multi-class classification.
    * Visualization and in-depth discussion of the **confusion matrix** to analyze model performance across classes.

---

## Project Structure

The project code is organized within a Jupyter Notebook template, aligning with the structured approach of a machine learning pipeline:

### 1. Data Management

* **Experimental Protocol:** Detail the data splitting strategy used (e.g., k-fold, cross-validation).
* **Dataloader & Preprocessing:** Implement the dataloader, including any normalization, data augmentation, or other techniques applied to preprocess the input images.

### 2. Neural Networks

* **Proposed CNN:** Define and describe the custom Convolutional Neural Network architecture designed for this problem.
* **Existing CNN:** Select and describe at least one established CNN (e.g., ResNet, VGG) to compare against the custom model.
* **Training Components:** Specify the chosen loss function, optimizer, and other necessary components for training the networks.
* **Training Procedures:** Train both the proposed architecture from scratch and the existing architecture using at least two different strategies (e.g., from scratch, fine-tuning, feature extraction).
* **Visualizations:** Plot loss and accuracy curves for all training procedures.

### 3. Evaluate Models

* **Test Set Evaluation:** Evaluate the best-performing model from the training phase on the separate testing dataset.
* **Performance Reporting:** Report results using at least three appropriate metrics and analyze the confusion matrix to assess classification performance.

---

## Contributions

This project was completed by Fia Proffitt.

---

## Disclaimer

This project was completed as part of a university assignment at the University of Liverpool. All intellectual property and ownership rights for this work belong to the university.
