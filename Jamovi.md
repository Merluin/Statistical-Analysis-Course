### **Descriptive Statistics in Jamovi: Example and Explanation**

#### **Scenario: Comparing Two High School Classes**

We are comparing the performance of two high school classes based on a test:
1. **Scuola della Vita:** A typical high school class.
2. **Liceo Scientifico Paperino:** A class from a scientific high school.

Each class consists of 40 students who were assessed on the same test. Our goal is to analyze their performance using **central tendency indices** and **dispersion indices**, followed by graphical representation to better understand the distributions.

Download the [data](dataset/two_classes_comparison.csv.zip)
---

#### **Step 1: Central Tendency Indices**

1. Import the CSV file into **Jamovi**.
2. Go to the **Descriptives** module and drag the `Score` variable into the **Variables** box and the `Class` variable into the **Split by** box.
3. Select central tendency indices such as:
   - **Mean:** Average score of each class.
   - **Median:** The middle score when data is sorted.
   - **Mode:** The most frequently occurring score.

**Question:** Based on these indices, do the two classes perform similarly?  
- Observe if the **mean** and **median** are close, suggesting symmetry in the data.
- If the mode is distinct or absent, it might indicate differences in score distribution.

---

#### **Step 2: Dispersion Indices**

4. Enable additional statistics under the **Descriptives** settings:
   - **Standard Deviation (SD):** Measures variability around the mean.
   - **Range:** Difference between the highest and lowest scores.
   - **Interquartile Range (IQR):** Range of the middle 50% of scores.

**Question:** Can you interpret the dispersion indices without graphical representation?  
- A higher standard deviation or range suggests greater variability.
- Differences in IQR may indicate uneven spread in the middle scores.

---

#### **Step 3: Graphical Representation**

5. Generate visualizations in Jamovi:
   - **Histograms:** Display the frequency of scores for each class.
   - **Boxplots:** Compare the spread, median, and potential outliers between classes.

---

#### **Explanation of Results (Corrigée):**

**Class A (Scuola della Vita):**
- The histogram shows a **single peak** near the average score.
- Most students perform around the mean, with few outliers at the extremes.
- This distribution is **unimodal** and relatively symmetrical.

**Class B (Liceo Scientifico Paperino):**
- The histogram reveals **two peaks** in the distribution:
  - One group of students performs very well (high scores).
  - Another group performs poorly (low scores).
- This is a **bimodal** distribution, with significant variability in scores.

---

#### **Key Insights:**
- While the **mean** may be the same for both classes, it fails to capture the differences in score distributions.
- The **dispersion indices** and **visualizations** provide critical insights:
  - Class A demonstrates consistent performance.
  - Class B shows significant performance disparity, highlighting two distinct subgroups.

This example underscores the importance of using both numerical summaries and graphical tools to understand data fully.
