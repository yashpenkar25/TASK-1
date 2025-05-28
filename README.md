Task 1: Data Cleaning and Preprocessing

📁 Dataset Used
Mall Customer Segmentation Data (from Kaggle)

🛠 Tools
Python
Pandas
Google Colab

🔧 Steps Performed
Identified and handled missing values using .isnull().sum() and dropna() in Python
Removed duplicate rows using .drop_duplicates()
Standardized text values like gender using .str.lower() and .str.strip()
Ensured consistent date format (none in this dataset, but applicable if added)
Renamed column headers to clean, lowercase names without spaces (e.g., Annual Income (k$) → annual_income_k)

📤 Output Files

Untititles9.ipynb – Jupyter Notebook with all cleaning steps

mall_customers_cleaned.csv – Final cleaned dataset
