# Predicting No-Show Appointments in Healthcare Using Machine Learning and BI

This project explores a real-world dataset of medical appointments in Brazil to predict and understand patient no-shows. It combines data preprocessing, machine learning classification models, and business intelligence (BI) visualizations to deliver actionable insights for improving appointment adherence in healthcare settings.

---

## 📁 Project Structure

- `healthcare_no_show_prediction.ipynb`: Jupyter Notebook containing data analysis, preprocessing, model building, and evaluation.
- `medical_appointments.csv`: Original dataset containing patient and appointment details.
- `processed_medical_appointments.csv`: Cleaned and preprocessed version of the dataset.
- `healthcare_noShow_pbi_dashboard.pbix`: Power BI dashboard visualizing key trends and insights.
- `summary_of_visualizations.pdf`: Summary of the insights drawn from the dashboard.
- `Optimization_Recommendations.pdf` : actionable strategy report
- `requirements.txt` : Python dependencies for the notebook
- `README.md` : Project overview and documentation(this file)

---

## 🔍 Problem Statement

Missed medical appointments cost healthcare systems time, resources, and money. By identifying patterns in patient demographics, health conditions, and scheduling practices, we aim to predict which patients are likely to miss appointments and explore what interventions could reduce no-show rates.

---

## 📊 Key Findings from Visualization

- **No-show Rate by SMS**: SMS reminders had little impact.
- **Age**: Young adults (18–34) are more likely to miss appointments.
- **Weekday**: Mondays saw the highest no-show rate.
- **Scheduling Delay**: Longer delays increased no-show probability.
- **Socioeconomic Status**: Scholarship recipients had higher no-show rates.
- **Chronic Conditions**: Hypertension and diabetes correlated with better attendance.
- **Alcoholism**: Associated with higher no-show rates.

(See `summary_of_visualizations.pdf` for detailed insights.)

---

## 🤖 Machine Learning Models

- **Algorithm Tested**:
  - Logistic Regression 
  - Decision Tree 
  - Random Forest 
  - XGBoost
- **Evaluation Metrics**: Accuracy, F1-score
- XGBoost provided the best performance, with the highest accuracy and F1-score. 

---

## 💡 Technologies Used

- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- Power BI
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   [git clone https://github.com/your-username/healthcare-no-show-prediction.git
   cd healthcare-no-show-prediction](https://github.com/vishnuvsh321/Predicting-No-Show-Appointments-in-Healthcare-Using-Machine-Learning-and-BI/tree/main)

