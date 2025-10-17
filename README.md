# 🎓 Student Performance Analysis using Deep Learning

## 📘 Project Overview
This project analyzes and predicts students’ academic performance using deep learning and machine learning models. The aim is to identify key factors influencing scores and predict a student’s average score based on demographic and academic attributes.

## 🧠 Objective
- Perform exploratory data analysis (EDA) on student exam performance data.
- Build a regression model using a Multi-Layer Perceptron (MLP) to predict average student scores.
- Compare results with a baseline Random Forest model.
- Visualize performance metrics including loss, MAE, and error distribution.

## 📊 Dataset
- **Source:** [Students Performance Dataset on Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Features:** Gender, parental education, test preparation course, and scores in Math, Reading, and Writing.
- **Target:** Average score (mean of Math, Reading, and Writing).

## 🧩 Methodology
1. Data preprocessing (encoding, scaling, splitting)
2. Exploratory Data Analysis (heatmaps, boxplots, histograms)
3. Model building:
   - Random Forest Regressor (baseline)
   - Deep Learning MLP model
4. Evaluation and visualization of results.

## 📈 Results
- The model achieved good prediction accuracy and low mean absolute error.
- Deep Learning model captured non-linear relationships effectively.
- Visualization of loss vs. epoch and MAE vs. epoch shows proper model convergence.

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

## 📁 Repository Contents
- `Student_Performance_Report.pdf` – Detailed project report  
- `Student_Performance.ipynb` – Full source code (Colab notebook)  
- `StudentsPerformance.csv` – Dataset  
- `README.md` – Project summary and usage instructions  

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/Student-Performance-Analysis.git
