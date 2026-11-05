# 🎬 Netflix Data Analysis

An Exploratory Data Analysis (EDA) project exploring Netflix Movies and TV Shows using Python, Pandas, Matplotlib, and Seaborn.

The goal of this project is to explore Netflix's content library, identify interesting patterns, and understand how its content varies across genres, countries, release years, and content ratings.

## 📌 Project Overview

This project uses the Netflix Movies and TV Shows dataset containing **8,807 titles and 12 attributes**.

Through data cleaning, exploration, and visualization, the project investigates:

- The distribution of Movies and TV Shows.
- Countries contributing the most titles.
- The most common genres on Netflix.
- Content release trends over the years.
- Distribution of content ratings.
- Directors with the highest number of titles.
- Netflix content additions over time.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |

## 📂 Project Structure

```text
Netflix-Data-Analysis/
│
├── netflix_analysis.ipynb   # Main analysis notebook
├── netflix_titles.csv       # Netflix dataset
├── README.md                # Project documentation
└── .gitignore               # Ignored files
```

## 📊 Analysis Performed

### 1. Movies vs TV Shows
Compared the number of Movies and TV Shows available in the dataset.

### 2. Country-wise Analysis
Identified the countries contributing the highest number of Netflix titles.

### 3. Genre Analysis
Explored the most frequently occurring genres and categories.

### 4. Release Year Trends
Analyzed how the distribution of content release years has changed over time.

### 5. Content Rating Distribution
Examined the distribution of ratings such as TV-MA, TV-14, PG-13, and others.

### 6. Content Addition Trends
Converted the `date_added` column into a datetime format and explored how Netflix's content additions varied by year.

### 7. Director Analysis
Identified the directors associated with the highest number of titles.

## 🔍 Key Insights

The analysis revealed several interesting patterns:

- **Movies dominate:** Netflix has significantly more Movies than TV Shows in this dataset.
- **United States leads:** The United States contributes the largest number of titles.
- **Popular categories:** Drama, International Movies, and Comedies are among the frequently occurring categories.
- **Content growth:** The dataset shows a substantial increase in titles released after 2015.
- **Content ratings:** TV-MA and TV-14 are among the most common content ratings.
- **Director distribution:** A relatively small number of directors have multiple titles, while many directors appear only once.

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Inspected dataset structure and data types.
- Identified missing values.
- Replaced missing values in `director`, `cast`, and `country` with `"Unknown"`.
- Converted `date_added` into datetime format using Pandas.
- Prepared the dataset for exploratory analysis and visualization.

## 🚀 How to Run the Project

### Prerequisites

Make sure Python and Jupyter Notebook are installed.

### 1. Clone the repository

```bash
git clone https://github.com/dhanushss05/Netflix-Data-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Netflix-Data-Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open `netflix_analysis.ipynb` and run the cells to explore the analysis and visualizations.

Make sure `netflix_titles.csv` is in the same directory as the notebook.

## 📁 Dataset

The project uses the Netflix Movies and TV Shows dataset, available through Kaggle.

The dataset contains information about:

- Show ID and title
- Content type
- Director and cast
- Country
- Date added to Netflix
- Release year
- Content rating
- Duration
- Genre categories
- Description

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Data loading and exploration using Pandas.
- Identifying and handling missing values.
- Working with datetime data.
- Performing exploratory data analysis.
- Analyzing categorical and numerical data.
- Creating visualizations to communicate insights.
- Documenting and managing a Python project using Git and GitHub.

## 👨‍💻 Author

**Dhanush S Sulthanpet**

GitHub: [@dhanushss05](https://github.com/dhanushss05)

---

*This project was developed as part of my journey into Data Science and Machine Learning.*