# 🧠 Employee Salary Prediction Using Random Forest

This project uses the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult) to build a machine learning model that predicts whether an individual's salary exceeds $50K/year based on features like age, education, occupation, and hours worked per week.

## 📁 Dataset

- File used: `adult 3.csv`
- Features include:
  - Age, Education, Occupation
  - Workclass, Relationship, Capital-gain/loss
  - Hours-per-week, Gender, Native country
- Target: `income` (<=50K or >50K)

## 🔍 Objective

To train a **Random Forest Classifier** that can accurately predict if a person's income is greater than 50K based on demographic features.

---

## 🚀 Project Flow

1. **Data Cleaning**  
   - Replace missing values (`?`) with `NaN`
   - Drop rows with missing entries

2. **Data Encoding**  
   - Label encode categorical columns for ML compatibility

3. **Model Training**  
   - Train/Test split (80/20)
   - Random Forest Classifier model fitting

4. **Model Evaluation**  
   - Accuracy Score
   - Confusion Matrix (with Heatmap)
   - Classification Report (Precision, Recall, F1)

5. **Visualization**
   - Input feature distributions (histograms)
   - Confusion matrix heatmap

---

## 📊 Example Output


