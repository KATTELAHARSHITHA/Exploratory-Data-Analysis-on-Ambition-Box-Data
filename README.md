# 📊 Exploratory Data Analysis (EDA) Project — Company Insights from AmbitionBox

## 🧠 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on data extracted from the **AmbitionBox** website, which provides information about various companies, their ratings, reviews, and details.
The goal of this project is to explore, clean, and visualize the data to uncover meaningful insights and prepare it for further analysis or model building.

---

## 📂 Dataset Description

The dataset used in this project was obtained via **web scraping** from [AmbitionBox](https://www.ambitionbox.com/).
It includes information such as:

* Company names
* Ratings and reviews
* Sectors or industries
* Employee satisfaction metrics
* Other attributes extracted during scraping

The dataset underwent multiple cleaning and transformation steps before being analyzed.

---

## ⚙️ Technologies Used

* **Python 3.x**
* **Pandas** — for data manipulation
* **NumPy** — for numerical computation
* **Matplotlib** and **Seaborn** — for data visualization
* **Requests** and **BeautifulSoup** — for web scraping
* **Jupyter Notebook** — for interactive analysis

---

## 🧩 Steps Performed

### 1. **Data Collection**

Data was scraped from AmbitionBox using the `requests` library and parsed using `BeautifulSoup`.
Headers and User-Agent strings were configured to ensure successful HTTP requests.

### 2. **Data Cleaning**

* Converted columns to appropriate datatypes.
* Checked for missing values and handled them appropriately.
* Removed duplicates if any.
* Detected and handled **outliers** using statistical methods.

### 3. **Descriptive Statistics**

* Summarized numerical features using mean, median, mode, and standard deviation.
* Identified trends and anomalies before and after outlier handling.

### 4. **Exploratory Data Analysis**

* Visualized distributions and relationships using histograms, boxplots, and pairplots.
* Compared ratings across companies and sectors.
* Investigated potential correlations between company attributes.

### 5. **Insights & Findings**

Some example insights (adjust as per your findings):

* Certain industries tend to have higher average ratings.
* Outlier handling significantly improved data consistency.
* Missing values in some features could be attributed to limited company information on the website.

---

## 📈 Key Visualizations

* Company rating distribution
* Industry-wise comparison plots
* Outlier visualization using boxplots
* Correlation heatmap between numerical attributes

*(Include images if you have them in your repo — e.g., `![Boxplot](images/boxplot.png)`)*

---

## 🧮 Results & Conclusions

* The cleaned dataset is now ready for further **predictive modeling** or **sentiment analysis**.
* The EDA provided clear insight into which industries perform better and how data inconsistencies affect overall statistics.

---

## 🚀 Future Scope

* Automate web scraping to collect periodic data updates.
* Extend analysis to include sentiment from company reviews.
* Develop machine learning models to predict company ratings or employee satisfaction.
