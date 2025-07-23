# -Web-Scraping-with-Pandas

# 🏟️ Football Data Aggregator with Pandas

This project collects and organizes historical football match data from the [Football-Data.co.uk](https://www.football-data.co.uk/data.php) website using Python and pandas.

---

## 📌 What This Project Does

- Reads `.csv` files directly from a URL
- Collects football match data for multiple:
  - **Leagues** (e.g., Premier League, League One, La Liga, etc.)
  - **Seasons** (2015–2020)
- Cleans the data (e.g., renames columns like `FTHG`, `FTAG`, etc.)
- Adds a new column: `season`
- Merges all CSVs into a single dataset per league
- Organizes all data in a dictionary for easy access

---

## 🔄 Key Functionalities

- 📥 Load `.csv` files from live URLs using `pd.read_csv()`
- 🔁 Loop through multiple leagues and seasons
- 🧹 Rename and clean columns
- 🗃️ Store DataFrames in a dictionary (`dict_historical_data`) using league names as keys

---

## 🛠️ Technologies Used

- Python 3.x
- pandas
- Jupyter Notebook

---

## 📁 Files

- `Pandas_firstProject.ipynb` — Main notebook with all data processing code.
- CSV files are **fetched live** from the internet.

---

## 📊 Sample Data Sources

All CSVs are from: https://www.football-data.co.uk/data.php

## 📬 Contact

Created by **Parul Gupta**  
Feel free to reach out via [GitHub](https://github.com/parulll13) or open issues for suggestions!

---

## ✅ Status

This project is complete as a basic data ingestion tool, but can be extended with:
- Match analytics and visualization
- Betting odds analysis
- Machine learning models
