# ⚽ Football Analytics with Python

> **A hands-on, beginner-friendly course that teaches Python & data science through the lens of football (soccer).**  
> Go from zero Python knowledge to building match dashboards and ML prediction models — all with real football data.

---

## 📖 Table of Contents

- [Why This Course?](#-why-this-course)
- [What You'll Learn](#-what-youll-learn)
- [Course Roadmap](#-course-roadmap)
- [Quick Start](#-quick-start)
- [Module Breakdown](#-module-breakdown)
  - [Module 1 — Python Fundamentals](#module-1--python-fundamentals)
  - [Module 3 — Getting Football Data](#module-3--getting-football-data)
  - [Module 4 — Visualisation & Plotting](#module-4--visualisation--plotting)
  - [Module 5 — Data Analysis & Statistics](#module-5--data-analysis--statistics)
  - [Module 6 — Machine Learning](#module-6--machine-learning)
  - [Projects — Putting It All Together](#projects--putting-it-all-together)
- [Repo Structure](#-repo-structure)
- [Recommended Learning Path](#-recommended-learning-path)
- [Tech Stack](#-tech-stack)
- [FAQ](#-faq)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 Why This Course?

Most Python courses use abstract examples. This one uses **real football data** — shots, passes, xG, match results — so every concept clicks immediately. Whether you want to break into football analytics, build a data portfolio, or just learn Python in a way that's actually fun, this is the place.

---

## 🧠 What You'll Learn

| Skill | You'll be able to… |
|---|---|
| **Python** | Write clean scripts, handle errors, use functions & loops |
| **Web Scraping** | Pull data from FBref, Sofascore, Understat, WhoScored & more |
| **APIs** | Query the StatsBomb open-data API |
| **Data Wrangling** | Clean, transform & analyse data with Pandas & NumPy |
| **Visualisation** | Build scatter plots, radar charts, shotmaps, pass networks, xG flow charts |
| **Statistics** | Understand correlation, distributions & basic stats in football |
| **Machine Learning** | Train classification, regression & clustering models on football data |
| **Projects** | Build a full match dashboard and a match-outcome prediction model |

---

## 🗺️ Course Roadmap

```
Module 1                Module 3              Module 4
Python Basics  ──────►  Data Collection  ──►  Visualisation
                                │                   │
                                ▼                   ▼
                          Module 5              Module 6
                          Data Analysis  ──►    Machine Learning
                                                    │
                                                    ▼
                                               Projects
                                          Dashboards & Prediction
```

---

## 🚀 Quick Start

### Prerequisites

- [Python 3.9+](https://www.python.org/downloads/) installed
- [Git](https://git-scm.com/) (to clone the repo)
- Basic comfort with a terminal / command prompt

### 1. Clone the repository

```bash
git clone https://github.com/danishsyed-dev/Football_Python_Course.git
cd Football_Python_Course
```

### 2. Create a virtual environment *(recommended)*

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Then open any notebook and start learning! 🎉

> **💡 Tip:** Start with `Module - 1/1.1 Python Syntax.ipynb` if you're brand new to Python.

---

## 📚 Module Breakdown

### Module 1 — Python Fundamentals

> *Start here if you've never written a line of Python.*

| # | Notebook | What You'll Learn |
|---|---|---|
| 1.1 | `Python Syntax.ipynb` | How Python code is structured — indentation, statements, comments |
| 1.2 | `Python Variables.ipynb` | Storing and naming data with variables |
| 1.3 | `Python Data Types.ipynb` | Strings, integers, floats, lists, dictionaries and more |
| 1.4 | `If .. Else.ipynb` | Conditional logic — making decisions in code |
| 1.5 | `Loops.ipynb` | `for` and `while` loops to repeat actions |
| 1.6 | `Functions.ipynb` | Writing reusable blocks of code |
| 1.7 | `Error Handling.ipynb` | Understanding and handling Python errors gracefully |

---

### Module 3 — Getting Football Data

> *Learn how to collect real football data from the web and APIs.*

| # | Notebook | What You'll Learn |
|---|---|---|
| 3.1 | `Web Scraping Basics.ipynb` | Intro to web scraping with `requests` & `BeautifulSoup` |
| 3.1.1 | `Web Scraping Basics (Self).ipynb` | Practice notebook — try scraping on your own |
| 3.1.2 | `Web Scraping Basics Updated.ipynb` | Updated scraping techniques |
| 3.2 | `Statsbomb API.ipynb` | Access StatsBomb's free event data (passes, shots, lineups) |
| 3.2.1 | `Statsbomb (Self).ipynb` | Practice notebook — explore StatsBomb data yourself |
| 3.3 | `FBREF.ipynb` | Scrape player & team stats from FBref |
| 3.4 | `Sofascore.ipynb` | Scrape shot data from Sofascore using Playwright |
| 3.4.1 | `Sofascore.ipynb` | Extended Sofascore scraping |
| 3.5 | `Understat.ipynb` | Pull xG and shot data from Understat |
| 3.5 / 3.6 | `Fotmob.ipynb` | Fetch match & player data from FotMob |
| 3.7 | `Whoscored.ipynb` | Scrape advanced stats from WhoScored |
| 3.8 | `Soccerdata.ipynb` | Use the `soccerdata` package to scrape from multiple sources |

> **⚠️ Note:** Some scrapers use browser automation (Playwright, undetected-chromedriver). Make sure to run `playwright install` after installing requirements if you plan to use those notebooks.

---

### Module 4 — Visualisation & Plotting

> *Turn raw data into beautiful, publication-ready football graphics.*

| # | Notebook | What You'll Learn |
|---|---|---|
| 4.1 | `Matplotlib, Seaborn, and mplsoccer.ipynb` | Foundations of plotting in Python |
| 4.2 | `Scatter Plots.ipynb` | Visualise relationships between two variables |
| 4.3 | `Radar Charts.ipynb` | Compare player stats in a circular layout |
| 4.4 | `Pizza Plots.ipynb` | An alternative to radar charts (popularised by analytics Twitter) |
| 4.5 | `Tables.ipynb` | Create clean, styled tables with `tabulate` |
| 4.6 | `xG Flow Charts.ipynb` | Plot the flow of expected goals through a match |
| 4.7 | `Plotting a Pitch.ipynb` | Draw a football pitch using `mplsoccer` |
| 4.8 | `Passmaps.ipynb` | Visualise a player's or team's pass patterns |
| 4.9 | `Shotmaps.ipynb` | Plot shot locations on a pitch |
| 4.10 | `Heatmaps.ipynb` | Show player positioning and activity zones |
| 4.11 | `Pass Networks.ipynb` | Map passing connections between teammates |
| 4.12 | `Grids.ipynb` | Arrange multiple plots into a single figure |

---

### Module 5 — Data Analysis & Statistics

> *Clean, analyse, and draw insights from football datasets.*

| # | Notebook | What You'll Learn |
|---|---|---|
| 5.1 / 5.2 | `Pandas & Numpy.ipynb` | Core data manipulation with Pandas and numerical computing with NumPy |
| 5.3 | `Cleaning Data.ipynb` | Handle missing values, duplicates, and messy data |
| 5.4 | `Basic Statistics.ipynb` | Mean, median, standard deviation & distributions in football |
| 5.5 | `Correlation.ipynb` | Measure and visualise relationships between football metrics |

**Included datasets:**
- `big5.csv` — Raw Big 5 European leagues data
- `big5-clean.csv` — Cleaned version for analysis

---

### Module 6 — Machine Learning

> *Apply ML algorithms to real football problems.*

| # | Notebook | What You'll Learn |
|---|---|---|
| 6.1 | `The idea behind machine learning.ipynb` | The ML pipeline — from data to predictions |
| 6.2 | `Supervised vs Unsupervised.ipynb` | Key differences and when to use each |
| 6.3 | `Classification.ipynb` | Predict categorical outcomes (e.g., win/loss) |
| 6.4 | `Regression.ipynb` | Predict continuous values (e.g., goals, points) |
| 6.5 | `Clustering.ipynb` | Group similar players/passes with K-Means |
| 6.6 | `Model Evaluation.ipynb` | Confusion matrices, accuracy, precision, recall & more |

**Included datasets:**
- `classification_data.csv` — Labelled data for classification exercises
- `historical_prem_standings.csv` — Historical Premier League standings for regression

---

### Projects — Putting It All Together

> *Capstone projects that combine everything you've learned.*

| Project | Notebook | Description |
|---|---|---|
| **1 — Match Dashboard** | `Project-1-Match-Dashboards.ipynb` | Build a comprehensive match dashboard with shotmaps, pass networks and xG flow charts |
| **2 — Match Prediction** | `Project-2-Match-Prediction.ipynb` | Train an ML model to predict football match outcomes |
| *Data Gathering* | `project-2-data-gathering.ipynb` | Collect and prepare the dataset for Project 2 |

**Included datasets:**
- `project2.csv` — Pre-gathered match data for Project 2

---

## 📁 Repo Structure

```
Football_Python_Course/
│
├── Module - 1/                 # Python fundamentals (7 notebooks)
│   ├── 1.1 Python Syntax.ipynb
│   ├── 1.2 Python Variables.ipynb
│   ├── 1.3 Python Data Types.ipynb
│   ├── 1.4 If .. Else.ipynb
│   ├── 1.5 Loops.ipynb
│   ├── 1.6 Functions.ipynb
│   └── 1.7 Error Handling.ipynb
│
├── Module - 3/                 # Data collection & web scraping (13 notebooks)
│   ├── 3.1 Web Scraping Basics.ipynb
│   ├── 3.2 Statsbomb API.ipynb
│   ├── 3.3 FBREF.ipynb
│   ├── 3.4 Sofascore.ipynb
│   ├── 3.5 Understat.ipynb
│   ├── 3.6 Fotmob.ipynb
│   ├── 3.7 Whoscored.ipynb
│   ├── 3.8 Soccerdata.ipynb
│   └── ... (+ self-practice notebooks)
│
├── Module - 4/                 # Visualisation & plotting (12 notebooks)
│   ├── 4.1 Matplotlib, Seaborn, and mplsoccer.ipynb
│   ├── 4.2 Scatter Plots.ipynb
│   ├── 4.3 Radar Charts.ipynb
│   ├── ...
│   └── 4.12 Grids.ipynb
│
├── Module - 5/                 # Data analysis & statistics (4 notebooks + 2 CSVs)
│   ├── 5.1 Pandas & 5.2 Numpy.ipynb
│   ├── 5.3 Cleaning Data.ipynb
│   ├── 5.4 Basic Statistics.ipynb
│   ├── 5.5 Correlation.ipynb
│   ├── big5.csv
│   └── big5-clean.csv
│
├── Module - 6/                 # Machine learning (6 notebooks + 2 CSVs)
│   ├── 6.1 The idea behind machine learning.ipynb
│   ├── 6.2 Supervised vs Unsupervised.ipynb
│   ├── ...
│   └── 6.6 Model Evaluation.ipynb
│
├── Projects/                   # Capstone projects (3 notebooks + 1 CSV)
│   ├── Project-1-Match-Dashboards.ipynb
│   ├── Project-2-Match-Prediction.ipynb
│   ├── project-2-data-gathering.ipynb
│   └── project2.csv
│
├── requirements.txt            # All Python dependencies
└── README.md                   # You are here!
```

---

## 🛤️ Recommended Learning Path

Follow this order for the smoothest experience:

```
1️⃣  Module 1  →  Get comfortable with Python syntax, variables, loops & functions
2️⃣  Module 5  →  Learn Pandas & NumPy — the backbone of data work
3️⃣  Module 3  →  Collect real football data via scraping & APIs
4️⃣  Module 4  →  Visualise your data with professional-quality charts
5️⃣  Module 5  →  Revisit for statistics & correlation analysis
6️⃣  Module 6  →  Dive into machine learning with football data
7️⃣  Projects  →  Build your portfolio with the capstone projects
```

> **🔁 Note:** Modules 3–5 can be explored in any order after Module 1 — the path above is just a suggestion for the best flow.

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Language** | Python 3.9+ |
| **Notebooks** | Jupyter Notebook |
| **Data** | Pandas, NumPy, PyArrow |
| **Visualisation** | Matplotlib, Seaborn, mplsoccer, highlight-text |
| **Scraping** | Requests, BeautifulSoup, Playwright, Cloudscraper, undetected-chromedriver |
| **Football Data** | statsbombpy, soccerdata |
| **ML** | scikit-learn |
| **Tables** | tabulate |

---

## ❓ FAQ

<details>
<summary><b>Do I need to know Python before starting?</b></summary>

No! Module 1 covers Python from absolute zero. If you can install Python and open a terminal, you're ready.
</details>

<details>
<summary><b>Why is there no Module 2?</b></summary>

Module 2 may cover additional topics not yet included in this repository, or it may be structured differently in the full course. The numbering follows the original course curriculum.
</details>

<details>
<summary><b>What are the "(Self)" notebooks?</b></summary>

These are practice notebooks where you can try things on your own. They follow the same topic as their parent notebook but give you space to experiment without guided solutions.
</details>

<details>
<summary><b>Some scrapers aren't working — what do I do?</b></summary>

Web scraping depends on the structure of external websites, which can change. If a scraper breaks:
1. Check if the website's HTML structure has changed
2. Make sure all dependencies are installed (`pip install -r requirements.txt`)
3. For Playwright notebooks, run `playwright install` to download browser binaries
4. Try the `soccerdata` package (Notebook 3.8) as a more stable alternative
</details>

<details>
<summary><b>Can I use this for my own projects?</b></summary>

Absolutely! The skills and code patterns here are designed to be reusable. The capstone projects are great portfolio pieces too.
</details>

---

## 🤝 Contributing

Contributions are welcome! If you find a bug, have a suggestion, or want to add a new notebook:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/new-notebook`)
3. Commit your changes (`git commit -m "Add new notebook on XYZ"`)
4. Push to the branch (`git push origin feature/new-notebook`)
5. Open a Pull Request

---

## 🙏 Credits & Acknowledgements

This repository is based on the **Complete Football Analytics** course by **[McKay Johns](https://www.youtube.com/@McKayJohns)**.

| Resource | Link |
|---|---|
| 🎬 YouTube Channel | [@McKayJohns](https://www.youtube.com/@McKayJohns) |
| 📺 Course Playlist | [Complete Football Analytics with Python](https://www.youtube.com/watch?v=fRt7IkhV99I&list=PL10a1_q15Hwpjw9bPoks8S6IFUVDO0PE7) |
| 💻 Original GitHub Repo | [mckayjohns/complete-football-analytics](https://github.com/mckayjohns/complete-football-analytics) |

> If you find this content valuable, please support McKay by subscribing to his channel and starring his original repo!

---

## 📄 License

This project is for educational purposes. Please check individual data source terms of service before using scraped data commercially.

---

<div align="center">

**⭐ If this repo helped you, give it a star!**

*Built with ❤️ for the football analytics community*

</div>
