# Data-Cleaning-EDA-SQL


## Layoffs Data Analysis & Cleaning
This project focuses on data cleaning and exploratory data analysis (EDA) of global tech layoffs, using a dataset that tracks company-wide layoffs, affected employees, funding stages, and more. The goal is to understand trends, patterns, and possible insights from the layoffs data.

### 📁 Dataset
Source: Layoffs.fyi

Table Used: layoffs_staging_v2

Columns: Company, Location, Industry, Total Laid Off, Percentage Laid Off, Date, Stage, Country, etc.

### 🧹 Data Cleaning Steps
Standardized company names and date formats

Handled null and inconsistent values in key columns

Removed duplicate rows

Filtered out invalid entries (e.g., "NULL" as a string in date fields)

Created a cleaned version of the dataset ready for analysis

### 📊 Exploratory Data Analysis
Performed EDA to uncover trends such as:

Layoffs over time (monthly/quarterly)

Top countries and companies by number of layoffs

Industries and funding stages most affected

Percentage-based layoff impact comparisons

### 📌 Key Insights
Layoffs peaked around major economic downturns

Tech companies in late-stage funding rounds were among the hardest hit

Certain months and quarters saw spikes in layoffs globally

