# EDA on Naukri.com Job Listings 🧑‍💻📊

This repository contains a detailed Exploratory Data Analysis (EDA) project on job listings scraped from the Naukri.com portal. The analysis aims to provide insights into job trends, required skills, locations, company preferences, salary distributions, and more, specifically focused on the Data Science domain.

## 📁 Files Included

### 1. `01_naukri_scraping.ipynb`
- Performs web scraping on Naukri.com using Selenium and BeautifulSoup.
- Extracts job information such as:
  - Job Title
  - Company Name
  - Ratings
  - Reviews
  - Location
  - Experience Required
  - Salary (if available)
  - Skills
  - Education Qualification
- Saves the cleaned dataset into a CSV format for analysis.

### 2. `02_data_cleaning_preparation.ipynb`
- Loads the scraped data and performs preprocessing:
  - Handles null values and duplicates.
  - Standardizes salary, experience, and location columns.
  - Converts columns to appropriate data types.
  - Creates new features like salary range, job level classification, etc.

### 3. `03_eda_visualization.ipynb`
- Conducts in-depth analysis using Python libraries like Pandas, Matplotlib, and Seaborn.
- Key visualizations include:
  - Most demanded skills for Data Science roles.
  - Top hiring locations in India.
  - Salary vs Experience comparison.
  - Company-wise job distribution.
  - Job level frequency (e.g., Entry, Mid, Senior).

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Numpy
- Selenium
- BeautifulSoup
- Matplotlib
- Seaborn
- Regex (re)

## 📌 Key Insights

- Python, SQL, and Machine Learning are the most in-demand skills.
- Bangalore, Hyderabad, and Pune are top hiring cities.
- Entry-level jobs often demand 0–2 years of experience with moderate salaries.
- Certain companies post more frequently, indicating high recruitment demand.

## 🙋‍♂️ About Me

**Yadagiri Kuruva**  
Recent B.Tech graduate in CSE (AI & DS) | Data Analysis & Science Enthusiast  
🔗 [GitHub](https://github.com/k-yadagiri)  
🔗 [linkedln](https://www.linkedin.com/in/k-yadagiri)
