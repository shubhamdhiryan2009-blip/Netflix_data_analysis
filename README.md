🎬 Netflix Movies and TV Shows Data Analysis
An exploratory data analysis (EDA) project in Python analyzing Netflix's catalog of movies and TV shows using pandas, NumPy, Matplotlib, and Seaborn.

📌 Project Overview
This project explores the netflix_titles.csv dataset containing over 8,800 titles available on Netflix. The main goal is to clean, analyze, and visualize trends regarding content types, release years, ratings, durations, and geographical distribution.

.
├── netflix_titles.csv       # Dataset containing Netflix content details
├── netflix_analysis.ipynb   # Jupyter Notebook containing data analysis & visualizations
└── README.md                # Project documentation

## 📊 Dataset Overview

The dataset contains information about **8,807 Netflix movies and TV shows** across **12 columns**. It includes details such as titles, directors, cast, countries, release years, ratings, duration, genres, and descriptions.

| # | Column Name | Non-Null Count | Data Type | Description |
|---|---|---:|---|---|
| 1 | `show_id` | 8,807 | `object` | Unique ID for every movie or TV show |
| 2 | `type` | 8,807 | `object` | Identifies whether the content is a **Movie** or **TV Show** |
| 3 | `title` | 8,807 | `object` | Title of the movie or TV show |
| 4 | `director` | 6,173 | `object` | Director of the movie or TV show |
| 5 | `cast` | 7,982 | `object` | Actors involved in the movie or TV show |
| 6 | `country` | 7,976 | `object` | Country where the movie or TV show was produced |
| 7 | `date_added` | 8,797 | `object` | Date when the content was added to Netflix |
| 8 | `release_year` | 8,807 | `int64` | Original release year of the movie or TV show |
| 9 | `rating` | 8,803 | `object` | Content rating, such as **TV-MA, PG-13, PG**, etc. |
| 10 | `duration` | 8,804 | `object` | Total duration in minutes for movies or number of seasons for TV shows |
| 11 | `listed_in` | 8,807 | `object` | Genres or categories associated with the content |
| 12 | `description` | 8,807 | `object` | Summary or description of the movie or TV show |

### 📌 Dataset Statistics

| Metric | Value |
|---|---:|
| **Total Rows** | 8,807 |
| **Total Columns** | 12 |
| **Content Types** | Movies & TV Shows |
| **Dataset Domain** | Netflix Movies & TV Shows |

🛠️ Requirements & Installation
To run the notebook locally, ensure you have Python installed along with the following libraries:
pip install pandas numpy seaborn matplotlib

🚀 How to Run
Clone the Repository
git clone https://github.com/shubhamdhiryan2009-blip/Netflix_data_analysis
cd 
Netflix_data_analysis

Launch Jupyter Notebook / Google Colab
jupyter notebook netflix_analysis.ipynb

Run All Cells to execute the data loading, inspection, and visualization steps.

📈 Analysis & Insights
Primary Key: show_id serves as a unique primary key across all 8,807 entries.

Data Completeness: Missing values are predominantly found in director, cast, and country.

Content Types: Categorized into Movies vs. TV Shows across different genres, ratings, and release years.

📝 License
This project is open-source and available under the MIT License.
