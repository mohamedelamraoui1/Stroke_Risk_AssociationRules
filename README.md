# 🧠 Stroke Risk Prediction using Association Rule Mining

This project applies Association Rule Mining to analyze stroke risk factors using the Stroke Prediction Dataset. It focuses on discovering meaningful patterns and relationships between variables (age, BMI, glucose level, hypertension, etc.) and stroke occurrence.

## 📌 Objective

To extract interpretable and actionable rules from health data that reveal combinations of features associated with stroke risk. This helps in understanding contributing risk factors and informing preventative care.

## 📊 Dataset

- Source: Stroke Prediction Dataset  
- Format: CSV  
- Key features: age, bmi, avg_glucose_level, hypertension, heart_disease, smoking_status, stroke

## 🧱 Project Structure

All steps are implemented in a single notebook:  
📓 Stroke_Risk_AssociationRules.ipynb

Steps:

1. Data Loading & Cleaning
2. Preprocessing: encoding & binning
3. Transactional conversion
4. Frequent itemset generation (Apriori)
5. Rule mining and filtering
6. Evaluation using interestingness metrics
7. Interpretation of rules related to stroke risk

## 🛠️ Tools & Libraries

- Python 3
- pandas, numpy
- mlxtend (Apriori & association_rules)
- matplotlib, seaborn

## 📈 Metrics Used

Based on the paper:  
“On selecting interestingness measures for association rules: user-oriented description and multiple criteria decision aid.”

Metrics include:

- Support
- Confidence
- Lift
- Conviction
- Leverage

## 📁 Output

- A list of filtered rules highlighting stroke-related patterns.
- Visualizations of rule strength.
- Interpretation of rules involving stroke as a consequent.

## ✅ Example Rule

"If BMI=Obese and Hypertension=True → Stroke"  
(Support=0.06, Confidence=0.72, Lift=1.8)

## 📄 License

This project is for academic and educational use. Attribution is appreciated.
