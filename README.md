# Task 1: Data Cleaning and Preprocessing
1 Objective
To clean and preprocess a raw dataset using Excel by identifying and fixing issues such as:
- Missing values
- Duplicates
- Inconsistent text formatting
- Mixed date formats
- Irregular column names and data types

2. Files Included
- `sales_data_large_raw.csv` → Raw dataset (200 rows) with errors
- `sales_data_cleaned.csv` → Final cleaned dataset (after Excel preprocessing)
- `screenshots/` → (Optional) Screenshots showing Excel steps
- `README.md` → Documentation of what I did
  
3 Data Cleaning Steps Performed in Excel
 **Handled Missing Values**
   - Used filters to identify blank cells
   - Filled gender/country nulls with "Unknown" and numeric nulls with average
 **Removed Duplicates**
   - Removed duplicate rows using **Remove Duplicates** under the Data tab
**Standardized Text**
   - Converted all gender values to "Male" or "Female"
   - Fixed inconsistent country names (e.g., "U.S.A" → "USA")
 **Unified Date Formats**
   - Reformatted all dates to `dd-mm-yyyy` using **Text to Columns** and custom formatting
 **Renamed Column Headers**
   - Changed column names to lowercase, removed spaces, e.g., `Customer Name` → `customer_name`
**Corrected Data Types**
   - Ensured amount and age were integers, and dates were recognized as dates

4  Tools Used
- Microsoft Excel
- GitHub

5 Result
The final cleaned dataset is ready for analysis or visualization with consistent formatting, correct data types, and no missing/duplicate issues.
