# Named Entity Recognition (NER) with Neural Networks 

## Project Overview

This project, completed as **COMP534: Machine Learning Pipeline - Assessment 3**, focuses on building and training neural network models for **Named Entity Recognition (NER)**. NER is a fundamental Natural Language Processing (NLP) subtask that involves identifying and classifying named entities (like locations, persons, organizations, etc.) within text. This assignment explores the development of both Recurrent Neural Networks (RNNs) and Transformer Networks from scratch for this crucial task.

---

## Dataset

The project utilizes a small, specialized dataset comprising approximately **1696 sentences**.
Each sentence is formatted with two columns (word and entity classification), separated by a space delimiter. Sentences are separated by blank lines.

**Entity Categories:**
* **`I-LOC`**: Location entity
* **`I-PER`**: Person entity
* **`I-ORG`**: Organization entity
* **`I-MISC`**: Miscellaneous entity
* **`O`**: Outside (non-entity word)

The dataset can be downloaded from Canvas.

---

## Features

* **Data Management & Preprocessing:**
    * Defined a clear **experimental protocol** (e.g., k-fold, cross-validation) for data splitting.
    * Created a custom **DataLoader** to efficiently load the sequential text data.
    * Implemented essential preprocessing steps, including **encoding** (e.g., converting words/entities to numerical IDs) and **vocabulary creation**.
* **Neural Network Architectures (PyTorch Only):**
    * Developed and implemented a **Recurrent Neural Network (RNN)** based model (e.g., simple RNN, GRU, or LSTM) for sequential tagging.
    * Designed and implemented a **Transformer Network** from scratch, showcasing understanding of its core components (attention mechanisms).
    * *(**Note:** External libraries like `transformers` were *not* used for implementing these architectures; only PyTorch was allowed.)*
* **Model Training:**
    * Defined necessary training components: **loss function** (e.g., Cross-Entropy Loss or a variant suitable for sequence tagging) and **optimizers** (e.g., Adam, SGD).
    * Trained both the RNN and Transformer models.
    * Visualized training progress by plotting **loss and accuracy curves** over epochs/iterations for all procedures.
* **Model Evaluation:**
    * Evaluated the best-performing model on a dedicated **testing dataset**.
    * Reported results using at least **three appropriate metrics** for NER (e.g., token-level accuracy, precision, recall, F1-score for each entity type or macro/micro averages).
    * Visualized and discussed the **confusion matrix** to understand the model's performance on different entity classes.

---

## Project Structure

The project code is organized within a Jupyter Notebook template, aligning with the structured approach of a machine learning pipeline:

### 1. Data Management
* **Experimental Protocol:** Details the data splitting strategy used.
* **Dataloader Implementation:** Contains code for the dataloader, including tokenization, numerical encoding, vocabulary building, and batching.

### 2. Neural Networks
* **RNN Implementation:** Code and description of the implemented Recurrent Neural Network (RNN, GRU, or LSTM).
* **Transformer Network Implementation:** Code and description of the Transformer Network built from scratch.
* **Training Components:** Definitions of loss functions, optimizers, and other training setup.
* **Model Training:** Code for training both RNN and Transformer models.
* **Visualizations:** Plots showing loss and accuracy trends during training for all models.

### 3. Evaluate Models
* **Test Set Evaluation:** Code for assessing the best model's performance on the unseen test set.
* **Performance Reporting:** Presentation of key metrics and a confusion matrix for the final chosen model.

---

## Contributions

This project was completed by Fia Proffitt.

---

## Disclaimer

This project was completed as part of a university assignment at the University of Liverpool. All intellectual property and ownership rights for this work belong to the university.
