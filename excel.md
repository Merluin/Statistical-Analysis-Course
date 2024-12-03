### **Excel: A Basic Introduction**

#### **What is Excel?**

Microsoft Excel is a powerful spreadsheet software widely used for data organization, exploration, and analysis. It allows users to manage data, perform calculations, create visualizations, and analyze trends effectively. Its accessibility and extensive features make it an excellent tool for exploring datasets, calculating statistics, and preparing data for further analysis.

#### **Basics of Using Excel for Data Analysis**

1. **Recopy Handle (Fill Handle):**
   - The fill handle is a small square at the bottom-right corner of a selected cell. 
   - To copy or autofill content:
     - Click and drag the fill handle across adjacent cells to replicate data or formulas.
     - Excel will auto-adjust references in formulas to match the new cells.
   - **Example: Absolute and Relative References:**
     - If `A1` contains `=B1+C1`, dragging the fill handle adjusts the formula for each row (e.g., `=B2+C2` for the next row).
     - To lock a row or column, use the `$` symbol:
       - `$B$1` locks both row and column.
       - `$B1` locks only the column.
       - `B$1` locks only the row.
     - For example, `=B1*$A$1` will multiply `B1` by the constant in cell `A1` no matter where the formula is copied.

2. **Checking Cell Format:**
   - Proper formatting ensures data is interpreted correctly.
   - To check or change cell format:
     - Select the cells.
     - Go to the **Home** tab → **Number** group → **Dropdown Menu**.
     - Choose the format (e.g., General, Number, Text, Date).
   - **Example:** Ensure numerical data is set to "Number" for calculations.

3. **Using Functions:**
   - Excel functions simplify calculations and data analysis.
   - Functions are written as `=FUNCTION_NAME(arguments)`.
   - **Common Functions:**
     - **Mean (Average):** `=AVERAGE(range)`
     - **Standard Deviation:** `=STDEV.S(range)` (sample) or `=STDEV.P(range)` (population)
     - **Sum:** `=SUM(range)`
     - **Count:** `=COUNT(range)`
   - **Example Table of Basic Functions:**

| **English Function**   | **Italian Function**         | **Description**                               | **Example (Italian)**       |
|-------------------------|------------------------------|-----------------------------------------------|------------------------------|
| `=AVERAGE(range)`       | `=MEDIA(intervallo)`         | Calculates the mean of a range.               | `=MEDIA(A1:A10)`            |
| `=SUM(range)`           | `=SOMMA(intervallo)`         | Adds all values in a range.                   | `=SOMMA(B1:B10)`            |
| `=COUNT(range)`         | `=CONTA.NUMERI(intervallo)`  | Counts numeric entries in a range.            | `=CONTA.NUMERI(C1:C10)`     |
| `=STDEV.S(range)`       | `=DEV.ST(intervallo)`        | Calculates sample standard deviation.         | `=DEV.ST(D1:D10)`           |
| `=STDEV.P(range)`       | `=DEV.ST.P(intervallo)`      | Calculates population standard deviation.     | `=DEV.ST.P(D1:D10)`         |
| `=MEDIAN(range)`        | `=MEDIANA(intervallo)`       | Finds the median value in a range.            | `=MEDIANA(E1:E10)`          |
| `=MODE.SNGL(range)`     | `=MODA.UNO(intervallo)`      | Finds the most frequent value (single mode).  | `=MODA.UNO(F1:F10)`         |

### **Important Notes:**
1. **Localized Function Names:**  
   Excel automatically localizes function names based on the language of the software. If you're using the Italian version, you need to use the Italian names.
   
2. **Formula Behavior:**  
   If you receive or share Excel files between different language versions, Excel will translate the function names automatically for the recipient's language version. 

3. **Function Lookups:**  
   If unsure, use Excel's **Function Wizard** (Insert Function button) to find the localized function name. 

You can find the Italian function [here](https://it.excelfunctions.eu/AVERAGE/Italiano)

---

#### **Importing CSV Files into Excel**

**What is a CSV file?**  
A CSV (Comma-Separated Values) file is a plain-text file where data is separated by commas or semicolons. It is commonly used for transferring data between software systems.

**Steps to Import a CSV File:**
1. Open Excel.
2. Go to the **File** menu → **Open** → Browse for the file.
3. In the file selection dialog, set the file type to `CSV (*.csv)`.
4. Select your CSV file and open it.

**Key Warnings:**
- **Decimal Separator Options:**  
  - European format often uses `;` as the delimiter and `,` for decimals.  
  - English format uses `,` as the delimiter and `.` for decimals.  
- To adjust:
  - Go to **File** → **Options** → **Advanced** → **Editing Options**.
  - Check or uncheck **Use system separators**, then set the decimal and thousands separators as needed.

**Alternative Method:**
- Use the **Text Import Wizard**:
  1. Open a blank Excel sheet.
  2. Go to **Data** → **Get External Data** → **From Text/CSV**.
  3. Select your file and configure delimiter settings for proper column separation.

---

### **Conclusion**

Excel provides a robust environment for data exploration and analysis. Mastering basic features like the fill handle, cell formatting, and functions enhances productivity. With a clear understanding of how to import and manage CSV files, Excel becomes an indispensable tool for working with data across various formats.

Return to [index](index.md)
