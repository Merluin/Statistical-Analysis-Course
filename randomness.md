# ♥️♠️♦️♣️ **Exercise: Random Playing Cards**

Your task is to determine whether humans are capable of generating truly random choices. In theory, in a standard deck of playing cards, the four suits (Hearts, Diamonds, Clubs, Spades) are equally distributed, so each suit has the same probability of being chosen. However, when we ask participants to name a card, biases may exist. Your job is to analyze the data and figure out whether human choices are random or exhibit systematic bias. We focused on only on "choice 1" output.

---

### **Dataset Location**  
Navigate to: **Data Library > lsj-data > Randomness**

---

## **Instructions**

### **1️⃣ Check the Data**  
- Summarize the data:
  - Calculate the frequencies of chosen suits (e.g., Hearts, Diamonds, Clubs, Spades).  
- Visualize the data:
  - Use a bar plot to compare the distribution of choices among the four suits.  

---

### **2️⃣ Write the Hypothesis**

- **Null Hypothesis (H₀):** Human choices are **random**, and all suits are equally likely to be chosen.  
- **Alternative Hypothesis (H₁):** Human choices are **not random**, and certain suits are chosen more frequently than others.  

---

### **3️⃣ Choose the Appropriate Test**

- Use a **Chi-Square Test for Goodness of Fit** to determine whether the observed distribution of choices deviates from the expected random distribution.  
- **Assumptions to Check**:
  1. The data must consist of **frequencies** (not percentages or proportions).  
  2. Each observation must belong to only one category (e.g., one suit per choice).  
  3. Expected frequencies for each suit should generally be ≥ 5.  

---

### **4️⃣ Report the Results**

- Include:
  1. **Chi-Square Statistic (χ²):** Test result value.  
  2. **Degrees of Freedom (df):** Number of categories minus 1 (e.g., 4 suits - 1 = 3).  
  3. **P-value:** Indicates whether results are statistically significant.  
  4. **Effect Size:** Consider using Cramér’s V to assess the strength of association.  

- Provide a clear interpretation:
  - Does the data support the hypothesis that human choices are random?  
  - If not, which suits are over- or underrepresented?  

---

### **Outcome Discussion**
Reflect on whether humans have cognitive biases when attempting to make random choices. What implications might this have for designing experiments or games involving human-generated randomness?

---

🔙 **[Return to Day 3](day3.md)**
