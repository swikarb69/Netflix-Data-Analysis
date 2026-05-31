# 🎬 Netflix Data Analysis

An exploratory data analysis (EDA) of Netflix's content library using Python. This project analyzes trends in genres, countries, release years, content types, and movie durations through data cleaning and visualization.

---

## 📊 Analysis Questions

1. **What are the most common genres on Netflix?**
2. **Which countries produce the most content?**
3. **How have content releases trended over the years?**
4. **How do Movies compare to TV Shows over time?**
5. **What does the distribution of movie durations look like?**

---

## 📁 Project Structure

```
Netflix-Data-Analysis/
│
├── README.md
├── requirements.txt
├── Netflix_Data_Analysis.ipynb
└── data/
    └── netflix_titles.csv
```

---

## 🗂️ Dataset

- **Source:** [Netflix Movies and TV Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File:** `netflix_titles.csv`
- **Size:** ~8,800 titles
- **Columns include:** title, type, director, cast, country, date_added, release_year, rating, duration, listed_in (genres), description

> Download the dataset from Kaggle and place it in the project root folder before running the notebook.

---

## 🔧 Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and manipulation |
| `matplotlib` | Base plotting |
| `seaborn` | Statistical visualizations |

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Download the dataset**

Download `netflix_titles.csv` from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and place it in the project root folder.

**4. Launch Jupyter Notebook**
```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

---

## 📈 Key Findings

- **International Movies** is the most tagged genre (~2,750 titles), reflecting Netflix's global content push
- **The United States** dominates production with 3,600+ titles — more than all other top countries combined
- **2018 was Netflix's peak year** for content releases, with ~1,150 new titles added
- **Movies consistently outnumber TV Shows**, but both surged through the 2010s
- Most Netflix movies run between **90–100 minutes**, the classic feature-film sweet spot

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-linkedin](https://linkedin.com/in/your-linkedin)