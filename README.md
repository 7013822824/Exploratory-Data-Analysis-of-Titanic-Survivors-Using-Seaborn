# 🚢 Titanic Survivors Visualization Using Seaborn

This project performs **exploratory data analysis (EDA)** on the Titanic dataset using **Seaborn**, a statistical data visualization library in Python. 
The project visualizes survival rates based on gender, passenger class, age, and fare using various plot types supported by Seaborn.

---

## 🗃️ Dataset

- **Source**: [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File Used**: `Titanic-Dataset.csv`
- Contains data for over 800 passengers including features like age, gender, class, fare, and survival status.

---

## 🧰 Technologies Used

- Python
- Google Colab / Jupyter Notebook
- **Pandas** (for data processing)
- **Seaborn** (for statistical visualization)
- **Matplotlib** (for plot display and styling)

---

## 📊 Visualizations Included

### 1. **Bar Plot**
- Survival counts by gender using `countplot`

### 2. **Box Plot**
- Distribution of age across different classes and survival status using `boxplot`

### 3. **Violin Plot**
- Distribution of age and survival by gender using `violinplot`

### 4. **Heatmap**
- Correlation between numeric features such as fare, age, and class using `heatmap`

### 5. **Pair Plot**
- Pairwise relationships between numeric features with hue based on survival using `pairplot`

---

## 🚀 How to Run

1. Download the dataset: [Titanic-Dataset.csv](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
2. Upload the CSV file to your Google Colab session or local directory.
3. Open the notebook `seaborn_titanic_visualization.ipynb`
4. Run the cells in sequence to generate visualizations.

---

## 📌 Key Insights

- Females had a much higher chance of survival than males.
- Higher passenger classes had better survival rates.
- Younger passengers were more likely to survive in some classes.
- Correlations between features like Fare, Class, and Survival are visible.

---

## 📁 Project Structure

titanic-seaborn-eda/
├── Titanic-Dataset.csv
├── seaborn_titanic_visualization.ipynb
└── README.md
