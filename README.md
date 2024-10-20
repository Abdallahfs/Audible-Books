# Audible Books Dataset Analysis 📚

## Objective
Prepare an Audible dataset for future machine learning tasks and gain insights into audiobook trends through exploratory data analysis.

## Project Overview
This project involved cleaning, preparing, and engineering new features from the Audible dataset to ensure high-quality data suitable for analysis and model building.

## Methodology
1. **Data Preparation**:  
   - Cleaned the dataset and handled missing values/duplicate rows.
   - Fixed columns data types
   - Removed unnecessary columns with limited information.

2. **Data Quality Testing**:  
   - Ensured the data’s integrity for future analysis.

3. **Feature Engineering**:  
   - Extracted the **day of the week** each book was released.
   - Added **Release_Year_Group** feature so each 5 years interval is in a group.
   - Added a **Price_Category** feature.
   - Counted the **number of words** in book titles.
   - performed EDA to explore relationships between features using various plots

4. **Dataset Splitting**:  
   - Split data into **train (80%) / test (10%) / eval (10%)** sets for machine learning tasks.

## Tools and Technologies
- Python, Pandas, NumPy, scipy, matplotlib, skimpy, sklearn, seaborn

## Usage
The prepared dataset is available for further analysis or use in predictive models. Feel free to clone this repository to explore the notebooks and perform your own analysis.

---

