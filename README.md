# **Spam Detection Using a Feed-Forward Neural Network with Word Embedding**  

## **Overview**  
This project implements a **two-layer feed-forward neural network** for **spam detection** using **custom Word2Vec embeddings**. The model classifies text messages as **spam or not spam** based on learned word representations.  

## **Dataset**  
- **Source**: [Spam or Not Spam Dataset](https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset?resource=download)  
- **Task**: Classify messages as **spam (1)** or **not spam (0)**  

## **Tasks**  

### 🛠 **1. Data Preprocessing**  
- Balance the dataset and clean text data for model training.  

### 📖 **2. Model Training**  

#### 🔡 **a. Word2Vec Embeddings**  
- Implement **Word2Vec from scratch** using **logistic regression with negative sampling**.  
- Each word is represented as a **10-dimensional embedding**.  

#### 🧠 **b. Neural Network Architecture**  
- **Input**: 12 words per message (each as a 10-dimensional vector).  
- **Hidden Layer**: 2 nodes, each with a size of 8.  
- **Output Layer**: 1 node for binary classification.  
- **Training**: Implement **forward & backward pass, stochastic gradient descent (SGD)** without using external libraries.  

### 📊 **3. Model Evaluation**  
- Evaluate performance using **accuracy, precision, recall, and F1-score**.  
- Visualize model performance using a **confusion matrix**.  

🚀 **This project demonstrates an end-to-end spam detection pipeline, from word embeddings to deep learning classification (from scratch)!**
