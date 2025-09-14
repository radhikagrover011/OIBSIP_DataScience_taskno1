# OIBSIP_DataScience_taskno1
Oasis Infobyte Internship Tasks-(Iris Classification)  

## 📌 Objective  
The goal of this project is to build a machine learning model that classifies iris flowers into three species (*Setosa, Versicolor, Virginica*) based on their sepal and petal measurements.  

---

## 📂 Dataset  
- **Source:** [Kaggle – Iris Dataset](https://www.kaggle.com/datasets/saurabh00007/iriscsv)  
- **Features:**  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Target:** Species (Setosa, Versicolor, Virginica)  

---

## 🛠️ Project Workflow  
1. **Data Loading & Preprocessing**  
   - Loaded dataset (`Iris.csv`) using pandas.  
   - Removed unnecessary columns (`Id`).  
   - Renamed columns for consistency.  
   - Encoded species labels into numeric form.  

2. **Exploratory Data Analysis (EDA)**  
   - Checked dataset structure and summary.  
   - Visualized species distribution and feature relationships.  

3. **Data Splitting**  
   - Train-test split: 80% training, 20% testing.  

4. **Model Building**  
   - Built a pipeline using:  
     - `StandardScaler` (feature scaling)  
     - `LogisticRegression` (classification model)  

5. **Evaluation**  
   - Calculated test accuracy (~93–96%).  
   - Generated classification report (precision, recall, f1-score).  
   - Plotted confusion matrix.  

6. **Model Saving & Prediction**  
   - Saved trained model as `iris_model.joblib`.  
   - Tested with a sample input `[5.1, 3.5, 1.4, 0.2]`.  

---

## ⚙️ Tools & Libraries  
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Joblib  
- Jupyter Notebook  

---

## 📊 Results  
- **Accuracy:** ~93–96%  
- **Classification Report:**  
  - Perfect classification for Setosa  
  - ~90% for Versicolor & Virginica  
- **Confusion Matrix:**  

![Confusion Matrix](iris_confusion_matrix.png)  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/radhikagrover011/OIBSIP_DataScience_taskno1.git
   cd OIBSIP_DataScience_taskno1
