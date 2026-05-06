# 🧠 Neurovault Brain Data Analysis

> Exploratory data analysis of real brain imaging studies using the NeuroVault public API.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat-square&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-3-003B57?style=flat-square&logo=sqlite)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)

---

## 📌 About the Project

[NeuroVault](https://neurovault.org/) is a public repository of unthresholded statistical brain maps from real neuroscience research studies worldwide. This project uses its open REST API to extract, clean, analyze, and visualize that data — with no API key required.

The goal is twofold: build a real end-to-end data analysis portfolio project, and explore what the global neuroscience research community looks like through data.

**Questions this project answers:**
- How has brain imaging research grown over time?
- Which institutions publish the most studies?
- What are the most common research modalities (fMRI, MRI, PET...)?
- Are there patterns in how studies are structured?

---

## 🗂️ Project Structure

```
Neurovault-Brain-Data-Analysis/
│
├── data/
│   ├── raw/                  # Original data from the API (CSV)
│   └── processed/            # Cleaned and transformed data
│
├── notebooks/
│   ├── 01_extraction.ipynb       # API consumption & data saving
│   ├── 02_cleaning.ipynb         # Data cleaning with Pandas
│   ├── 03_sql_analysis.ipynb     # SQL queries with SQLite
│   ├── 04_visualization.ipynb    # Charts and visual storytelling
│   └── 05_summary.ipynb          # Key findings and conclusions
│
├── src/
│   └── api_client.py         # Reusable functions for the API
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| `Python 3.10+` | Main programming language |
| `requests` | HTTP calls to the NeuroVault API |
| `pandas` | Data manipulation and cleaning |
| `sqlite3` | Local database storage and SQL queries |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical charts |
| `jupyter` | Interactive notebooks |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Valbu11/Neurovault-Brain-Data-Analysis.git
cd Neurovault-Brain-Data-Analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the first notebook
```bash
jupyter notebook notebooks/01_extraction.ipynb
```

> No API key needed. The NeuroVault API is completely public and free.

---

## 📓 Notebooks

### `01_extraction.ipynb` — Data Extraction
Connects to the NeuroVault REST API, handles pagination, and saves collections and images as CSV files.

### `02_cleaning.ipynb` — Data Cleaning
Handles null values, fixes data types, parses dates, and prepares the dataset for analysis.

### `03_sql_analysis.ipynb` — SQL Analysis
Loads cleaned data into a SQLite database and answers business-style questions using pure SQL queries.

### `04_visualization.ipynb` — Visualization
Creates bar charts, line plots, heatmaps and distribution plots to communicate the findings visually.

### `05_summary.ipynb` — Summary & Findings
Consolidates the key insights from the analysis in a narrative format.

---

## 📊 Key Findings

> ⏳ *This section will be updated as the analysis progresses.*

---

## 🌱 What I Learned

> ⏳ *To be completed at the end of the project.*

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🙋 Author

**Valbu11**  
Aspiring data analyst • Learning in public  
[GitHub](https://github.com/Valbu11)
