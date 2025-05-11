# 🎓 Student Performance Prediction – Machine Learning Project
 
This project aims to predict whether a student will pass or fail using real-world educational data from Portuguese secondary schools. It was conducted as part of a machine learning assignment, divided into three structured phases: exploration & preprocessing, model implementation, and final insights & recommendations.

---
 
## 📁 Project Structure

```bash
├── data/
│ ├── student_data_raw.xlsx
│ └── student_data_processed.csv
│
├── notebooks/
│ ├── phase1_eda.ipynb
│ └── phase2_models.ipynb
│
├── report/
│ └── final_project_report.pdf
│
├── figures/
│ ├── confusion_matrix.png
│ ├── roc_curve.png
│
└── README.md
```

## ✅ Project Phases Overview
 
### 🔹 Phase 1 – Exploration & Preprocessing
- Dataset summary, problem type (classification)
- EDA: summary statistics, missing values, outliers
- Visualizations: grade distribution, pass/fail by gender
- Preprocessing: handling missing data, one-hot encoding, scaling
 
### 🔹 Phase 2 – Model Implementation & Evaluation
- Models used: Decision Tree, KNN, Random Forest, Logistic Regression
- Hyperparameter tuning and justification
- Evaluation metrics: Accuracy, Precision, Recall, F1-score
- Confusion matrices and ROC curve analysis
- Performance comparison table
 
### 🔹 Phase 3 – Insights & Recommendations
- Key insights from model results
- Actionable recommendations for schools and educators
- Limitations of the dataset and approach
- Future improvement ideas and research extensions

- ---
 
## 💡 Key Takeaways
 
- Early performance (`G1`, `G2`) is a strong predictor of final success.
- Absences and prior failures are strongly linked to failure risk.
- Models performed extremely well, suggesting linear separability.
- Machine learning can be a useful early-warning tool in education.
 
---
 
## 👥 Group Contribution Summary
 
| Member Name        | Contributions                                                                                  |
|--------------------|-----------------------------------------------------------------------------------------------|
| **Adjiey Junior**   | Led the project across all phases. In **Phase 1**, performed dataset exploration, preprocessing (EDA, missing values, outliers, encoding, scaling). In **Phase 2**, implemented and evaluated all four models. Contributed significantly to writing and structuring the final report. |
| **Aloyem Anna**        | Contributed to **Phase 1** by helping with visualization and feature analysis. In **Phase 2**, handled model training (Decision Tree & KNN), hyperparameter tuning, and supported the metrics comparison. |
| **Joel Tiendrebeogo**  | In **Phase 2**, focused on evaluating models (precision, recall, F1), building the confusion matrices, and plotting ROC curves. Also participated in reviewing preprocessing logic. |
| **Josué KOFFI**        | Took charge of **Phase 3** – Insights, Recommendations, and Future Work. Finalized the formatting of the report, organized project folders, and structured the GitHub repository. Helped with dataset cleaning in Phase 1. |
 
> All team members actively participated in reviewing each phase and committed to GitHub regularly to ensure full collaboration and transparency.

## 🔗 How to Run the Project
 
1. Clone the repository:
```bash
git clone https://github.com/your-username/student-performance-ml.git
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Open the notebooks in the /notebooks/ folder using Jupyter Notebook or VSCode.
 
## 🧩 Requirements
Python 3.8+
 
pandas
 
numpy
 
scikit-learn
 
matplotlib
 
seaborn
 
openpyxl (for reading .xlsx files)
 
## 📜 License
This project was completed for academic purposes and is not intended for production or commercial use.
