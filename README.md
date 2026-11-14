# 📱 Google Play Store Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the Google Play Store dataset to understand the distribution of mobile applications across different categories.

The analysis explores app categories, ratings, reviews, installs, pricing, and other important attributes to identify trends and patterns in the Google Play Store ecosystem.

The main objective is to extract meaningful insights from app-related data through data cleaning, statistical analysis, and data visualization.

## 🎯 Project Objectives

- Analyze the distribution of applications across different categories.
- Identify the most popular app categories.
- Understand app ratings and user reviews.
- Explore free vs. paid applications.
- Analyze app installations and popularity.
- Identify patterns and trends in application data.
- Visualize important insights using charts and graphs.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Interactive analysis

## 📊 Exploratory Data Analysis

The project includes the following analysis:

1. **Data Understanding**
   - Dataset structure and dimensions
   - Column information and data types
   - Statistical summary

2. **Data Cleaning**
   - Handling missing values
   - Removing duplicate records
   - Handling inconsistent data
   - Converting columns into appropriate data types

3. **Category Analysis**
   - Distribution of applications across categories
   - Identifying categories with the highest number of applications
   - Comparing app category distributions

4. **Rating Analysis**
   - Distribution of application ratings
   - Identifying highly rated applications
   - Understanding rating patterns

5. **Install Analysis**
   - Analyzing application installations
   - Identifying popular applications
   - Comparing installs across categories

6. **Price Analysis**
   - Comparing free and paid applications
   - Understanding pricing patterns
   - Exploring paid app distribution

## 📈 Key Insights

Based on the category distribution visualization:

- **Family** is the largest category, accounting for approximately 19% of applications.
- **Game** represents around 9.9% of applications.
- **Tools** contributes approximately 8.6%.
- Business accounts for around 4.3%.
- Medical represents approximately 4.1%.
- Several other categories contribute smaller proportions to the overall application distribution.

The visualization highlights that application distribution is not uniform across categories, with Family, Game, and Tools representing significant portions of the dataset.

## 📊 Visualization

The project uses different visualizations to understand the dataset:

- Pie Charts – Category distribution
- Bar Charts – Category-wise app counts
- Histograms – Ratings and price distributions
- Box Plots – Distribution and outlier detection
- Count Plots – Free vs. paid applications

## 📂 Project Structure

```text
Google-Play-Store-EDA/
│
├── Google_Play_Store_EDA.ipynb
├── googleplaystore.csv
├── images/
│   └── category_distribution.png
│
└── README.md
```

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:

```bash
cd Google-Play-Store-EDA
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Google_Play_Store_EDA.ipynb` and execute the cells.
