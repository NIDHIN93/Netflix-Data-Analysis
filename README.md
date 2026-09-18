# Netflix Data Analysis

## Project Overview

This project performs exploratory data analysis (EDA) on a Netflix titles dataset using Python.

The analysis explores the content available on Netflix, including movies and TV shows, ratings, countries, release information, genres, cast, and other title-level attributes.

The project focuses on understanding patterns and characteristics within the Netflix content catalog through data cleaning, analysis, and visualization.

---

## Objectives

* Explore and understand the Netflix titles dataset
* Perform basic data cleaning and preprocessing
* Analyze the distribution of Movies and TV Shows
* Explore Netflix content by rating
* Analyze content by country
* Compare Netflix content related to the USA and India
* Explore categories, cast members, and titles
* Use visualizations to identify patterns in the dataset
* Practice exploratory data analysis using Python

---

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **WordCloud**
* **Jupyter Notebook**

---

## Dataset

The project uses the **Netflix Titles** dataset stored as:

```text
data/netflix_titles.csv
```

The dataset contains information about Netflix movies and TV shows, including attributes such as:

* Title
* Type
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Listed In
* Description

---

## Analysis Performed

### 1. Data Exploration

The dataset is loaded and explored to understand:

* Dataset structure
* Columns and data types
* Basic statistics
* Missing values
* Available Netflix content information

### 2. Movies vs TV Shows

The project analyzes the distribution of:

* Movies
* TV Shows

This provides an overview of the types of content available in the dataset.

### 3. Ratings Analysis

Netflix titles are analyzed based on their content ratings to understand the distribution of different rating categories.

### 4. Country Analysis

The project explores the countries associated with Netflix titles and examines the distribution of content across different countries.

### 5. USA and India Analysis

The analysis includes a comparison/exploration of Netflix content associated with the **United States** and **India**.

### 6. Word Cloud Analysis

Word clouds are used to visually explore frequently occurring information related to:

* Countries
* Cast members
* Categories
* Netflix titles

---

## Project Structure

```text
Netflix-Data-Analysis/
│
├── data/
│   └── netflix_titles.csv
│
├── Netflix_Data_Analysis.ipynb
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

### File Description

**`data/netflix_titles.csv`**
The dataset used for the analysis.

**`Netflix_Data_Analysis.ipynb`**
The Jupyter Notebook containing the complete Python-based analysis, data exploration, and visualizations.

**`README.md`**
Documentation describing the project.

**`requirements.txt`**
Python libraries required to run the notebook.

**`.gitignore`**
Specifies files that should not be uploaded to GitHub.

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd Netflix-Data-Analysis
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Netflix_Data_Analysis.ipynb
```

Run the notebook cells from top to bottom.

---

## Key Skills Demonstrated

* Data loading
* Data inspection
* Data cleaning
* Missing-value handling
* Data filtering
* Grouping and aggregation
* Exploratory Data Analysis
* Categorical analysis
* Data visualization
* Word cloud visualization
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Limitations

* The analysis is based on the available Netflix titles dataset.
* The dataset represents a specific snapshot of Netflix content and may not represent the current Netflix catalog.
* Country, cast, rating, and category information may contain multiple values within individual records.
* The analysis is descriptive and does not attempt to predict future Netflix content trends.

---

## Project Type

**Exploratory Data Analysis (EDA)**

---

## Disclaimer

This project is created for educational and portfolio purposes. The analysis reflects the information available in the dataset and should not be interpreted as current Netflix catalog information.
