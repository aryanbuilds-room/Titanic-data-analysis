# 🚢 Titanic Dataset – Data Cleaning & Preprocessing

## 📌 Project Overview

Welcome to my **Titanic Data Cleaning Project!**

This project focuses on exploring, cleaning, and preprocessing the famous Titanic dataset using Python and Pandas.

Real-world datasets often contain missing values, duplicate records, inconsistent information, and incorrect data types. The purpose of this project is to understand these problems and apply practical data cleaning techniques to make raw data more organized and suitable for further analysis.

This project represents my hands-on learning journey in Python, Pandas, and Data Analytics.

## 📂 Dataset Source

The dataset used in this project was obtained from **Kaggle**.

- **Dataset Name:** Titanic-datasets(1).
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Platform:** Kaggle

The dataset contains passenger information such as Name, Age, Gender, Ticket, Fare, Cabin, Passenger Class, and Survival Status.

It was used to perform data cleaning, handle missing values, explore passenger information, and prepare the data for further analysis.


## 🎯 Project Objectives

- Understand the structure of a real-world dataset.
- Identify missing and inconsistent values.
- Handle missing data using appropriate techniques.
- Detect and remove duplicate records.
- Explore categorical and numerical columns.
- Perform basic data transformation.
- Generate a clean CSV dataset for further analysis.

## 🛠️ Technologies & Tools Used

| Technology       | Application                         |
| :--------------- | :---------------------------------- |
| Python           | Core programming language           |
| Pandas           | Data manipulation and cleaning      |
| NumPy            | Numerical operations                |
| Google Colab     | Cloud-based coding environment      |
| Jupyter Notebook | Interactive Python notebook         |
| GitHub           | Project hosting and version control |

## 📊 About the Dataset

The Titanic dataset contains passenger information from the RMS Titanic, including passenger demographics, ticket information, and survival status.

**Dataset Features:**

| Column      | Description                       |
| :---------- | :-------------------------------- |
| PassengerId | Unique passenger identification   |
| Survived    | Survival status (0 = No, 1 = Yes) |
| Pclass      | Passenger ticket class            |
| Name        | Passenger name                    |
| Sex         | Passenger gender                  |
| Age         | Passenger age                     |
| SibSp       | Number of siblings/spouses aboard |
| Parch       | Number of parents/children aboard |
| Ticket      | Ticket number                     |
| Fare        | Ticket fare                       |
| Cabin       | Cabin number                      |
| Embarked    | Port of embarkation               |

## 🧹 Data Cleaning Workflow

The project covers the following data preparation techniques:

### 1. Data Exploration

- `head()` – Display the first five rows.
- `tail()` – Display the last five rows.
- `shape` – Check dataset dimensions.
- `info()` – Examine columns and data types.
- `describe()` – Generate statistical summaries.

### 2. Missing Value Handling

- `isnull()` – Identify missing values.
- `isnull().sum()` – Count missing values in each column.
- `fillna()` – Replace missing values.
- `dropna()` – Remove rows with missing values when appropriate.

### 3. Duplicate Data Handling

- `duplicated()` – Identify duplicate records.
- `drop_duplicates()` – Remove duplicate records.

### 4. Categorical Data Analysis

- `value_counts()` – Count occurrences of unique values.
- `unique()` – Find unique categories.
- `nunique()` – Count distinct values.

### 5. Data Transformation

- Clean column names.
- Handle inconsistent text values.
- Convert data types where required.
- Prepare the dataset for further analysis.

### 6. Exporting Cleaned Data

- Export the processed dataset using Pandas `to_csv()`.
- Save the final output as a separate CSV file.

## 📁 Project Structure

```text
Titanic-Data-Cleaning/
│
├── ARYAN CHAURASIA 2026B01010175.ipynb
│
├── Titanic-Dataset (1).csv
│
├── Titanic-cleaned_data (1).csv
│
└── README.md
```

| File                                  | Description                                          |
| :------------------------------------ | :--------------------------------------------------- |
| `ARYAN CHAURASIA 2026B01010175.ipynb` | Python notebook containing the data cleaning process |
| `Titanic-Dataset (1).csv`             | Original raw dataset                                 |
| `Titanic-cleaned_data (1).csv`        | Processed and cleaned dataset                        |
| `README.md`                           | Project documentation                                |

## 📈 Project Output

The project generates a cleaned Titanic dataset in CSV format.

The cleaned file can be used for:

- Exploratory Data Analysis (EDA).
- Data visualization.
- Passenger survival analysis.
- Further data preprocessing.
- Machine learning experiments.

## 📚 Key Learnings

By completing this project, I gained practical experience in:

- Working with real-world datasets.
- Data inspection and exploration.
- Handling missing values.
- Detecting duplicate records.
- Data manipulation using Pandas.
- Understanding numerical and categorical data.
- Exporting cleaned datasets.
- Using Google Colab and GitHub for project development.

## 🚀 How to Run This Project

**Step 1:** Clone or download this repository.

**Step 2:** Open Google Colab.

**Step 3:** Upload the Jupyter Notebook.

**Step 4:** Upload the original Titanic CSV dataset.

**Step 5:** Execute the notebook cells sequentially.

**Step 6:** Download the cleaned CSV output.

## 🔮 Future Improvements

I plan to extend this project by exploring:

- Exploratory Data Analysis (EDA).
- Data visualization using Matplotlib and Seaborn.
- Passenger survival rate analysis.
- Survival comparison based on gender and passenger class.
- Feature engineering.
- Machine learning-based survival prediction.

## 👨‍💻 About Me

**Aryan Chaurasia**

🎓 B.Tech – Computer Science & Engineering

