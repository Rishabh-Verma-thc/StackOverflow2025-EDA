# 📊 StackOverflow 2025 — Exploratory Data Analysis (EDA)
<p align="center"> <img src="https://img.shields.io/badge/Python-3.10+-blue" /> <img src="https://img.shields.io/badge/Jupyter-Notebook-orange" /> <img src="https://img.shields.io/badge/Status-In+Progress-yellow" /> <img src="https://img.shields.io/badge/EDA-Data%20Analysis-green" /> </p>

### This repository contains data cleaning and exploratory analysis of the StackOverflow Developer Survey 2025 dataset.

### The aim is to transform raw survey data into analysis-ready format and uncover trends, behaviors, and insights about the global developer community.

# 📂 Dataset

This project uses the **Stack Overflow Developer Survey 2025 dataset**.

Due to the large file size, the dataset is not included in the repository.
You must download it manually from the official source:

🔗 Download page:
https://survey.stackoverflow.co/

After downloading, place the following files inside the datasets/ folder:

```
datasets/
│── survey_results_public.csv
└── survey_results_schema.csv
```

The notebook expects this structure, so **do not** rename the files.


# 🎯 Project Objectives

- Clean and preprocess the raw StackOverflow 2025 dataset
- Standardize column names, formats, and categories
- Remove missing or inconsistent entries
- Analyze key areas such as:
- Developer demographics
- Technologies used
- Salary distribution
- Experience and learning patterns
- Work preferences
- Visualize important trends using charts
- Summarize insights for decision-making


# 🧽 Data Cleaning Summary

### The cleaning workflow includes:
- Handling missing/null values
- Fixing incorrect datatypes
- Normalizing text fields
- Consolidating categories
- Extracting structured values
- Exporting cleaned CSVs to datasets/cleaned/

> Full process is available in the notebook: notebooks/01_cleaning.ipynb


# 📊 Exploratory Data Analysis (EDA)

### The EDA notebook (coming next) will include:
- Developer role distribution
- Technology usage and popularity
- Salary distribution by region, experience, and role
- Work-style preferences
- Correlation heatmaps
- Country-level comparisons

### Charts will include:
- Histograms
- Bar charts
- Boxplots
- Line graphs (if applicable)
- Correlation matrices

> Notebook to be added soon.


# 🛠️ Tech Stack

- `Python` — Core language
- `Pandas` — Data manipulation
- `Matplotlib` — Visualization
- `Jupyter Notebook` — Experimentation
- `IPykernel` — Notebook kernel management


# 🏁 How to Run the Project

1. Clone the repo:
    ```
    git clone https://github.com/yourusername/yourrepo.git
    ```

2. Create the datasets/ folder if it doesn’t exist:
    ```
    mkdir datasets
    ```

3. Download the dataset from the official Stack Overflow survey page.
4. Place the CSV files inside:
    ```
    datasets/
    ```
5. Install dependencies:
    ``` 
    pip install -r requirements.txt
    ```

# 📌 Project Status

- 🔄 In Progress
- ✔ Folder structure setup
- ✔ Raw data added
- ✔ Data cleaning complete
- ⬜ EDA notebook
- ⬜ Visualization gallery
- ⬜ Final insights summary


# 📜 License

This project is for educational and analytical use.