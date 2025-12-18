# Kyphosis Classification using Decision Tree

## 📌 Project Overview
This project implements a **Decision Tree classifier** to predict the presence or absence of **Kyphosis** in patients after spinal surgery.  
The goal is to demonstrate a simple **supervised machine learning workflow** including data preprocessing, model training, evaluation, and interpretation.

---

## 📊 Dataset
- **Dataset Name:** Kyphosis  
- **Source:** Included as `Kyphosis.csv`  
- **Number of Rows:** 81  
- **Features:**  
  1. `Age` – Age of the patient (in months)  
  2. `Number` – Number of vertebrae involved in the operation  
  3. `Start` – The starting vertebra  
- **Target Variable:** `Kyphosis` – Whether kyphosis is present (`present`) or absent (`absent`)

---

## 🧠 Methodology
1. **Data Loading:** Load the CSV dataset using Pandas.  
2. **Feature & Target Separation:** Divide dataset into `X` (features) and `y` (target).  
3. **Train-Test Split:** Split the dataset into training (70%) and testing (30%) sets using `train_test_split` with a `random_state` for reproducibility.  
4. **Model Training:** Train a `DecisionTreeClassifier` on the training data.  
5. **Prediction:** Predict target labels on the test set.  
6. **Evaluation:** Evaluate model performance using:
   - **Accuracy Score**
   - **Confusion Matrix**
   - Optional: Classification report for precision, recall, F1-score.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Kyphosis-Decision-Tree.git
