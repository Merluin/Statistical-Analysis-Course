# 🖥️ **Excel: A Basic Introduction**

Excel is a versatile and powerful tool for organizing, analyzing, and visualizing data. This page will guide you through its essential features and explain how to transform data for analysis.

---

## 📊 **What is Excel?**

Microsoft Excel is widely used for:
- 📂 Organizing data into rows and columns.
- 📈 Performing calculations and creating charts.
- 🔍 Exploring and analyzing datasets.

Its features make it a go-to tool for both beginners and professionals in data analysis.

---

## 🔄 **Wide vs. Long Format in Data**

Using the provided dataset, we can demonstrate the difference between **wide** and **long** data formats.

### **Wide Format:**
Each row represents a single observation, with variables in separate columns.

| **Name**     | **IQ** | **Size (cm)** | **Weight (kg)** | **Age**    |
|--------------|--------|---------------|-----------------|------------|
| Valentino    | 179    | 89            | 78              | over 30    |
| Peppina      | 120    | 55            | 78              | under 30   |

**Key Features:**
- Easy to read for small datasets.
- Columns represent different variables.

---

### **Long Format:**
Each observation is recorded in a separate row, with variables categorized in one column.

| **Name**     | **Variable** | **Value**  |
|--------------|--------------|------------|
| Valentino    | IQ           | 179        |
| Valentino    | Size (cm)    | 89         |
| Valentino    | Weight (kg)  | 78         |
| Valentino    | Age          | over 30    |
| Peppina      | IQ           | 120        |
| Peppina      | Size (cm)    | 55         |
| Peppina      | Weight (kg)  | 78         |
| Peppina      | Age          | under 30   |

**Key Features:**
- Useful for plotting and advanced analysis.
- Ideal for tools like R, Jamovi, or Python.

📥 **Download Dataset:**  
[Dataset](dataset/VeryFakeData.zip)

---

## 🛠️ **Basics of Using Excel for Data Analysis**

### 1️⃣ **Recopy Handle (Fill Handle):**
- The fill handle helps replicate data or formulas.
- Drag the square at the bottom-right of a cell to copy across adjacent cells.
- **Example with References:**
  - `$B$1`: Locks both row and column.
  - `$B1`: Locks column only.
  - `B$1`: Locks row only.

---

### 2️⃣ **Checking Cell Format:**
Ensure your data is interpreted correctly:
- Navigate to **Home → Number** and select the desired format (e.g., Number, Text).
- Example: Use "Number" for calculations.

---

### 3️⃣ **Using Functions:**

| **English Function**   | **Italian Function**         | **Description**                               | **Example (Italian)**       |
|-------------------------|------------------------------|-----------------------------------------------|------------------------------|
| `=AVERAGE(range)`       | `=MEDIA(intervallo)`         | Calculates the mean of a range.               | `=MEDIA(A1:A10)`            |
| `=SUM(range)`           | `=SOMMA(intervallo)`         | Adds all values in a range.                   | `=SOMMA(B1:B10)`            |
| `=COUNT(range)`         | `=CONTA.NUMERI(intervallo)`  | Counts numeric entries in a range.            | `=CONTA.NUMERI(C1:C10)`     |
| `=STDEV.S(range)`       | `=DEV.ST(intervallo)`        | Calculates sample standard deviation.         | `=DEV.ST(D1:D10)`           |

💡 Use Excel’s **Function Wizard** for localized names and guidance.

---

## 📥 **Importing CSV Files into Excel**

### What is a CSV file?  
A **CSV (Comma-Separated Values)** file stores data in plain text, separating values with commas or semicolons.

---

### **Steps to Import a CSV File:**
1. Open Excel.
2. Go to **File → Open** and select your CSV file.
3. Use the **Text Import Wizard** to configure delimiters (`;` or `,`).

**Key Warning:**
- European formats use `;` and `,` for decimals.
- Adjust in **File → Options → Advanced → Editing Options**.

---

## 🎉 **Conclusion**

Excel is a robust platform for data exploration. By mastering basics like the fill handle, formatting, and functions, you can efficiently analyze and visualize datasets.

🔙 **Return to [Day 2](day2.md)**
