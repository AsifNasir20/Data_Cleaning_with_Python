## 🧹 Data Cleaning with Python

### Project Overview
This project focuses on preparing raw datasets for analysis using Python. It covers essential data-cleaning techniques using Pandas, NumPy, and data visualization libraries to improve data quality, consistency, and reliability.

### 🔍 1. Data Inspection & Exploration
- `head()` and `tail()` – Previewing dataset records.
- `shape` and `columns` – Understanding dataset dimensions and column names.
- `info()` – Examining column data types and non-null values.
- `describe()` – Generating descriptive statistical summaries.
- Frequency Distribution – Identifying value counts and category distributions.
- Visual Inspection – Exploring data patterns and identifying potential inconsistencies.

### 🛠️ 2. Handling Missing Values
- Identifying missing values using `isnull()` and `isna()`.
- Counting missing values using `sum()`.
- Removing rows and columns containing missing values using `dropna()`.
- Imputing missing values using `fillna()`.
- Applying appropriate imputation techniques based on data types and distributions.

### 🔄 3. Fixing Inconsistent Formatting
- Standardizing inconsistent categorical values.
- Correcting variations such as `Male`, `male`, and `M` into a consistent format.
- Removing unwanted spaces and correcting text inconsistencies.
- Applying string manipulation techniques for data standardization.

### 🔁 4. Handling Duplicate Records
- Identifying duplicate records using `duplicated()`.
- Counting duplicate entries.
- Removing duplicate records using `drop_duplicates()`.
- Ensuring data uniqueness and consistency.

### 🔢 5. Correcting Data Types
- Identifying incorrect column data types.
- Converting columns into appropriate data types using `astype()` and `to_datetime()`.
- Handling mixed-format values.
- Using Regular Expressions (`re`) to extract and clean numeric values from inconsistent text fields.

### 📊 6. Handling Outliers
- Identifying potential outliers through statistical analysis.
- Detecting extreme values using the Interquartile Range (IQR) method.
- Visualizing outliers using Box Plots.
- Evaluating and treating outliers to improve data consistency.

### 💻 Tools & Libraries
- **Python**
- **Pandas** – Data manipulation and cleaning.
- **NumPy** – Numerical operations.
- **Matplotlib & Seaborn** – Data visualization.
- **Regular Expressions (re)** – Pattern matching and text cleaning.

### 🎯 Project Outcome
Developed practical knowledge of the data-cleaning workflow, from initial data inspection to handling missing values, inconsistencies, duplicates, incorrect data types, and outliers, creating a more reliable dataset for further analysis.
