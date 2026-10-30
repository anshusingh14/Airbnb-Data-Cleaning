# Airbnb Data Cleaning Project

## Project Overview

This project focuses on cleaning and preprocessing an Airbnb listings dataset using **Python and Pandas**.

The main objective is to improve data quality by identifying and handling missing values, removing duplicate records, standardising categorical values, and converting columns into appropriate data types.

This project demonstrates practical data cleaning skills that are essential for real world Data Analysis.

## Objectives

- Explore the dataset and understand its structure.
- Identify unnecessary columns.
- Detect and remove duplicate records.
- Identify and handle missing values.
- Standardise categorical data.
- Clean and convert price values into numeric format.
- Export the cleaned dataset into a CSV file.

## Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and cleaning
- **Jupyter Notebook** – Interactive development environment

## Project Structure

```text
Airbnb-Data-Cleaning/
│
├── Dataset/
│   ├── Airbnb_Open_Data.csv
│   ├── Cleaned_Airbnb_data.csv
│   └── Airbnb.ipynb
│
└── README.md
```

## Data Cleaning Process

The following operations were performed:

### 1. Data Loading and Exploration
- Loaded the dataset using Pandas.
- Examined column names and dataset structure.
- Checked data types and non-null values.

### 2. Column Selection and Removal
- Identified relevant columns for the cleaning process.
- Removed unnecessary columns that were not required for the intended analysis.

### 3. Renaming Columns
- Renamed Coulmns for better readability.

### 4. Duplicate Removal
- Identified duplicate records.
- Removed duplicate rows using `drop_duplicates()`.

### 5. Missing Value Handling
- Identified missing values using `isna()`.
- Examined missing value counts across columns.
- Removed rows containing missing values using `dropna()`.

### 6. Categorical Data Cleaning
- Converted `Host_identity_verified` values to uppercase for consistency.
- Converted `Instant_bookable` Boolean values into numerical representation:
  - True → 1
  - False → 0

### 7. Price Column Transformation
- Removed dollar signs (`$`).
- Removed commas and unnecessary spaces.
- Converted the price column from string to integer format.

### 8. Exporting Cleaned Data
- Exported the cleaned dataset into a CSV file.
- Used `index=False` to avoid exporting the DataFrame index.

## Output

The final cleaned dataset is saved as:

`Cleaned_Airbnb_data.csv`

## Key Learnings

Through this project, I gained practical experience in:

- Data inspection and exploration.
- Handling missing values.
- Removing duplicate records.
- Data type conversion.
- String manipulation using Pandas.
- Data preprocessing and transformation.
- Exporting cleaned datasets.

## Future Improvements

- Perform Exploratory Data Analysis (EDA).
- Analyse Airbnb pricing trends across neighbourhoods.
- Explore room type distributions.
- Investigate relationships between reviews and prices.
- Create meaningful data visualisations.

## Author

**Anshu Singh**
IIT Madras BS (Data Science)

---

⭐ If you find this project useful, feel free to explore the repository!
