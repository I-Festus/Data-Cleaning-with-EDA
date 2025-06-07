# Data cleaning using EDA
### Leveraging Python to Clean and Prepare Marketing Data While Creating SEO-Optimized Short Titles for Enhanced Product Insights

![image](https://github.com/user-attachments/assets/01094ee3-a078-40cb-84af-3037cd1ba071)


*Disclaimer⚠️: This project uses dummy data and does not include any real, proprietary, or sensitive information. It is designed to demonstrate my ability to clean and prepare marketing data using Python, including the creation of SEO-optimized short titles.*


## Task Overview
This task focuses on ensuring the dataset is clean, reliable, and ready for further marketing analysis while introducing a new short_title feature for SEO-optimized and concise product titles. I explore, identify, and resolve common data issues using tools like Python (Pandas, NumPy, re). 

## Objective
Prepare raw marketing data for analysis by addressing data quality issues and creating a new feature, short_title, for improved SEO and readability. The task involves resolving data quality issues like missing values and duplicates, standardizing data formats, and generating concise product titles for better marketing impact

##  Dataset Familiarization

![image](https://github.com/user-attachments/assets/78f6ac08-92fc-41ce-b34f-206ada584ab1)

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

![image](https://github.com/user-attachments/assets/989213ee-1c94-4aac-8910-ddbb5de9b038)


**Removing Duplicates**

![image](https://github.com/user-attachments/assets/92918742-49a3-4d5c-bdab-06615998e406)

**Standardizing Data**

![image](https://github.com/user-attachments/assets/7d0f477b-428b-4db3-b263-e2db4e714f6c)

- Rename columns for clarity

![image](https://github.com/user-attachments/assets/747b8c35-790c-47b1-9fd9-d4a842688f53)

**Data Preparation:**
- Convert the columns title, description, and bullet_point to the categorical data type for efficiency.
**Rounding Values:**
- The product_length column values are rounded to two decimal places to improve readability and consistency.

**Creating the short_title Feature**

![Screenshot 2025-02-05 113350](https://github.com/user-attachments/assets/af201fd9-e9b3-41a5-b169-315eb7adb8ce)

**Objective:** Generate concise product titles for SEO and readability.

**Steps:**

Analyze the original Product Title column to identify key components (e.g., product name, category, attributes).

Remove redundant phrases (e.g., "includes," "set of," "features").

Limit titles to 50 characters, focusing on essential details and keywords.

![image](https://github.com/user-attachments/assets/7beb9c8f-9348-4dd4-a808-e62463371a29)

**Drop title column**

![image](https://github.com/user-attachments/assets/16a0b5af-247d-4b02-a10a-1a4599388299)

## Clean Data

![image](https://github.com/user-attachments/assets/13c0f917-d047-492b-859b-f85dfdbce6d3)

# Thank you

For more information, you can contact me

![1744659](https://github.com/user-attachments/assets/17caa157-ecfd-4f5a-82c2-11ad5ee04f8d)
