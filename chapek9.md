# 📝 **Exercise: Planet Chapek 9**

Inspired by the fictional planet **Chapek 9** from the television show *Futurama*, this dataset examines the preferences of humans and robots. To gain access to the capital city, visitors must prove they are robots by expressing a preference for **puppies**, **flowers**, or **large, properly formatted data files**. 

Your task is to determine whether the group of humans that took the test can gain access based on their preferences compared to robots.

---

### **Dataset Location**  
Navigate to: **Data Library > lsj-data > Chapek 9**

---

## **Instructions**

### **1️⃣ Check the Data**  
- Summarize the data:
  - Calculate the frequencies of preferences for humans and robots.
  - Report the number of humans who attended the test.  
- Visualize the preferences:
  - Use bar plots to compare the distribution of preferences between humans and robots.

---

### **2️⃣ Write the Hypothesis**

- **Null Hypothesis (H₀):** Humans and robots have **similar preferences** for puppies, flowers, and large data files.  
- **Alternative Hypothesis (H₁):** Humans and robots have **different preferences** for puppies, flowers, and large data files.  

---

### **3️⃣ Choose the Appropriate Test**

- Use a **Chi-Square Test for Independence** to analyze whether preferences are associated with being human or robot.  
- **Assumptions to Check**:
  1. The data must consist of **frequencies** (not percentages or raw scores).  
  2. Each observation must belong to only one category (e.g., one preference per individual).  
  3. Expected frequencies in each cell should generally be ≥ 5.  

---

### **4️⃣ Report the Results**

- Include:
  1. **Chi-Square Statistic (χ²):** Test result value.  
  2. **Degrees of Freedom (df):** Number of categories minus constraints.  
  3. **P-value:** Indicates if results are statistically significant.  
  4. **Effect Size:** Consider using Cramér’s V to assess the strength of association.  

- Provide a clear interpretation:
  - Does the data support the hypothesis that humans and robots have different preferences?
  - Can the humans who took the test plausibly "prove" they are robots based on their preferences?

---

🔙 **[Return to Day 3](day3.md)** 

