

# 🧠 Customer Purchase Prediction using Decision Tree Classifier

This project uses a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on demographic and behavioral data. The model is trained on the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

## 📌 Project Goal

The aim is to build a classification model that can:
- Predict customer purchase intent (yes/no).
- Understand the factors influencing a customer’s decision.
- Help marketers and sales teams target customers more effectively.

## 📁 Dataset: Bank Marketing Dataset (UCI)

- 📄 **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- 📊 **Description**: Contains information related to a direct marketing campaign (phone calls) of a Portuguese banking institution.

### Features include:
- Age, job, marital status, education
- Contact communication type and duration
- Campaign details (number of contacts, previous outcomes)
- Economic indicators (employment variation rate, consumer confidence, etc.)

### Target:
- `y` (binary): Whether the client subscribed to a term deposit (yes/no)

---

## 🛠 Tech Stack

- **Python**
- **Pandas** – Data preprocessing
- **Scikit-learn** – Model building and evaluation
- **Matplotlib / Seaborn** – Visualization
- **Jupyter Notebook / Google Colab** – Development environment

---

## 🔍 Workflow

1. **Data Loading**  
   Load and explore the dataset to understand its structure and features.

2. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize numerical features

3. **Exploratory Data Analysis (EDA)**  
   Visualize key relationships and distribution of features.

4. **Model Building**  
   - Train a **Decision Tree Classifier**
   - Perform train-test split  
   - Tune hyperparameters (e.g., max_depth, min_samples_split)

5. **Evaluation**  
   - Confusion matrix  
   - Accuracy, precision, recall, F1-score  
   - Feature importance analysis

---

## 📈 Sample Result

| Metric        | Value  |
|---------------|--------|
| Accuracy      | 89.2%  |
| Precision     | 83.4%  |
| Recall        | 78.1%  |
| F1-Score      | 80.6%  |

(*Note: Replace with your actual results.*)

---

## 🌳 Feature Importance (Top 5)

1. Contact duration  
2. Number of contacts performed during this campaign  
3. Previous campaign outcome  
4. Age  
5. Job type  

(*Based on Decision Tree model insights*)



---

## 📜 License

This project is open-source and available for educational and non-commercial use.

---


