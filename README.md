# Drug-Classification-Project
ML project to classify drugs using patient data

# 💊 Drug Classification - Machine Learning Project

##  Submitted by:
**Shubham Mishra(Admin),**
  Annu Kumar,
  Saksham Kumar
  and Suraj Tiwari

B.Tech CSE, Semester IV  
Galgotias University

---

## 🧠 Project Objective

The goal is to classify drugs based on patient features using machine learning. The classification is done using patient attributes:

- Age
- Sex
- Blood Pressure (BP)
- Cholesterol level
- Sodium to Potassium ratio (Na_to_K)

---

## 🔍 Dataset

- File: `drug200.csv`
- Records: 200
- Features: Age, Sex, BP, Cholesterol, Na_to_K
- Target: Drug (drugA, drugB, drugC, drugX, drugY)

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## 📊 Workflow Summary

### 1. Data Cleaning
- Checked for missing values
- Removed duplicate rows

### 2. Preprocessing
- Categorical encoding (Sex, BP, Cholesterol)
- Outlier capping using 95th percentile
- Feature scaling using `StandardScaler`

### 3. Exploratory Data Analysis (EDA)
- Heatmap of correlations
- Boxplot to visualize outliers
- Countplot of drug class distribution
- Pairplot for feature relationships

### 4. Model Building
- Used `RandomForestClassifier`
- Split: 70% training, 30% testing
- Stratified to ensure class balance

### 5. Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1)
- Feature Importance Chart

---

## 📈 Output Example

- ✅ Accuracy: ~100% (on stratified sample)
- 🔬 Key Insight: `Na_to_K` and `BP` strongly influence drug prediction
- 🧠 Most important feature: `Na_to_K`

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `drug_classification.ipynb` | Full code with comments and outputs |
| `drug200.csv` | Dataset file used |
| `README.md` | This project summary file |
| `presentation.pptx` | Final presentation for review submission |

---

## 🚀 How to Run This Project (Step-by-Step)

You can run this project on your local system using **Jupyter Notebook** or online using **Google Colab**.

---

### 🧪 Option 1: Run in Jupyter Notebook

1. Download the repository as ZIP from GitHub and extract it.
2. Make sure these files are present in the same folder:
   - `drug_classification.ipynb`
   - `drug200.csv`
3. Open **Jupyter Notebook** and launch the notebook:
   ```bash
   jupyter notebook


## 👥 Team Members

- Shubham Mishra (Project Lead)
- Annu Kumar
- Saksham Kumar
- Suraj Tiwari

---

##  Acknowledgement

This project was created as part of **Data Analytics Review Submission** at Galgotias University.

Thanks for reviewing!  
— **Shubham Mishra**
