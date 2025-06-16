# 🩺 Exploratory Data Analysis on Cardiotocographic Dataset

## 🎯 Project Title

**Exploratory Data Analysis (EDA) on Cardiotocographic Dataset**

---

## 📌 Objective

The goal of this project is to perform a comprehensive **Exploratory Data Analysis (EDA)** on the `Cardiotocographic.csv` dataset. Through statistical summaries, visualizations, and preprocessing, we aim to extract insights, understand variable relationships, and prepare the data for further modeling.

---

## 📊 Dataset Description

The dataset contains measurements from fetal monitoring, including fetal heart rate and uterine contraction metrics.

### 🧬 Columns:

- `LB`: Baseline Fetal Heart Rate (FHR)
- `AC`: Accelerations in FHR
- `FM`: Fetal Movements
- `UC`: Uterine Contractions
- `DL`: Late Decelerations
- `DS`: Short-term Decelerations
- `DP`: Prolonged Decelerations
- `ASTV`: % Time with Abnormal Short-Term Variability
- `MSTV`: Mean Short-Term Variability
- `ALTV`: % Time with Abnormal Long-Term Variability
- `MLTV`: Mean Long-Term Variability
- `Width`: Width of the FHR Histogram
- `Tendency`: FHR Pattern Trend
- `NSP`: Fetal State Class Code (Normal, Suspect, Pathologic)

---

## 📁 Files in this Repository

- `Cardiotocographic.csv` — Dataset used for the EDA.
- `eda 1.ipynb` — Jupyter Notebook with Python code for preprocessing, visualization, and analysis.
- `EDA1.docx` — Documentation outlining project objectives, steps, and deliverables.

---

## 🧰 Tools & Libraries Used

- `pandas` — Data manipulation
- `numpy` — Numerical operations
- `matplotlib` — Data visualization
- `seaborn` — Statistical plotting

---

## 📈 Key Findings & Insights

- **Data Cleaning**:
  - Missing values were imputed using the median.
  - Outliers were treated using the IQR method.
- **Data Types**:
  - Converted `Tendency` and `NSP` to categorical types.
- **Distributions & Relationships**:
  - Many features had non-normal or bimodal distributions.
  - Weak linear relationships suggest non-linear models may be more effective.
- **Feature Engineering Potential**:
  - Moderate correlations between certain features.
  - Important for reducing noise in modeling.

---

## 🚀 How to Run

bash
### 1. Clone the repository
git clone https://github.com/your-username/cardiotocographic-eda.git
cd cardiotocographic-eda

### 2. Install the required libraries
pip install pandas numpy matplotlib seaborn jupyter

### 3. Run the Jupyter Notebook
jupyter notebook "eda 1.ipynb"
⚠️ Note: Make sure Python is installed and added to your system path.


---

## 🔍 Further Considerations
Bimodal distributions suggest subgroup-specific analysis.

Outliers may signal high-risk or erroneous records.

Feature selection will be important for predictive modeling.

## 📬 Contact
For suggestions or collaboration, feel free to reach out via GitHub or LinkedIn.
