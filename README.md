# 🎓 Student Success – Data Preprocessing and Cleaning Challenge  

## 📌 Project Overview  
This project focuses on applying **data preprocessing and cleaning techniques** to the [Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams). The cleaned dataset can be used for building machine learning models to analyze and predict student success factors.  

## 🎯 Objectives  
- Practice real-world **data cleaning and preprocessing**  
- Handle missing values, categorical encoding, and normalization  
- Prepare a dataset suitable for ML workflows  

## 📂 Dataset  
- **Source:** Kaggle – Students Performance in Exams  
- **Input File:** `StudentsPerformance.csv`  
- **Output File:** `students_cleaned.csv`  

## 🛠️ Tasks Performed  
1. **Data Loading** – Imported dataset into Pandas  
2. **Dropping Unnecessary Columns** – Removed irrelevant attributes (e.g., IDs if present)  
3. **Handling Missing Values** – Checked for nulls and cleaned appropriately  
4. **Encoding Categorical Variables** – Used **one-hot encoding** for:  
   - gender  
   - race/ethnicity  
   - parental level of education  
   - lunch  
   - test preparation course  
5. **Normalizing Numerical Features** – Applied **MinMaxScaler** to scale:  
   - math score  
   - reading score  
   - writing score  
6. **Exporting Cleaned Data** – Saved final dataset as `students_cleaned.csv`  
7. **Reflection** – Added notes on encoding, normalization, and challenges  

## 📊 Tools & Libraries  
- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  

## 📑 Deliverables  
- 📓 `student_preprocessing.ipynb` – Jupyter Notebook with preprocessing steps  
- 📂 `students_cleaned.csv` – Cleaned dataset  
- 📝 `reflection.txt` – Short reflection on preprocessing choices  

## 💡 Reflection Highlights  
- **Encoding:** One-hot encoding chosen to avoid imposing false ordinal relationships  
- **Normalization:** Ensures equal contribution of features and helps ML models converge faster  
- **Challenge:** Handling categorical variables required careful selection of encoding methods  

---
