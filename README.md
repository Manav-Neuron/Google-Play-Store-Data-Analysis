# Google-Play-Store-Data-Analysis
Exploratory Data Analysis of Google Play Store apps using Python, Pandas, Matplotlib &amp; Seaborn to identify trends, patterns, and factors influencing app performance.


## Project Overview
This project focuses on analyzing the Google Play Store dataset to uncover insights about app popularity, installs, ratings, and category-wise performance.  
The goal is to apply real-world data cleaning, exploratory data analysis (EDA), and visualization techniques using Python.

---

## Objectives
- Clean and preprocess raw Play Store data
- Handle missing, duplicate, and inconsistent values
- Analyze app installs and ratings
- Identify top-performing apps and categories
- Visualize insights for better interpretation

---

## Dataset
- Source: Google Play Store dataset (via GitHub)
- Format: CSV
- Key Columns:
  - App
  - Category
  - Rating
  - Installs
  - Size

---

## Tools & Technologies Used
- Python
- NumPy – numerical operations
- Pandas – data cleaning and manipulation
- Matplotlib – basic data visualization
- Seaborn – advanced statistical visualizations
- Jupyter Notebook

---

## Data Cleaning & Preprocessing
The following steps were performed:
- Removed duplicate app entries
- Handled missing ratings by imputing with mean values
- Cleaned install counts by removing symbols (+, ,)
- Converted installs into numeric format
- Handled inconsistent size values (MB, KB, and non-numeric entries)

---

## Exploratory Data Analysis (EDA)
Key analyses include:
- Identifying top 10 most installed apps
- Category-wise distribution of installs
- Formatting large numbers for better readability (K, M, B)
- Counting 5-star rated apps by category
- Understanding quality concentration across categories

---

## What I Learned From This Project
Through this project, I gained practical experience in handling real-world datasets and learned:

- How to convert large numerical values and scientific notation into human-readable formats (K, M, B) for better data presentation
- How to clean and standardize symbolic values such as '+', ',', and text-based numeric fields
- Techniques to handle missing (NaN) values using appropriate statistical methods
- The importance of separating raw numeric data from formatted presentation data
- How proper data cleaning directly improves the accuracy of analysis and visualizations

---

## Visualizations
- Bar charts for:
  - Top app categories by total installs
  - Number of 5-star rated apps across categories
- Rotated axis labels and clear titles for readability

---

## Key Insights
- GAME and COMMUNICATION categories dominate total installs
- Certain categories show a high concentration of 5-star rated apps
- Cleaning and preprocessing significantly improves data reliability
- Human-readable formatting improves data storytelling

---

## Project Structure
