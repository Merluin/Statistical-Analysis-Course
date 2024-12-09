# 📝 **Exercise: Student Grades in Dr. Chico's Class**

Dr. Chico evaluates the performance of his students twice during the semester to help them improve their study methodologies. He believes that with his approach, students will perform better on the final exam compared to their initial test.

---

### **Dataset Location**  
Navigate to: **Data Library > lsj-data > chico**

---

## **Instructions**

### **1️⃣ Check the Data**  
- Summarize the data:
  - Calculate descriptive statistics (e.g., mean, median, standard deviation) for grades from both tests.  
- Visualize the data:
  - Use histograms or boxplots to examine the distribution of grades for the two tests.

---

### **2️⃣ Write the Hypothesis**

- **Null Hypothesis (H₀):** The mean grades of the first and second tests are **equal** (no improvement in student performance).  
- **Alternative Hypothesis (H₁):** The mean grades of the second test are **higher** than the first test (students improved their performance).  

---

### **3️⃣ Choose the Appropriate Test**

- Since the data involves comparing the same students' performance across two time points:
  - Use a **paired samples t-test** to compare the means of the two tests.  
  - Check assumptions:
    - Test for normality of the difference scores (e.g., Shapiro-Wilk test).  
  - If assumptions are violated, consider a **non-parametric test** like the Wilcoxon signed-rank test.

---

### **4️⃣ Report the Results**

- Include:
  1. **Test statistic** (e.g., t-value for paired t-test or W-value for Wilcoxon test).  
  2. **Degrees of freedom (df)** for the test.  
  3. **P-value** to determine statistical significance.  
  4. **Effect size** (e.g., Cohen’s d for paired t-test).  

- Provide a clear interpretation:
  - Does the data support the hypothesis that students performed better on the final exam?  
  - What does this mean for Dr. Chico's study methodology?

---

🔙 **[Return to Day 3](day3.md)**  
