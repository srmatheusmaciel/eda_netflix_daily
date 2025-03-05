# Netflix Daily Top 10 Analysis

## 📊 Project Overview

This repository contains an Exploratory Data Analysis (EDA) of the Netflix Daily Top 10 dataset, providing insights into Netflix's most popular content over time.

## 🚀 Project Structure

```
eda_netflix_daily/
│
├── datasets/
│   └── netflixdailytop10.csv
│
├── notebooks/
│   └── estatistica_netflix_daily.ipynb
│
├── Pipfile
├── Pipfile.lock
└── README.md
```

## 📋 Dataset Information

### Data Characteristics
- **Total Entries**: 7,100 records
- **Columns**: 10 key features capturing Netflix top content metrics

### Columns Description
1. `as_of`: Date of the ranking
2. `rank`: Content ranking position
3. `year_to_date_rank`: Cumulative ranking for the year
4. `last_week_rank`: Previous week's ranking
5. `title`: Content title
6. `type`: Content type (e.g., Movie, Series)
7. `netflix_exclusive`: Exclusive Netflix content status
8. `netflix_release_date`: Original release date on Netflix
9. `days_in_top_10`: Number of days in top 10 ranking
10. `viewership_score`: Popularity metric

### Data Quality
- **Null Values**: 
  - `netflix_exclusive`: 2,501 missing entries
- **Data Types**: 
  - 3 Numeric columns (int64)
  - 7 Object/String columns

## 🛠 Technologies & Tools

- **Language**: Python 3.11
- **Key Libraries**: 
  - Pandas
  - Matplotlib
  - Datetime

## 🔍 EDA Highlights

The analysis focused on:
- Data type exploration
- Temporal analysis of the dataset
- Database size and structure
- Null value investigation
- Outlier detection

## 🏁 Getting Started

### Prerequisites
- Python 3.11
- Pipenv
- pyenv

### Installation
```bash
# Clone the repository
git clone https://github.com/srmatheusmaciel/eda_netflix_daily.git

# Install dependencies
pipenv install

# Activate virtual environment
pipenv shell

# Run the notebook
jupyter notebook notebooks/estatistica_netflix_daily.ipynb
```


## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

## 📄 License
MIT License

## 👥 Contact
- GitHub: https://github.com/srmatheusmaciel
- LinkedIn: https://www.linkedin.com/srmatheusmaciel
