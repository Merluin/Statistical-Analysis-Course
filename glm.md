# 📝 **Exercise: Dani's Mood**

The dataset we’ll use is fictitious but reflects real-life events. Dani wants to measure how his son’s sleeping habits affect his mood. He recorded his **grumpiness**, **his sleeping habits**, and **his son’s sleeping habits** over several days. The dataset is saved as **`parenthood.csv`** and contains the following variables:

- **dani.sleep**: Dani's sleeping hours  
- **baby.sleep**: Baby's sleeping hours  
- **dani.grump**: Dani's grumpiness (0–100 scale)  
- **day**: Number of recorded days  

---

### **Dataset Location**  
Navigate to: **Data Library > lsj-data > Parenthood**

---

## **Exercise Instructions**

---

### **1️⃣ Check the Data**  
- **Load the Dataset**: Open the `parenthood.csv` file in Jamovi.  
- **Adjust Variable Types**:
  - Ensure **dani.sleep**, **baby.sleep**, and **dani.grump** are specified as **continuous variables**.  
  - The **day** variable is nominal (integer).  

---

#### **Descriptive Statistics**  
- Summarize each variable (**dani.sleep**, **baby.sleep**, **dani.grump**):  
  - **Mean**, **Standard Deviation**, **Minimum**, and **Maximum**.  

#### **Graphical Representation**  
- Create histograms or boxplots to visualize each variable.  
- Create scatterplots between variables (e.g., **dani.sleep** vs **dani.grump**).

---

### **2️⃣ Write the Hypotheses**

Identify the **Dependent Variable (DV)** and **Independent Variable(s) (IV)**:  

- **DV**: dani.?
- **IV (simple regression)**: dani.? 
- **IVs (multiple regression)**: dani.? and baby.sleep  

---

Write the Hypotheses:

- **Null Hypothesis (H₀)**: The IV(s) have no effect on Dani's ?.  
- **Alternative Hypothesis (H₁)**: The IV(s) influence Dani's ?.  

---

### **3️⃣ Check Correlation Between Variables**

#### **Correlation Matrix**  
- Generate a **correlation matrix** for the following variables:  
  - **dani.sleep**, **baby.sleep**, and **dani.grump**.  
- Include the following correlation coefficients:  
  - **Pearson**: Measures linear correlation.  
  - **Spearman**: Measures rank correlation.  

#### **Graphical Representation**  
- Create a scatterplot matrix to visualize the relationships between variables.

---

### **4️⃣ Simple Regression Analysis**  

#### **Test Relationship Between Dani's Sleep and Grumpiness**  
1. Perform a **simple regression** where:  
   - **DV**: dani.?  
   - **IV**: dani.?  

2. **Report the Results**:
   - Write the regression equation:  
     \[
     \text{Dani's ?} = b_0 + b_1(\text{Dani's ?}) + \epsilon
     \]
   - Report the following statistics:  
     - **R²**: Proportion of variance explained.  
     - **Regression coefficient (b1)**: Effect of Dani's sleep on grumpiness.  
     - **p-value**: Statistical significance.  

3. **Interpretation**:
   - Is the relationship significant?  
   - What does this tell us about the impact of Dani's sleep on his grumpiness?

---

### **5️⃣ Multiple Regression Analysis**

#### **Test the Combined Effect of Dani's and Baby's Sleep**  
1. Perform a **multiple regression** where:  
   - **DV**: dani.grump  
   - **IVs**: dani.sleep and baby.sleep  

2. **Report the Results**:
   - Write the regression equation:  
     \[
     \text{Dani's grumpiness} = b_0 + b_1(\text{Dani's sleep}) + b_2(\text{Baby's sleep}) + \epsilon
     \]
   - Report the following statistics:  
     - **R²**: Proportion of variance explained.  
     - **Regression coefficients (b1, b2)**: Effects of Dani's and Baby's sleep.  
     - **p-values**: Statistical significance for each predictor.  

3. **Interpretation**:
   - Which predictor is most influential?  
   - Does Baby's sleep significantly impact Dani’s grumpiness when controlling for his own sleep?

---

### **6️⃣ Write Up the Results**

Provide a brief summary of findings:

1. **Correlation Analysis**: Summarize correlations between the variables.  
2. **Simple Regression**: Report the effect of Dani's sleep on grumpiness.  
3. **Multiple Regression**: Report the combined effect of Dani's and Baby's sleep.  

---

🔙 **[Return to Day 4](day4.md)**  
