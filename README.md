## Task-1-Data-Cleaning-and-Preprocessing

This project demonstrates essential data cleaning techniques using Python and pandas. It includes handling missing values, removing duplicates, standardizing text, converting date formats, renaming columns, and correcting data types.

## Tech Stack
- Python 3
- Jupyter Notebook
- pandas

## Tasks Performed

1. **Identify and Handle Missing Values**
   - Used .isnull() to detect missing values.
   - Handled them via dropna() based on context.

2. **Remove Duplicate Rows**
   - Used .drop_duplicates() to remove repeated data entries.

3. **Standardize Text Values**
   - Converted country names and categorical fields to lowercase/uppercase.
   - Used .str.strip(), .str.lower(), etc.

4. **Convert Date Formats**
   - Converted date columns to a consistent format using pd.to_datetime().

5. **Rename Column Headers**
   - Standardized column names: all lowercase, replaced spaces with underscores.

6. **Fix Data Types**
   - Converted age columns to int.
   - Converted date columns to datetime64.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SamGarg-111/Task-1-Data-Cleaning-and-Preprocessing.git
   cd Task-1-Data-Cleaning-and-Preprocessing

2. Write the codes in Jupiter notebook under the file Task-1-Data-Cleaning-and-Preprocessing.
3. Save the file and download it as .ipynb on your system.
4. Go to your Github repo and upload the same and then commit to the changes.
5. Your coded file is now saved in the preffered repo. 
   

