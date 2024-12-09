# 📝 **Exercise: Student Grades in Dr. Harpo's Class**

Dr. Harpo's students are divided between two tutors. Dr. Harpo wants to know if the tutors provide the same level of support to students. He believes the quality of tutor support can be reflected in student performance (grades). 

---

### **Dataset Location**  
Navigate to: **Data Library > lsj-data > Harpo**

---

## **Instructions**

### **1️⃣ Check the Data**  
- Summarize the data:
  - Calculate descriptive statistics (e.g., mean, median, standard deviation) for each tutor group.
- Visualize the data:
  - Create histograms or boxplots to compare grade distributions between the two tutor groups.

---

### **2️⃣ Write the Hypothesis**

- **Null Hypothesis (H₀):** The mean grades of the two tutor groups are **equal** (i.e., there is no difference in student performance between tutors).  
- **Alternative Hypothesis (H₁):** The mean grades of the two tutor groups are **not equal** (i.e., student performance differs between tutors).  

---

### **3️⃣ Choose the Appropriate Test**

- Since there are two groups to compare:
  - Use an **independent samples t-test** (if assumptions of normality and homogeneity of variances are met).
  - If assumptions are violated, consider a **non-parametric test** like the Mann-Whitney U test.  
- Check assumptions:
  - Test for normality (e.g., Shapiro-Wilk test).
  - Test for equal variances (e.g., Levene’s test).

---

### **4️⃣ Report the Results**

- Include:
  1. **Test statistic** (e.g., t-value for t-test or U-value for Mann-Whitney test).  
  2. **Degrees of freedom (df)** for the test.  
  3. **P-value** to determine statistical significance.  
  4. **Effect size** (e.g., Cohen’s d for t-test).  

- Provide a clear interpretation:
  - Does the data support the hypothesis that the tutors provide different levels of support based on student grades?  
  - What does this mean for Dr. Harpo's assumption about tutor support?

---

🔙 **[Return to Day 3](day3.md)**  
