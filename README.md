<div align="center">

# Data Analysis

**A curated, version-controlled knowledge base documenting a structured journey through data analytics.**

Course notes · hands-on labs · graded assessments · Jupyter notebooks · real datasets

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](#technologies)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](#technologies)
[![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)](#technologies)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](#technologies)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](#technologies)
[![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)](#technologies)

[![Notebooks](https://img.shields.io/badge/notebooks-36-informational?style=flat-square)](#repository-structure)
[![Courses](https://img.shields.io/badge/courses-6-informational?style=flat-square)](#learning-paths)
[![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen?style=flat-square)](#learning-philosophy)

</div>

---

## Overview

This repository collects the complete body of work produced while studying data analytics: lecture takeaways, guided labs, self-directed exercises, graded quizzes with worked answers, and end-to-end analysis projects. Everything here was written or completed by hand and is committed as it is produced, so the history doubles as a learning log.

The material is organised around the **IBM Data Analyst** track, progressing from analytics fundamentals through spreadsheet analysis, dashboarding, Python programming, applied data projects, and relational databases. Each course keeps its own notes, datasets, and solutions together so any topic can be revisited in isolation.

It is written to be useful to more than one reader: as a personal reference for revision, as a study companion for anyone working through the same curriculum, and as a portfolio of practical work backed by runnable notebooks and real data.

> [!NOTE]
> This is an **educational knowledge base**, not an application. There is nothing to build, deploy, or install at the repository level — individual exercises declare their own dependencies where needed.

---

## Highlights

- 📚 **Structured learning paths** — six sequential courses, each with notes, labs, and assessments
- 🧪 **Hands-on exercises** — 36 Jupyter notebooks covering Python, pandas, NumPy, APIs, and web scraping
- 📈 **Data visualization** — charts, dashboards, and reporting in Excel, Cognos Analytics, and Google Data Studio
- 🗄️ **SQL and databases** — ER modelling, DDL scripts, and query practice against a SQLite database
- 📊 **Spreadsheet analysis** — cleaning, filtering, pivot tables, slicers, and timelines on real datasets
- 🧾 **Worked assessments** — quizzes and exams with the correct answers and the reasoning behind them
- 📦 **Real datasets included** — 22 workbooks, CSV and JSON extracts, and a SQLite database, versioned alongside the work
- 🔁 **Reproducible** — notebooks are committed with outputs, and scripts ship with pinned `requirements.txt`

---

## Repository Structure

Only the top levels are shown. Every course follows the same internal layout, so the pattern below repeats.

```
DataAnalysis/
├── learning/
│   └── courses/
│       └── ibm/
│           └── dataanalyst/
│               ├── 01-introduction-to-data-analytics/
│               ├── 02-excel-basics-for-data-analysis/
│               ├── 03-data-visualization-dashboards-excel-cognos/
│               ├── 04-python-for-data-science-ai-development/
│               ├── 05-projects-for-data-science/
|               ├── 06-databases-sql-for-data-science-python/
|               ├── 07-data-analysis-with-python/
|               ├── 08-data-visualization-with-python/
|               ├── 09-ibm-data-analyst-capstone-project/
|               ├── 10-generative-ai-enhance-data-analyst-career/
│               └── 11-data-analyst-career-guide-interview-preparation/
└── projects/
```

Inside each course:

```
<course>/
├── activities/
│   ├── articulate/       # Guided in-course activities
│   ├── hands-on/         # Step-by-step labs with datasets
│   └── practice-lab/     # Open-ended practice
├── assessments/
│   └── blackboard/       # Scored module assessments
├── checklists/           # Projects checklists
├── final-assignment/     # Capstone deliverable (naming varies per course)
├── final-exam/           # Graded final course exam questions with answers (naming varies per course)
├── final-project/        # Graded final project
├── graded-quiz/          # Graded quizzes with answers
├── practice-project/     # Ungraded practice projects
├── practice-quiz/        # Ungraded practice questions
└── resources/            # documents, cheat sheets and other resources
```

> [!TIP]
> Folders are numerically prefixed (`01-`, `02-`, …) so the intended study order matches the alphabetical order shown by Git, your file explorer, and GitHub.

---

## Learning Paths

**Track:** IBM Data Analyst — [`learning/courses/ibm/dataanalyst/`](./learning/courses/ibm/dataanalyst/)

| #   | Course                                                                                                                                        | Status      | Topics                                                                                                                                                                                                                                                                                                                         |
| :-- | :-------------------------------------------------------------------------------------------------------------------------------------------- | :---------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01  | [Introduction to Data Analytics](./learning/courses/ibm/dataanalyst/01-introduction-to-data-analytics/)                                       | ✅ C1       | Analytics fundamentals, data ecosystems, case analysis, outlier identification                                                                                                                                                                                                                                                 |
| 02  | [Excel Basics for Data Analysis](./learning/courses/ibm/dataanalyst/02-excel-basics-for-data-analysis/)                                       | ✅ C2       | Data editing and formatting, cleaning, filtering and sorting, pivot tables                                                                                                                                                                                                                                                     |
| 03  | [Data Visualization and Dashboards with Excel and Cognos](./learning/courses/ibm/dataanalyst/03-data-visualization-dashboards-excel-cognos/)  | ✅ C3       | Basic and advanced charts, Excel dashboards, Cognos Analytics, Google Data Studio                                                                                                                                                                                                                                              |
| 04  | [Python for Data Science, AI & Development](./learning/courses/ibm/dataanalyst/04-python-for-data-science-ai-development/)                    | ✅ C4       | Python core, data structures, OOP, file I/O, pandas, NumPy, REST APIs, web scraping                                                                                                                                                                                                                                            |
| 05  | [Python Project for Data Science](./learning/courses/ibm/dataanalyst/05-projects-for-data-science/)                                           | ✅ C5       | Applied extraction and visualization, stock and revenue data, dashboard building                                                                                                                                                                                                                                               |
| 06  | [Databases and SQL for Data Science with Python](./learning/courses/ibm/dataanalyst/06-databases-sql-for-data-science-python/)                | ✅ C6       | ER diagrams, relational modelling, Relational DB, Intermediate SQL, Accessing Databases using Python                                                                                                                                                                                                                           |
| 07  | [Data Analysis with Python](./learning/courses/ibm/dataanalyst/07-data-analysis-with-python/)                                                 | ✅ C7       | Importing Data Sets, Data Wrangling, Exploratory Data Analysis, Model Development, Model Evaluation and Refinement                                                                                                                                                                                                             |
| 08  | [Data Visualization with Python](./learning/courses/ibm/dataanalyst/08-data-visualization-with-python/)                                       | ✅ C8       | Data Visualization, Basic and Specialized Visualization Tools, Advanced Visualizations and Geospatial Data, Creating Dashboards with Plotty and Dash                                                                                                                                                                           |
| 09  | [IBM Data Analyst Capstone Project](./learning/courses/ibm/dataanalyst/09-data-analyst-capstone-project/)                                     | ✅ C9       | Collecting Data Using APIs & Webscraping, Exploring Data, Fiding Duplicates, Removing Duplicates, Finding Missing Values, Inputing Missing Values, Normalizing Data, Data Wrangling, Exploratory Data Analysis, Finding Outliers, Finding Correlation, Data Visualization, Building a Dashboard, Data Analyst Capstone Project |
| 10  | [Generative AI: Enhance your Data Analytics Career](./learning/courses/ibm/dataanalyst/10-generative-ai-enhance-data-analyst-career/)         | ✅&nbsp;C10 | Data Analytics and Generative AI, Use of Generative AI for Data Analytics, Generative AI Considerations in Data Analytics                                                                                                                                                                                                      |
| 11  | [Data Analyst Career Guide and Interview Preparation](./learning/courses/ibm/dataanalyst/11-data-analyst-career-guide-interview-preparation/) | ✅&nbsp;C11 | Building a Foundation, Applying and Preparing to Interview, Interviewing                                                                                                                                                                                                                                                       |

---

## Technologies

Only tools that actually appear in the repository are listed.

### Languages

| Technology | Where it is used                            |
| :--------- | :------------------------------------------ |
| **Python** | Notebooks and scripts across courses 04–05  |
| **SQL**    | Query practice and DDL scripts in course 06 |

### Data Analysis

| Technology          | Where it is used                                                               |
| :------------------ | :----------------------------------------------------------------------------- |
| **pandas**          | DataFrame loading, selection, and transformation; `read_html` table extraction |
| **NumPy**           | 1-D and 2-D array operations, numeric manipulation                             |
| **Microsoft Excel** | Cleaning, filtering, pivot tables, slicers, timelines (courses 01–03)          |

### Visualization

| Technology               | Where it is used                                     |
| :----------------------- | :--------------------------------------------------- |
| **Matplotlib**           | Plotting in Python labs and the stock data dashboard |
| **Seaborn**              | Statistical plots in the file-formats lab            |
| **IBM Cognos Analytics** | Product sales, customer, and advanced dashboards     |
| **Google Data Studio**   | Dashboard hands-on lab                               |

### Data Acquisition

| Technology                  | Where it is used                                   |
| :-------------------------- | :------------------------------------------------- |
| **Requests**                | HTTP access to REST APIs and web pages             |
| **BeautifulSoup 4**         | HTML parsing and web scraping                      |
| **lxml**                    | HTML/XML table parsing backend                     |
| **yfinance**                | Historical share price, dividend, and company data |
| **nba_api**, **randomuser** | API consumption examples                           |

### Databases

| Technology                | Where it is used                                   |
| :------------------------ | :------------------------------------------------- |
| **SQLite**                | `Company.db` schema for the HR ER-diagram activity |
| **DB Browser for SQLite** | `.sqbpro` project file accompanying the database   |
| **draw.io**               | ER diagram source for the company HR model         |

### Formats

`.ipynb` · `.xlsx` · `.csv` · `.json` · `.sql` · `.db` · `.txt` · `.html`

---

## Projects

### Extracting and Visualizing Stock Data

📁 [`05-projects-for-data-science/final-project/`](./learning/courses/ibm/dataanalyst/05-projects-for-data-science/final-project/)

Builds a comparative dashboard of share price and quarterly revenue for two companies. Price history is pulled with `yfinance`, revenue is scraped from HTML tables with BeautifulSoup, both are reconciled into pandas DataFrames, and a reusable graphing function renders the paired time series.

**Concepts** — API data extraction · HTML parsing · data cleaning and type coercion · time-series alignment · reusable plotting functions<br>
**Stack** — `yfinance` · `BeautifulSoup` · `pandas` · `Matplotlib`

---

### GDP Data Extraction and Processing

📁 [`04-python-for-data-science-ai-development/practice-project/`](./learning/courses/ibm/dataanalyst/04-python-for-data-science-ai-development/practice-project/)

Extracts the ten largest world economies by nominal GDP from an archived Wikipedia snapshot, converts the figures from millions to billions of USD, rounds to two decimals, and exports a clean CSV.

**Concepts** — web scraping · tabular normalisation · numeric transformation · CSV export<br>
**Stack** — `pandas` · `NumPy`

---

### Wikipedia Table Scrapers

📁 [`05-projects-for-data-science/webscraping/wikipedia-scraping/`](./learning/courses/ibm/dataanalyst/05-projects-for-data-science/webscraping/wikipedia-scraping/)

Two standalone scripts that fetch live Wikipedia pages and lift structured tables straight into DataFrames — the largest banks by market capitalisation, and countries ranked by nominal GDP. Both set an explicit `User-Agent` and parse via `StringIO` to avoid deprecated literal-HTML input.

**Concepts** — `pandas.read_html` · request headers · selecting the right table from a page<br>
**Stack** — `requests` · `pandas` · `lxml` · pinned [`requirements.txt`](./learning/courses/ibm/dataanalyst/05-projects-for-data-science/webscraping/wikipedia-scraping/requirements.txt)

---

### Stock Data Extraction — Library vs. Web Scraping

📁 [`05-projects-for-data-science/practice-project/`](./learning/courses/ibm/dataanalyst/05-projects-for-data-science/practice-project/)

A paired study of the same problem solved two ways: once through the `yfinance` library and once by scraping a financial web page. Raw JSON responses for AMD and Apple are committed so the results can be inspected without re-running the requests.

**Concepts** — API vs. scraping trade-offs · JSON handling · historical price and dividend data<br>
**Stack** — `yfinance` · `BeautifulSoup` · `pandas`

---

### Company HR Database — ER Model

📁 [`06-databases-sql-for-data-science-python/activities/articulate/01-build-er-diagram-company-hr-database/`](./learning/courses/ibm/dataanalyst/06-databases-sql-for-data-science-python/activities/articulate/01-build-er-diagram-company-hr-database/)

A relational HR model designed from requirements and implemented end to end: a draw.io entity-relationship diagram, a SQLite DDL script with primary keys, unique and check constraints, defaults, and a self-referencing manager foreign key, plus the materialised `Company.db`.

**Concepts** — entity-relationship modelling · normalisation · constraints and referential integrity · self-referencing keys<br>
**Stack** — `SQLite` · `draw.io` · DB Browser for SQLite

---

### Excel Dashboards and Reports

📁 [`03-data-visualization-dashboards-excel-cognos/`](./learning/courses/ibm/dataanalyst/03-data-visualization-dashboards-excel-cognos/)

Car sales and customer loyalty data turned into interactive reporting: basic and advanced chart types in Excel, a linked dashboard with slicers, and equivalent dashboards rebuilt in Cognos Analytics and Google Data Studio for comparison. Final deliverables are committed as PDFs and images.

**Concepts** — chart selection · dashboard layout · interactivity · cross-tool comparison<br>
**Stack** — `Excel` · `IBM Cognos Analytics` · `Google Data Studio`

---

## Where to Find Things

| Looking for                           | Location                                                                              |
| :------------------------------------ | :------------------------------------------------------------------------------------ |
| **Course notes and worked solutions** | `activities/` in each course, plus the `README.md` inside each exercise folder        |
| **Guided labs**                       | `activities/hands-on/`                                                                |
| **In-course activities**              | `activities/articulate/`                                                              |
| **Open practice**                     | `activities/practice-lab/`                                                            |
| **Quizzes and answers**               | `practice-quiz/` and `graded-quiz/`                                                   |
| **Scored assessments**                | `assessments/blackboard/`                                                             |
| **Capstones**                         | `final-assignment/`, `final-exam/`, or `final-project/`, depending on the course      |
| **Datasets**                          | Stored beside the exercise that uses them (`.xlsx`, `.csv`, `.json`, `.db`)           |
| **Notebooks**                         | `learning/courses/ibm/dataanalyst/**/*.ipynb`                                         |
| **Personal projects**                 | [`projects/`](./projects/) — reserved for self-directed work outside the course track |

> [!NOTE]
> [`projects/`](./projects/) is currently a placeholder. Independent, non-course analyses will land there as they are completed.

---

## How to Use This Repository

**Following the curriculum.** Start at [`01-introduction-to-data-analytics`](./learning/courses/ibm/dataanalyst/01-introduction-to-data-analytics/) and work up. Within a course, read the exercise `README.md` first, then open the notebook or workbook next to it.

**Looking up a specific topic.** Jump to the course in the [Learning Paths](#learning-paths) table, or use GitHub's file finder (press <kbd>t</kbd>) — folder names describe their contents (`15-loading-data-pandas`, `03-insert-update-delete`).

**Reviewing before an assessment.** The `graded-quiz/` and `practice-quiz/` folders hold questions with the correct answer marked and, in most cases, an explanation.

**Running the notebooks.** Notebooks are committed with their outputs and can be read on GitHub without running anything. To execute them locally:

```bash
git clone https://github.com/pfiterman/DataAnalysis.git
cd DataAnalysis

python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate

pip install jupyterlab pandas numpy matplotlib seaborn requests beautifulsoup4 lxml yfinance
jupyter lab
```

**Running the scripts.** Standalone scripts pin their own dependencies:

```bash
cd "learning/courses/ibm/dataanalyst/05-projects-for-data-science/webscraping/wikipedia-scraping"
pip install -r requirements.txt
python banks-wikipedia-scraping.py
```

> [!IMPORTANT]
> Some notebooks originate from the IBM Skills Network lab environment and reference `piplite` or `pyodide.http`, which only exist in that browser-based runtime. Replace those calls with `pip install` and `requests` to run them locally.

---

## Learning Philosophy

Knowledge that is not written down decays. This repository treats learning the way software is treated: work in small, reviewable increments, commit each one with a descriptive message, and keep the artefact next to the reasoning that produced it.

Every concept is paired with something executable — a notebook, a query, a workbook, a script. Solutions are kept even when imperfect, because the value is in the record of how a problem was approached, not only in the final answer.

---

## Contributing

This is a personal learning archive, so pull requests that add course content are not expected. Corrections and improvements, however, are genuinely welcome:

- 🐛 **Found an error?** Open an issue naming the file and describing what is incorrect.
- 💡 **Have a better approach?** Issues suggesting cleaner solutions or clearer explanations are appreciated.
- 📝 **Spotted a typo or broken link?** A small pull request is the fastest fix.

**Guidelines**

1. Keep the existing folder conventions — numeric prefixes, kebab-case names, one topic per folder.
2. Place datasets next to the exercise that uses them; do not add a central `data/` directory.
3. Strip credentials and API keys from notebooks before committing.
4. Use [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`), matching the existing history.
5. Do not commit virtual environments or caches — `.venv/`, `__pycache__/`, and `*.pyc` are already ignored.

---

## License

No license file is currently present in this repository.

Personal notes, solutions, and scripts are shared for educational reference. Course materials, datasets, and lab notebooks originating from **IBM Skills Network / Coursera** remain the property of their respective owners and are included here only as personal study records. Please respect the academic integrity policy of any course you are enrolled in — use this repository to check your understanding, not to substitute for doing the work.

---

## Author

**Pablo Fiterman**

[![GitHub](https://img.shields.io/badge/GitHub-@pfiterman-181717?style=flat-square&logo=github)](https://github.com/pfiterman)

Documenting an ongoing path into data analytics — from spreadsheets and dashboards to Python, SQL, and applied data projects. Questions, corrections, and suggestions are welcome via [issues](https://github.com/pfiterman/DataAnalysis/issues).

<div align="center">

---

⭐ If this repository helps your own studies, consider starring it.

</div>
