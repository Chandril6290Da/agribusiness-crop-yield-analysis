# 🌾 Agribusiness Crop Yield Analysis

## Machine Learning Data Analyst Internship Project

This project focuses on analyzing agricultural and farming data to understand the factors that influence crop yield and to develop a data-driven machine learning solution for crop yield prediction.

The project follows a complete data analytics and machine learning workflow, starting from data collection and cleaning, followed by exploratory data analysis, predictive modelling, and finally business-oriented recommendations for the agribusiness sector.

---

## 🎯 Project Objective

The main objectives of this project are:

* Collect and prepare a publicly available agribusiness dataset.
* Clean and preprocess agricultural data.
* Identify and handle missing values and duplicate records.
* Detect invalid values and potential outliers.
* Perform statistical analysis and exploratory data analysis.
* Identify relationships between farming/environmental factors and crop yield.
* Build a machine learning model for crop yield prediction.
* Evaluate model performance using appropriate metrics.
* Convert analytical findings into practical agribusiness recommendations.

---

## 📊 Dataset

The project uses the **Crop Yield of a Farm** dataset from Kaggle.

The dataset contains approximately **3,000 observations** representing farming and environmental conditions associated with crop yield.

### Dataset Features

| Feature              | Description                    |
| -------------------- | ------------------------------ |
| `rainfall_mm`        | Amount of rainfall received    |
| `soil_quality_index` | Soil quality score             |
| `farm_size_hectares` | Size of the farm in hectares   |
| `sunlight_hours`     | Average sunlight exposure      |
| `fertilizer_kg`      | Quantity of fertilizer used    |
| `crop_yield`         | Crop yield in tons per hectare |

**Target Variable:** `crop_yield`

This makes the dataset suitable for a **regression-based machine learning problem**.

---

# 🔄 Project Workflow

```text
Kaggle Dataset
      ↓
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Analysis
      ↓
Machine Learning Model
      ↓
Model Evaluation
      ↓
Agribusiness Insights
      ↓
Recommendations
```

---

# 📅 Internship Week-wise Work

## Week 1 — Data Collection & Cleaning

The first phase focuses on preparing the dataset for further analysis.

### Tasks Completed

* Dataset collection
* Dataset loading using Pandas
* Dataset structure inspection
* Data type inspection
* Missing value analysis
* Missing value treatment
* Duplicate record detection
* Duplicate removal
* Invalid value detection
* Logical range validation
* Outlier detection using the IQR method
* Statistical summary
* Final data quality verification
* Export of cleaned dataset

### Main Libraries

```python
Pandas
NumPy
Matplotlib
Seaborn
```

The cleaned dataset is stored in:

```text
Dataset/cleaned_dataset.csv
```

---

# 📈 Week 2 — Exploratory Data Analysis

The second phase will focus on understanding the cleaned dataset through statistical and visual analysis.

### Planned Analysis

* Distribution analysis
* Histograms
* Boxplots
* Scatter plots
* Correlation analysis
* Heatmap
* Feature-to-target relationships
* Trend identification
* Anomaly identification
* Statistical interpretation

### Key Questions

The analysis will investigate questions such as:

* How does rainfall affect crop yield?
* Does soil quality influence yield?
* What is the relationship between farm size and crop yield?
* Does sunlight exposure have an observable relationship with yield?
* How does fertilizer usage relate to crop yield?
* Which variables have the strongest relationship with the target?

---

# 🤖 Week 3 — Machine Learning Modelling

The third phase will use the cleaned dataset to develop a predictive machine learning model.

Since `crop_yield` is a continuous numerical variable, the primary problem will be treated as a **regression problem**.

### Planned Workflow

```text
Cleaned Dataset
      ↓
Feature Selection
      ↓
Train/Test Split
      ↓
Model Training
      ↓
Prediction
      ↓
Performance Evaluation
```

### Candidate Algorithms

Depending on the EDA results, suitable regression algorithms may include:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor

### Evaluation Metrics

The model may be evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

The final algorithm will be selected based on model performance and suitability for the dataset.

---

# 💡 Week 4 — Findings & Agribusiness Recommendations

The final phase will convert technical analysis into understandable business insights.

The report will explain:

* Important factors affecting crop yield
* Model findings
* Significant relationships identified during EDA
* Prediction performance
* Potential agricultural implications
* Practical recommendations for farmers and agribusiness stakeholders

The objective is to communicate the results in a way that can be understood by a **non-technical audience**.

---

# 🛠️ Technologies Used

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn

### Development Environment

* Visual Studio Code
* Jupyter Notebook

### Version Control

* Git
* GitHub

---

# 📁 Project Structure

```text
Agribusiness_Internship/
│
├── Dataset/
│   ├── original_dataset.csv
│   └── cleaned_dataset.csv
│
├── Notebook/
│   └── Agribusiness_Crop_Yield_Analysis.ipynb
│
├── Visualizations/
│
├── Model/
│
├── Report/
│
└── README.md
```

---

# 🚀 How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/Chandril6290Da/agribusiness-crop-yield-analysis.git
```

## 2. Open the Project

Open the project folder in Visual Studio Code.

## 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter openpyxl python-docx
```

## 4. Open the Notebook

Navigate to:

```text
Notebook/Agribusiness_Crop_Yield_Analysis.ipynb
```

Open the notebook using the Jupyter extension in Visual Studio Code.

## 5. Run the Notebook

Run the cells sequentially from data loading through analysis and modelling.

---

# 📌 Current Project Status

| Phase                     | Status      |
| ------------------------- | ----------- |
| Dataset Collection        | ✅ Completed |
| Data Cleaning             | ✅ Completed |
| Data Quality Analysis     | ✅ Completed |
| Cleaned Dataset           | ✅ Generated |
| Exploratory Data Analysis | 🔄 Next     |
| Machine Learning Model    | 🔄 Planned  |
| Model Evaluation          | 🔄 Planned  |
| Final Recommendations     | 🔄 Planned  |
| Final Internship Report   | 🔄 Planned  |

---

# ⚠️ Dataset Limitation

The selected dataset contains a crop-yield target generated using a predefined relationship between the input variables.

Therefore, extremely high machine learning performance should not automatically be interpreted as proof of real-world agricultural prediction capability.

Real-world agricultural datasets may contain additional factors such as:

* Crop variety
* Temperature
* Humidity
* Pest and disease conditions
* Irrigation
* Geographic location
* Seasonal effects
* Market and farming practices

These factors are not fully represented in the current dataset.

---

# 🔮 Future Scope

The project can be extended by:

* Using real-world agricultural datasets
* Adding weather data
* Adding geographic information
* Adding crop-type information
* Developing a crop yield prediction web application
* Creating an interactive Power BI dashboard
* Deploying the machine learning model through an API
* Integrating real-time IoT agricultural sensors
* Developing a farmer-oriented prediction system

---

# 📚 Learning Outcomes

Through this internship project, the following skills are being developed:

* Data collection
* Data cleaning
* Data preprocessing
* Statistical analysis
* Exploratory data analysis
* Data visualization
* Feature analysis
* Regression modelling
* Model evaluation
* Business interpretation
* Technical documentation
* Git and GitHub workflow

---

## 👨‍💻 Project Repository

**Agribusiness Crop Yield Analysis**

Repository:

https://github.com/Chandril6290Da/agribusiness-crop-yield-analysis

---

## 📄 Internship Project

This repository documents the complete progression of an agribusiness data analytics and machine learning project from raw data to predictive modelling and actionable recommendations.
