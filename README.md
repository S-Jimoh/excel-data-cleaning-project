# Excel-Data-Cleaning-Project
Excel based data cleaning projects using power query and formulas

 
## Project Overview
This project focuses on cleaning a structured dataset using **Microsoft Excel**. The dataset originally contained records with inconsistencies, missing values, and formatting issues. The goal was to clean and prepare the data for further analysis by applying Excel’s data cleaning tools and formulas.

---

## Tools & Skills Used
- Microsoft Excel
- Power Query
- Data Cleaning
- Data Validation
- Logical Formulas (IF, OR, ISNUMBER, SEARCH)
- Text Functions (TRIM, PROPER, CONCATENATE)

---

## Cleaning Steps

### 1. Initial Assessment
- Removed unnecessary images and section titles
- Cleaned 7 empty rows before headers

### 2. Duplicate & Missing Values
- Removed 6 duplicate rows
- Replaced missing numerical data (e.g., Service KM) with zero

### 3. Column-Specific Cleaning

| Column                     | Cleaning Actions                                                                 |
|---------------------------|-----------------------------------------------------------------------------------|
| **Date**                  | Fixed formatting from numeric to date format (e.g., "42064" → "01-03-15")        |
| **Vehicle Reg. Number**   | Removed brackets using Find & Replace                                            |
| **Make/Model**            | Split into multiple columns and recombined using CONCATENATE                     |
| **Item Description**      | Categorized into 5 groups using Excel functions                                  |
| **Assigned To**           | Standardized inconsistent name formats                                           |
| **Service KM**            | Converted to numeric, replaced blanks with 0, formatted with commas              |
| **Workshop Name**         | Corrected casing, removed extra spaces, fixed typos                              |
| **Invoice Number**        | Standardized entries and missing values replaced with “NA”                       |
| **Amount (NGN)**          | Formatted with Naira currency symbol                                             |
| **Remarks**               | Dropped due to being completely empty                                            |

### 4. Final Review
- Loaded the cleaned data into **Power Query** for verification
- Corrected remaining minor errors
- Final dataset exported back into Excel

---

## Results
- All columns cleaned, standardized, and formatted
- Dataset now ready for analysis and reporting

---


## Access the Dataset
You can view the cleaned spreadsheet here:  
[**Google Sheets – Final Dataset**](https://docs.google.com/spreadsheets/d/1TGoD1g7KLcqjrqMIFXpBs7-ibfA3cl9W/edit?usp=sharing&ouid=106812219724605440864&rtpof=true&sd=true)

---

## Contact
For questions or collaboration, reach out at:  
**[sekinateniola.jimoh@gmail.com](mailto:sekinateniola.jimoh@gmail.com)**
