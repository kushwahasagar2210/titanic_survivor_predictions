# Titanic Survival Predictor 🚢

An end-to-end **Data Science & Machine Learning project** predicting survival chances of passengers aboard the Titanic.

## 📌 Project Overview
- **Goal:** Predict whether a passenger survived based on demographic and travel information.
- **Dataset:** Titanic train & test datasets (`titanic_train.csv`, `titanic_test.csv`).
- **Tech Stack:** Python, Pandas, Matplotlib, Scikit-learn.

## 🔑 Steps Followed
1. **Problem Definition & Understanding**
   - Binary Classification: Survived (1) or Not Survived (0).

2. **Data Collection & Cleaning**
   - Handled missing values (Age, Fare, Embarked).
   - Feature Engineering: Title, FamilySize, IsAlone, CabinDeck, TicketGroupSize.

3. **Exploratory Data Analysis (EDA)**
   - Survival rates by gender, class, family size, etc.
   - Distribution plots for Age and Fare.

4. **Model Building**
   - Logistic Regression, Random Forest, Gradient Boosting.
   - Hyperparameter tuning with GridSearchCV.

5. **Model Evaluation**
   - Accuracy: ~85% (Best Model: Logistic Regression).
   - Precision, Recall, F1-score, ROC-AUC evaluated.

6. **Results & Insights**
   - Females and first-class passengers had higher survival rates.
   - Family-related features improved predictions.

## 📊 Results
- **Best Model:** Logistic Regression  
- **Validation Accuracy:** 85%  
- **F1-score (Survived class):** 0.80  

## 📂 Repository Structure
- `data/` → Titanic datasets (CSV)  
- `notebooks/` → Jupyter Notebook with full workflow  
- `reports/` → Figures, metrics, PowerPoint presentation  
- `src/` → Final Python pipeline script  
- `README.md` → Project documentation  

## ▶️ How to Run
```bash
git clone https://github.com/<your-username>/titanic-survival-predictor.git
cd titanic-survival-predictor
pip install -r requirements.txt
python src/titanic_pipeline.py
