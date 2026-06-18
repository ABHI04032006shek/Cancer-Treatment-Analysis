# Cancer Treatment Analysis

> A comprehensive data analysis and machine learning project that explores cancer patient trends across India (2022–2025) and predicts patient status using Logistic Regression.

---

## 📊 Project Overview

Cancer remains one of the leading causes of mortality worldwide. This project analyzes a large dataset of cancer patients across India to uncover patterns related to demographics, cancer types, survival rates, treatment outcomes, and geographical distribution.

The project also develops a Machine Learning model to predict patient status based on medical and demographic characteristics.

---

## 📂 Dataset Information

**Dataset:** `india_cancer_patients_2022_2025.csv`

The dataset contains:

- Patient Demographics
- Age
- Gender
- State
- Cancer Type
- Cancer Stage
- Treatment Type
- Survival Months
- Patient Status

---

## 🎯 Objectives

- Analyze age-wise cancer distribution.
- Study survival rates across age groups.
- Identify states with the highest cancer burden.
- Compare male and female patient trends.
- Examine cancer type prevalence.
- Build a predictive machine learning model.
- Generate actionable healthcare insights.

---

# 📸 Project Screenshots

## DATA 
![DATA](IMAGES/Data1.png)
 
![DATA](IMAGES/Data2.png)

![DATA](IMAGES/Data3.png)


## Age Distribution Analysis

![Age Distribution](IMAGES/Age_distribution.png)

![Age Distribution](IMAGES/age.png.png)


*Most cancer cases are concentrated between 40–70 years of age.*

---

## Geographical Analysis

![Geographical](IMAGES/geo1.png)

![Geographical](IMAGES/geo2.png)

![Geographical](IMAGES/geo3.png)

## Survival Analysis

![Survival Analysis](IMAGES/survival1.png)

![Survival Analysis](IMAGES/survival2.png)

![Survival Analysis](IMAGES/survival3.png)

*Younger patients show higher average survival months compared to older patients.*

---

## Prediction

![Prediction](IMAGES/predicition.png)

---

## 🔍 Exploratory Data Analysis (EDA)

The project performs:

### Data Cleaning

- Missing value detection
- Duplicate record checking
- Data type verification
- Removal of unnecessary columns:
  - City
  - Hospital_Name

### Statistical Analysis

- Mean
- Distribution Analysis

### Visualization

- Histograms
- Count Plots
- Bar Charts
- Survival Analysis Charts

---

# 📈 Key Findings

## 1️⃣ Age Group Analysis

- Majority of patients belong to the **40–70 years** age group.
- Cancer incidence increases significantly after age 40.

### Recommendation

- Promote regular cancer screening after age 40.
- Increase awareness among middle-aged populations.

---

## 2️⃣ Survival Analysis

- Highest survival months observed among patients aged **19–20 years**.
- Survival tends to decrease with increasing age.

### Recommendation

- Encourage early diagnosis and preventive healthcare.

---

## 3️⃣ Geographical Analysis

| State | Observation |
|---------|-------------|
| Delhi | Highest cancer cases |
| West Bengal | Lowest cancer cases |

### Possible Reasons

- Pollution
- Urban lifestyle
- Population density
- Better reporting systems

### Recommendation

- Expand cancer treatment facilities in Delhi.
- Increase screening and awareness campaigns.

---

## 4️⃣ Gender Analysis

- Female patients significantly outnumber male patients.
- Breast and cervical cancers contribute heavily to female cancer cases.

### Recommendation

- Expand women's cancer screening programs.
- Promote breast self-examination awareness campaigns.

---

## 5️⃣ Cancer Type Analysis

Most common cancers include:

- Breast Cancer
- Lung Cancer
- Oral Cancer
- Cervical Cancer
- Leukemia
- Prostate Cancer
- Ovarian Cancer
- Colorectal Cancer
- Stomach Cancer

### Recommendation

- Allocate more resources for specialized treatment centers.
- Conduct cancer-specific awareness programs.

---

# 🤖 Machine Learning Model

## Model Used

**Logistic Regression**

### Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Feature Encoding
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Prediction
      ↓
Evaluation
```

### Features Used

- Age
- Gender
- State
- Cancer Type
- Cancer Stage
- Treatment Type
- Survival Months

### Target Variable

- Patient Status

### Steps Performed

1. Data preprocessing
2. Ordinal Encoding of categorical features
3. Train-Test Split (80%-20%)
4. Logistic Regression training
5. Accuracy evaluation

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📁 Project Structure

```text
Cancer-Treatment-Analysis/
│
├── Cancer Treatment analysis.ipynb
├── india_cancer_patients_2022_2025.csv
│
├── images/
│   ├── age_distribution.png
│   ├── survival_analysis.png
│   ├── state_analysis.png
│   ├── gender_analysis.png
│   └── cancer_types.png
│
└── README.md
```

---

## 🚀 Future Improvements

- Deploy the model using Streamlit.
- Build an interactive dashboard.
- Compare Logistic Regression with other ML models.
- Integrate real-world healthcare datasets.
- Explore deep learning techniques for prediction.

---

## 📌 Conclusion

This project provides valuable insights into cancer trends across India and highlights important demographic, geographical, and medical patterns.

Key conclusions include:

- Most cancer patients belong to the 40–70 years age group.
- Younger patients generally have better survival outcomes.
- Delhi has the highest cancer burden among analyzed states.
- Female patients represent a larger proportion of cancer cases.
- Logistic Regression can effectively predict patient status.

The findings can help healthcare organizations, hospitals, policymakers, and researchers improve cancer prevention, diagnosis, and treatment strategies.

---

## ⭐ Skills Demonstrated

✔ Data Cleaning

✔ Exploratory Data Analysis (EDA)

✔ Data Visualization

✔ Statistical Analysis

✔ Feature Engineering

✔ Machine Learning

✔ Logistic Regression

✔ Healthcare Analytics

✔ Business Recommendations

---

## 👨‍💻 Author

**Abhishek**
### Email ID: a66054462@gmail.com

Data Analytics & Data Science Enthusiast

