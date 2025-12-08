# Excel Data Cleaning Project

# 🧾 Dataset Description

This dataset represents a sample business dataset designed for practicing data-cleaning and spreadsheet preparation in Excel.
It includes fields commonly found in business and sales reporting such as:

-Customer and department information

-Transaction date and region

-Payment method

-Revenue and profit values

-Profit margin calculations



# 📌 Objective

This project demonstrates how raw real-world data can be cleaned and transformed into structured, usable, and analysis-ready format using Microsoft Excel only.

The goal was to detect errors, fix inconsistent entries, deal with missing data, remove duplicates, and improve overall data integrity.


# 🧪 Problems Found in the Raw Data

-Inconsistent text format (uppercase/lowercase mix)

-Extra spaces in cells

-Blank / missing values

-Duplicate entries

-Combined text fields needing separation

-Formula errors (like #N/A or #VALUE!)

-Unclear formatting, making data hard to read


# 🛠 Data Cleaning Steps Performed

## 1. Autofit columns and rows to read data clearly.

📍 Purpose: To make data readable and properly aligned without changing values.

![new (1)](https://github.com/user-attachments/assets/b1b5b189-c983-4072-92e7-195984ceb3ec)


## 2. Used Find & Replace to remove unwanted characters and clean repeated pattern.

📍 Purpose: Remove unwanted characters or fix formatting issues.

![1](https://github.com/user-attachments/assets/5f2d64c9-8488-49bb-90f2-751e63e730cf)


## 3. Standardized text using LOWER functions.

📍 Purpose: Standardize inconsistent text formatting.

![2](https://github.com/user-attachments/assets/522a40c9-f5b5-4a5a-8274-bb0e48a89f54)


## 4. Removed unnecessary spaces using the TRIM function.

📍 Purpose: Remove extra spaces and standardize text formatting for better readability and consistency.

![3](https://github.com/user-attachments/assets/93547432-47f6-4115-9a38-802fac654e0e)


## 5. Split combined values (like “Full Name” or “City, State”) using Text to Columns.

📍 Purpose: Split combined values into separate fields using delimiters like comma, space, or tab.

![4](https://github.com/user-attachments/assets/2c282e57-5286-4e4c-a4a4-e8f89a1a806a)


## 6. Identified and removed duplicate records using Remove Duplicates.

📍 Purpose: Keep only unique entries to avoid repeated or invalid data points.

![5](https://github.com/user-attachments/assets/1fa319c6-6027-40ca-a213-9d196e52aed8)


## 7. Handled blank cells using appropriate filling techniques.

📍 Purpose: Handle missing data to avoid gaps or errors in analysis.
📌 Example Options:
Fill with zero/NA

![6](https://github.com/user-attachments/assets/fbb52f99-05bb-4a14-8176-f6a2d7d4e577)


## 8. Fixed formula errors using IFERROR to avoid broken results.

📍 Purpose: Hide or replace formula errors (like #DIV/0! or #N/A) with readable values.

![7](https://github.com/user-attachments/assets/cc50b6b0-d1bd-4223-ba1f-b1e02f43111e)


## 9. Applied consistent formatting to make the dataset clean and readable.

📍 Purpose: Improve readability and maintain consistent formatting such as:

![8](https://github.com/user-attachments/assets/78aa6c1c-e72f-48fb-8e19-d6459e9b5c5f)


## 10. Modified view options (gridlines, alignment, and formatting) to finalize the cleaned version.

📍 Purpose: Clean up dataset visuals for presentation or export.

![9](https://github.com/user-attachments/assets/e4d35f7e-65c2-40a5-98ca-55c5f9f8423d)

