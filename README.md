# Health_risk_classification_202401100400213
[README.md](https://github.com/user-attachments/files/20185037/README.md)
# Health Risk Classification using Machine Learning

##  Overview

This project aims to classify individuals into health risk categories (Low, Medium, High) using a Random Forest classifier. The model is trained on lifestyle and health data such as BMI, exercise frequency, alcohol consumption, and diet habits.

---

##  Objective

- Preprocess health-related data.
- Train a Random Forest classifier.
- Evaluate model performance using classification metrics.
- Visualize prediction results using a confusion matrix heatmap.

---

## 📂 Dataset

The dataset is uploaded by the user in CSV format (e.g., `health_risk.csv`). The script dynamically identifies the target column containing "risk".

---

##  Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

---

## 🧪 Methodology

1. **Data Upload and Cleaning**
   - Load CSV using `pandas`
   - Strip column names of extra whitespace
   - Detect and assign the target column dynamically

2. **Preprocessing**
   - Forward-fill missing values
   - Encode categorical features using `LabelEncoder`
   - Scale numeric features using `StandardScaler`

3. **Model Training**
   - Train-test split (80/20)
   - Fit a `RandomForestClassifier` on training data

4. **Evaluation**
   - Generate classification report
   - Visualize confusion matrix using Seaborn heatmap

---

## 📝 Results

- Good classification accuracy across risk levels
- Balanced confusion matrix
- Useful insight into the distribution of true vs predicted classes

---

## 📊 Output

The project also includes:
- A complete evaluation report in PDF format: `Health_Risk_Classification_Report.pdf`
- A confusion matrix plotted using `matplotlib` and `seaborn`

---

## ▶️ How to Run

1. Upload your dataset (CSV format)
2. Run the Jupyter/Colab notebook with the provided code
3. View results, confusion matrix, and download the final report

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Library](https://seaborn.pydata.org/)

---

## 👨‍💻 Author

**Name:** Vishal Beniwal  
**Roll Number:** 202401100400213  
**Section:** C  
**Supervisor:** Abhishek Shukla  
**Institution:** KIET Group of Institutions, Ghaziabad
