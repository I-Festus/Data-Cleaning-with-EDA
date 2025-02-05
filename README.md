# Data cleaning using EDA
## Task Overview
This task focuses on ensuring the dataset is clean, reliable, and ready for further marketing analysis while introducing a new short_title feature for SEO-optimized and concise product titles. I explore, identify, and resolve common data issues using tools like Python (Pandas, NumPy, re). 

## Objective
Prepare raw marketing data for analysis by addressing data quality issues and creating a new feature, short_title, for improved SEO and readability. The task involves resolving data quality issues like missing values and duplicates, standardizing data formats, and generating concise product titles for better marketing impact

##  Dataset Familiarization
- **PRODUCTID:** Unique identifier for each product.
- **TITLE:** Brief title or name of the product.
- **BULLET_POINTS:** Key features or highlights of the product, often listed in bullet format.
- **DESCRIPTION:** Detailed description of the product, including specifications and features.
- **PRODUCTTYPEID:** Identifier representing the category or type of the product.
- **ProductLength:** Length of the product, likely in millimeters based on the values.

## Data Exploration

**TOOLS**

Python (jupyter notebook)
- Numpy
- Pandas
- re

**Dataset Insights**
![image](https://github.com/user-attachments/assets/abb75986-da8e-45a2-89c5-f0ffa1da7bfd)

- **Total Entries:** 3,847 rows.
- **Columns:** 6 in total

**Descriptive Statistics**

![image](https://github.com/user-attachments/assets/3f86bc2d-3a1f-440e-b395-a586a8e34235)

**Key Insights**
- **PRODUCTID:** No missing values, ranges from 1.3M to 3M, evenly distributed.
- **PRODUCTTYPEID:** 178 missing, ranges from 0 to 13,330, high variation.
- **ProductLength:** 178 missing, ranges from 1 to 96,000, extreme outliers present.

## Data Cleaning Process

**Handling Missing Values**

![image](https://github.com/user-attachments/assets/6048e27a-98fb-4678-a604-1f249c9f0f6d)

**Missing Values Overview**

- **BULLET_POINTS:** 1,591 missing
- **DESCRIPTION:** 2,144 missing
- **PRODUCTTYPEID & ProductLength:** 178 missing each
- **PRODUCTID & TITLE:** No missing values

**Missing Value Handling:**

- **Numerical Columns (PRODUCTTYPEID, ProductLength):** Filled with the median to reduce outlier impact.
- **Text Columns (BULLET_POINTS, DESCRIPTION):** Filled with the mode (most common value) for consistency.





































