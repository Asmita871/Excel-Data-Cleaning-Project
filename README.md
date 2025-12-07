# Excel Data Cleaning Project

Dataset Used: (Write dataset name here, e.g., “Online Retail Sales Dataset from Kaggle”)


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

📌 Action: Select sheet → Auto-fit rows and columns.

![new (1)](https://github.com/user-attachments/assets/b1b5b189-c983-4072-92e7-195984ceb3ec)


## 2. Used Find & Replace to remove unwanted characters and clean repeated pattern.

📍 Purpose: Remove unwanted characters or fix formatting issues.

![1](https://github.com/user-attachments/assets/5f2d64c9-8488-49bb-90f2-751e63e730cf)


## 3. Standardized text using LOWER functions.

📍 Purpose: Standardize inconsistent text formatting.

![2](https://github.com/user-attachments/assets/522a40c9-f5b5-4a5a-8274-bb0e48a89f54)


## 4. Removed unnecessary spaces using the TRIM function.

Split combined values (like “Full Name” or “City, State”) using Text to Columns.

Identified and removed duplicate records using Remove Duplicates.

Handled blank cells using appropriate filling techniques.

Fixed formula errors using IFERROR to avoid broken results.

Applied consistent formatting to make the dataset clean and readable.

Modified view options (gridlines, alignment, and formatting) to finalize the cleaned version.
