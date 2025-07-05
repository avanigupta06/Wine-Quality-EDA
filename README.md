# 🍷 Wine-Quality-EDA

This project performs **Exploratory Data Analysis (EDA)** on the Red Wine Quality dataset available from the UCI Machine Learning Repository. The goal is to analyze the chemical properties of wine and understand how they influence wine quality ratings.

---

## 📂 Dataset Information

- **Source**: UCI Machine Learning Repository  
- **Type**: Red Wine ("Vinho Verde")  
- **Instances**: 1,599  
- **Features**: 11 input variables (physicochemical tests) + 1 output variable (quality score)

### 📌 Features

| Feature                 | Description                              |
|------------------------|------------------------------------------|
| fixed acidity          | Tartaric acid level                      |
| volatile acidity       | Acetic acid content                      |
| citric acid            | Citric acid concentration                |
| residual sugar         | Sugar left after fermentation            |
| chlorides              | Salt content                             |
| free sulfur dioxide    | Free SO₂ for protection                  |
| total sulfur dioxide   | Total SO₂                                |
| density                | Density of wine                          |
| pH                     | Acidity level                            |
| sulphates              | Sulfate content                          |
| alcohol                | Alcohol percentage                       |
| quality (target)       | Wine quality score (0–10)                |

---

## 🔍 EDA Highlights

- **Initial Data Inspection**:
  - Loaded the dataset using `pandas`
  - Checked for null values and data types
  - Removed duplicate rows for cleaner analysis

- **Quality Distribution**:
  - Imbalanced dataset with most wines rated 5 or 6

- **Correlation Analysis**:
  - Used heatmap to visualize correlation matrix
  - Found strong positive correlation between **alcohol** and **quality**

- **Visual Explorations**:
  - Histograms and KDE plots for univariate analysis
  - Boxplots and scatter plots for bivariate analysis
  - Pairplots for multivariate relationships
  - Categorical plots showing alcohol levels across quality ratings

---

## 📊 Key Takeaways

- Wines with higher **alcohol content** tend to have higher quality scores.
- **Volatile acidity** is negatively correlated with quality.
- Dataset is suitable for both classification and regression modeling.

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`

---

## 🚀 Run the Notebook

To run this notebook locally:

```bash
git clone https://github.com/your-username/Wine-Quality-EDA.git
cd Wine-Quality-EDA
jupyter notebook 1.0-WinequalityEDA.ipynb
