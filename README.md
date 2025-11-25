# 📊 StackOverflow 2025 — Exploratory Data Analysis (EDA)
<p align="center"> <img src="https://img.shields.io/badge/Python-3.10+-blue" /> <img src="https://img.shields.io/badge/Jupyter-Notebook-orange" /> <img src="https://img.shields.io/badge/Workflow-Structured-green" /> <img src="https://img.shields.io/badge/Status-Completed-brightgreen" /> </p>

A full end-to-end data cleaning and exploratory analysis project using the Stack Overflow Developer Survey 2025.
This repository reflects a real-world data analyst workflow: cleaning 30+ raw columns, organizing EDA into thematic sections, and extracting insights supported by visualizations.

The aim is to transform raw survey data into analysis-ready format and uncover trends, behaviors, and insights about the global developer community.

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

- Clean and preprocess 30+ relevant survey columns  
- Remove or impute missing, noisy, or inconsistent entries  
- Conduct structured, multi-section EDA  
- Analyze:
  - Developer demographics  
  - Technology preferences  
  - Salary and compensation patterns  
  - Education & learning behavior  
  - AI adoption & sentiment  
  - Work preferences  
  - Country-level comparisons  
- Generate meaningful visualizations and insights 


# 🧽 Data Cleaning Summary

The cleaning workflow includes:

- Handling missing/null values  
- Fixing/changing datatype inconsistencies  
- Normalizing textual responses  
- Standardizing category labels  
- Parsing multi-response fields   
- Exporting to clean dataset

📘 Detailed cleaning notebook:  
`notebooks/SO_2025-clean.ipynb`


# 📊 Exploratory Data Analysis (EDA)

The EDA notebook covers **six major analytical themes**, each containing multiple structured questions.

### Topics include:
- 🌍 Developer demographics  
- 🛠 Technology stacks  
- 🤖 AI usage & sentiment patterns  
- 💼 Salary and earnings  
- 🎓 Developer experience  
- 🧑‍💻 Professional work environments   

📘 Full EDA notebook:  
`notebooks/SO_2025-EDA-insights.ipynb`


# 📝 Key Insights (Preview)

- **Accumulating experience** and the **choice of field** play crucial roles in achieving higher-paying job outcomes.
- **Web technologies** and **data/automation technologies** dominate the landscape of modern developer workflows.
- **Full-stack**, **front-end**, and **back-end** roles remains the most common entry-level pathways for early-career developers.
- AI adoption is widespread, with **OpenAI leading the ecosystem**.
- Developers show a **strongly positive** outlook on AI in the workplace.

📘 Full summary report notebook:  
`notebooks/SO_2025-summary-report.ipynb`

# 🖼️ Visualization Gallery

### Countries by Average Salary
![Top 20 Countries by Average Salary](visualization/country_avgSalary(hbar).png)

### Average Salary by Work Exp
![Average Salary by Work Exp](visualization/AvgSalary_workExp(line).png)

### Most used Programming Languages
![Top 10 most used Programming Languages](visualization/progLang_usage(hbar).png)

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

# 📜 License

This project is for educational and analytical use.  
Not affiliated with Stack Overflow or Stack Exchange.

