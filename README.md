# 🩺 Heart Disease Analysis ❤️

Welcome to the **Heart Disease Analysis** project! 🚀 This repository contains a Jupyter Notebook 📓 that dives into analyzing a heart disease dataset using powerful Python libraries like NumPy, Pandas, Matplotlib, and Seaborn. The goal? To uncover insights from medical indicators that predict the presence of heart disease! 🩺

---

## 🌟 Overview

Heart disease is a critical health concern, and understanding its risk factors can save lives. This project explores a dataset (`heart_data.csv`) containing medical attributes to identify patterns and predictors of heart disease. Using data analysis and visualization techniques, we aim to provide meaningful insights for researchers and enthusiasts alike. 📊

---

## 📊 Dataset

The dataset (`heart_data.csv`) includes the following columns:

| **Column**   | **Description**                                                                 |
|--------------|---------------------------------------------------------------------------------|
| `age`        | Age of the patient 👶👴                                                        |
| `sex`        | Sex of the patient (1 = male; 0 = female) 🚹🚺                                  |
| `cp`         | Chest pain type (0 = typical angina; 1 = atypical angina; 2 = non-anginal pain; 3 = asymptomatic) 🤕 |
| `trestbps`   | Resting blood pressure (in mm Hg) 🩺                                            |
| `chol`       | Serum cholesterol in mg/dL 🩺                                                  |
| `fbs`        | Fasting blood sugar > 120 mg/dL (1 = true; 0 = false) 🍬                       |
| `restecg`    | Resting electrocardiographic results (0 = normal; 1 = ST-T wave abnormality; 2 = probable/definite left ventricular hypertrophy) 📈 |
| `thalach`    | Maximum heart rate achieved 💓                                                 |
| `exang`      | Exercise-induced angina (1 = yes; 0 = no) 🏃‍♂️                                |
| `oldpeak`    | ST depression induced by exercise relative to rest 📉                          |
| `slope`      | Slope of the peak exercise ST segment (0 = upsloping; 1 = flat; 2 = downsloping) 📏 |
| `ca`         | Number of major vessels (0-3) colored by fluoroscopy 🩻                        |
| `thal`       | Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect) 🧬           |
| `target`     | Presence of heart disease (1 = yes; 0 = no) ❤️🚫                                |

---

## 🛠️ Requirements

To run the analysis, you'll need the following Python libraries:

| **Library**  | **Purpose**                     |
|--------------|---------------------------------|
| `NumPy`      | Numerical computations 🧮      |
| `Pandas`     | Data manipulation & analysis 📅 |
| `Matplotlib` | Data visualization 📊           |
| `Seaborn`    | Enhanced visualizations 🎨     |

Install them using pip:
```bash
pip install numpy pandas matplotlib seaborn
```

---

## 🚀 How to Run

Follow these steps to explore the heart disease analysis:

### 📋 Prerequisites
- Python 3.x 🐍
- Git 🌳
- Jupyter Notebook 📓

### 🛠️ Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mohamed-Teba/Heart_Disease_Analysis.git
   cd Heart_Disease_Analysis
   ```

2. **Install Dependencies**:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook heart_disease_analysis.ipynb
   ```

4. **Explore the Analysis**:
   - Open the notebook in your browser and run the cells to visualize insights! 🎉

---

## 📂 Project Structure

| **File**                         | **Description**                                                                 |
|----------------------------------|--------------------------------------------------------------------------------|
| `heart_disease_analysis.ipynb`   | Jupyter Notebook with the full data analysis and visualizations 📓             |
| `heart_data.csv`                | Dataset containing heart disease indicators 📊                                 |
| `README.md`                     | Project documentation (you're reading it!) 📜                                  |

---

## 🔍 Analysis Steps

The `heart_disease_analysis.ipynb` notebook includes:
1. **Data Loading** 📂: Importing the dataset using Pandas.
2. **Data Cleaning** 🧹: Handling missing values and ensuring data quality.
3. **Exploratory Data Analysis (EDA)** 🔎: Visualizing distributions and relationships between variables.
4. **Insights Generation** 💡: Identifying key factors influencing heart disease risk.
5. **Visualizations** 📈: Creating plots (e.g., histograms, heatmaps) with Matplotlib and Seaborn.

---

## 🎯 Results

The analysis reveals:
- Key correlations between features like `age`, `chol`, and `thalach` with heart disease. 📊
- Visual insights into how chest pain types and exercise-induced angina impact diagnosis. 🩺
- Patterns in demographic factors (e.g., sex) and their relation to heart disease risk. 🚹🚺

---

## 🌈 Future Improvements

- 🧠 Add machine learning models to predict heart disease risk.
- 📈 Enhance visualizations with interactive plots (e.g., using Plotly).
- ⚡ Expand the dataset with additional features or larger sample sizes.

---

## 🙌 Acknowledgments

- Thanks to the creators of the heart disease dataset for making this analysis possible! 🙏
- Shoutout to the open-source communities behind NumPy, Pandas, Matplotlib, and Seaborn. 🌟

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📜 Footer
© 2025 GitHub, Inc. All rights reserved.