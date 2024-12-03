# 📊 **Descriptive Statistics in Jamovi: Example and Explanation**

---

### **Scenario: Comparing Two High School Classes**

We are comparing the performance of two high school classes based on a test:
1. **Scuola della Vita:** A typical high school class.
2. **Liceo Scientifico Paperino:** A class from a scientific high school.

Each class consists of 40 students who were assessed on the same test. Our goal is to analyze their performance using **central tendency indices** and **dispersion indices**, followed by graphical representation to better understand the distributions.

📥 **Download the dataset:** [Two Classes Comparison (ZIP)](dataset/two_classes_comparison.csv.zip)

---

## 🧮 **Step 1: Central Tendency Indices**

1. **Import the CSV file into Jamovi.**
   - Go to **File → Open** and load the dataset.

2. **Analyze Central Tendency:**
   - Navigate to the **Descriptives** module.
   - Drag the `Score` variable into the **Variables** box.
   - Drag the `Class` variable into the **Split by** box.

3. **Select Key Indices:**
   - **Mean:** The average score for each class.
   - **Median:** The middle score when data is sorted.
   - **Mode:** The most frequently occurring score.

📌 **Question:** Based on these indices, do the two classes perform similarly?  
- Compare the means and medians of both classes for symmetry.  
- Check the mode for distinct or absent patterns in score frequency.

---

## 📐 **Step 2: Dispersion Indices**

4. **Enable Additional Statistics:**
   - Under **Descriptives**, select:
     - **Standard Deviation (SD):** Measures variability around the mean.
     - **Range:** Difference between the highest and lowest scores.
     - **Interquartile Range (IQR):** Range of the middle 50% of scores.

📌 **Question:** Can dispersion indices alone provide a clear understanding of variability?  
- High SD or range may indicate greater variability in scores.  
- A large difference in IQR suggests uneven score distribution.

---

## 📊 **Step 3: Graphical Representation**

5. **Generate Visualizations:**
   - **Histograms:** Display the frequency of scores for each class.  
     - Class A should show a single peak (unimodal).  
     - Class B will likely show two peaks (bimodal).  
   - **Boxplots:** Compare the spread, median, and outliers for each class.

---

## 📝 **Explanation of Results (Corrigée)**

### **Class A (Scuola della Vita):**
- The histogram shows a **single peak** near the average score.  
- Most students perform around the mean, with minimal outliers.  
- This distribution is **unimodal** and relatively symmetrical.

### **Class B (Liceo Scientifico Paperino):**
- The histogram reveals **two peaks**:  
  - One peak for high-performing students.  
  - Another peak for low-performing students.  
- This is a **bimodal** distribution, reflecting significant performance disparity.

---

## 🔍 **Key Insights**
- **Central Tendency:** While the mean for both classes may be similar, it does not fully capture their differences.  
- **Dispersion Indices:** Highlight the variability within each class, with Class B showing a much higher spread.  
- **Visual Representations:** Crucial for understanding unique patterns such as bimodal distributions in Class B.

---

This example demonstrates the importance of combining **numerical summaries** and **graphical tools** to understand and interpret data distributions effectively.

🔙 **[Return to Index](index.md)**
