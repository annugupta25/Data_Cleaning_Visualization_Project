# 🎬 Netflix Data Cleaning and Exploratory Data Analysis

A complete data cleaning and exploratory data analysis (EDA) project on the **Netflix Movies and TV Shows** dataset, built as part of a Data Science Internship at **Thiranex**.

---

## 📌 Overview

This project was completed as part of my Data Science Internship at **Thiranex**. The objective was to clean a raw dataset, perform exploratory data analysis (EDA), create meaningful visualizations, and generate insights using Python.

---

## 🎯 Project Objective

The main goals of this project are:

- Load and inspect the dataset
- Handle missing values
- Remove duplicate records
- Detect and analyze outliers
- Perform Exploratory Data Analysis (EDA)
- Create visualizations using Matplotlib and Seaborn
- Generate meaningful business insights
- Save the cleaned dataset for future analysis

---

## 📊 Dataset

**Dataset Name:** Netflix Movies and TV Shows

The dataset contains information about Netflix titles, including:

| Column | Description |
|---|---|
| `show_id` | Unique identifier for each title |
| `type` | Movie or TV Show |
| `title` | Name of the content |
| `director` | Director name |
| `cast` | Cast members |
| `country` | Country of production |
| `date_added` | Date added to Netflix |
| `release_year` | Year of release |
| `rating` | Content rating |
| `duration` | Movie duration or TV show seasons |
| `listed_in` | Genre / category |
| `description` | Brief description |

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---

## 📁 Project Structure

```
Netflix_Data_Cleaning_Project/
│
├── dataset.csv
├── cleaned_netflix_dataset.csv
├── netflix_analysis.ipynb
├── README.md
└── images/
```

---

## 🧹 Data Cleaning Process

### Missing Values

Missing values were found in the following columns:

- Director
- Cast
- Country
- Date Added
- Rating

These values were handled using appropriate methods, such as replacing them with `"Unknown"`, `"Not Available"`, or the most frequent value (mode).

### Duplicate Records

Duplicate records were identified using Pandas and removed from the dataset.

### Outlier Detection

Outliers were analyzed using the **Interquartile Range (IQR)** method on the numerical column `release_year`.

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Movies vs TV Shows
- Distribution of Content Ratings
- Top Countries Producing Content
- Release Year Distribution
- Top Genres
- Top Directors
- Pie Chart of Content Types
- Boxplot for Outlier Detection

---

## 📈 Visualizations

The project includes the following visualizations:

- Count Plot
- Histogram
- Bar Chart
- Pie Chart
- Box Plot

These visualizations help in understanding trends and patterns within the Netflix dataset.

---

## 💡 Key Insights

- The dataset contains both Movies and TV Shows.
- Missing values were successfully handled.
- Duplicate records were removed.
- Most Netflix content consists of Movies.
- The United States contributes the highest number of titles.
- Drama and International Movies are among the most popular genres.
- The majority of content was released after the year 2000.
- TV-MA is one of the most common content ratings.

---

## 📤 Output

The cleaned dataset is saved as:

```
cleaned_netflix_dataset.csv
```

---

## ✅ Conclusion

This project demonstrates the complete workflow of data cleaning and exploratory data analysis using Python. It highlights the importance of preparing raw data before analysis and extracting useful insights through visualization techniques.

---

## 👤 Author

**Dhruv Bhadoriya**
Data Science Intern – Thiranex
