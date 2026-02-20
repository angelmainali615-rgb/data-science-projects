# Adult Census Income Data Cleaning Project

## Project Overview
This project focuses on **cleaning and preparing the Adult Census Income dataset** for analysis and potential machine learning tasks.  
The dataset contains demographic and income-related information about individuals.  
The goal is to handle messy or missing data properly and make the dataset ready for analysis.

---

## Dataset
- Contains attributes like age, workclass, education, marital status, occupation, race, sex, hours per week, and income.
- The dataset may include:
  - Missing values
  - Inconsistent or messy entries
  - Categorical values that need encoding

---

## Steps Performed

1. **Load Dataset**
   - Imported using pandas
   - Inspected the first few rows

2. **Handle Missing Values**
   - Identified missing or unknown values
   - Decided whether to drop, impute, or clean based on context

3. **Data Cleaning**
   - Removed duplicates
   - Fixed inconsistent categorical values
   - Converted categorical variables to numerical form (Label Encoding / One-Hot Encoding)
   - Corrected numerical inconsistencies (e.g., negative hours, impossible ages)

4. **Data Validation**
   - Checked distributions and outliers
   - Ensured logical consistency (e.g., income categories match attributes)

5. **Save Cleaned Dataset**
   - Saved as `adult_census_income_cleaned.csv` for further analysis or ML tasks

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn (for encoding)
- Jupyter Notebook

---

## Learning Outcomes
- Understand real-world messy data
- Apply context-aware cleaning techniques
- Prepare categorical and numerical data for analysis
- Build strong foundational skills in data preprocessing

---



