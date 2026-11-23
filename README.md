# Machine-learning-Train-dataset-day20-univariate-analysis# Titanic Dataset – Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic passenger dataset using Python. It explores passenger information and uses statistical calculations and visualizations to understand the data.

## Dataset
- **Dataset:** Titanic Training Dataset
- **Source file:** `train.csv`
- **Notebook:** `day20.ipynb`
- **Data columns:** PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib

## Python Libraries

```python
import pandas as pd
import seaborn as sns
```

## Load Dataset

```python
df = pd.read_csv('train.csv')
df.head()
```

## Topics Covered

### 1. Categorical Data Analysis
- Count Plot
- Passenger Embarkation Analysis
- Pie Chart

### 2. Numerical Data Analysis
- Age Distribution
- Histogram / Distribution Plot
- Boxplot
- Minimum Age
- Maximum Age
- Average Age
- Skewness

## Statistical Analysis

The notebook performs the following calculations:

```python
df['Age'].min()
df['Age'].max()
df['Age'].mean()
df['Age'].skew()
```

### Observed Results

| Calculation | Result |
|---|---:|
| Minimum Age | 0.42 |
| Maximum Age | 80.00 |
| Average Age | 29.70 |
| Age Skewness | 0.3891 |

## Data Visualization

The notebook includes:
- Count plot for Embarked
- Age distribution plot
- Age boxplot
- Pie chart section

## Project Objectives
1. Understand the Titanic dataset.
2. Load CSV data using Pandas.
3. Explore categorical and numerical variables.
4. Create visualizations using Seaborn.
5. Calculate statistical measures.
6. Understand the distribution of passenger ages.

## How to Run the Project

1. Install Python or open Google Colab.
2. Install the required libraries:

```bash
pip install pandas seaborn matplotlib
```

3. Keep `train.csv` and `day20.ipynb` in the same folder.
4. Open `day20.ipynb` in Jupyter Notebook.
5. Run the cells one by one.

## Conclusion
This project demonstrates basic Exploratory Data Analysis using the Titanic dataset. It provides practical experience in loading data, analyzing categorical and numerical variables, calculating statistics, and creating visualizations with Python.

---

## Trainer Details

**Name:** MD SAFDAR  
**Designation:** Senior Trainer for Data Analytics  
**Institute:** Intensive Institute, New Delhi  

- **Email:** safdar.ncpul@gmail.com
- **Mobile No.:** 9810845947

---

**Prepared By:** MD SAFDAR  
**Project:** Titanic Dataset – Exploratory Data Analysis  
**Institute:** Intensive Institute, New Delhi
