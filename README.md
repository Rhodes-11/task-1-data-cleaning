# Task 1: Data Cleaning and Preprocessing

## Dataset
**Chocolate Sales** — raw sales records with salespeople, product, country, amount, and boxes shipped.

## Objective
To clean and prepare the dataset for analysis by addressing issues like formatting, data types, and consistency.

## Tools Used
- Python
- Pandas

## Steps Taken

1. **Renamed Columns:**
   - Converted to lowercase and replaced spaces with underscores.
   - E.g., `Sales Person` → `sales_person`

2. **Converted `amount`:**
   - Removed dollar signs and commas (`$5,320` → `5320.0`)
   - Converted to float.

3. **Standardized `date`:**
   - Parsed `dd-mmm-yy` format to standard datetime (`2022-01-04`).

4. **Checked for Missing & Duplicate Values:**
   - No missing values or duplicates found.

## Output
- `Cleaned_Chocolate_Sales.csv`: Final processed dataset ready for analysis or modeling.

