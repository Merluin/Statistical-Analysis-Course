# 📊 **Day 5: Null Hypothesis Testing, t-Test, Chi-Square**  

Welcome to the third day of the course! Today, we dive into inferential statistics and learn how to perform a t-test and a chi-square test.

---

## 🗂️ **Topics**

- 🎁 **Predicting Santa’s Gift Delivery**  
- 🍬 **Toys production**  
- ✨ **Elf Socks and Sizes**
- 🎄 **Fulmine and Rudolf's Favorite Food**
- 💵 **Scrooge Company Bias Investigation**
- 🎅🏻 **Santa’s Fireplace Size vs Belly Size**

---
for each exercise: 
Tasks:
Determine the Test to Use.
Analyze the Data.
Restituate  briefly the results

---

## 🎁 Predicting Santa’s Gift Delivery
Santa wants to predict how many gifts he can deliver based on the hours of travel time available on Christmas Eve. Over the past 100 years, he collected data on:

Travel Hours (continuous)
Santa wants to predict how many gifts he can deliver based on the hours of travel time available on Christmas Eve. As the population increase each years, he assume that there are 2 billion child. He collects data on the number of hours he traveled (continuous) and the number of gifts delivered (integer the number is provided in million) over the past 100 years.

Question: What test should Santa use to determine if travel time can predict the number of gifts delivered?
How much time Santa need to deliver all gift this year?

Data are available in Santa_gift.csv

--- 

## 🍬 Toys production
The elves are analyzing the efficiency of their toy production. They want to predict the total production of toys (continuous) based on two factors: the number of elves working in the workshop (continuous) and the average number of candy canes consumed per elf (continuous).

Question: What test should the elves use to evaluate the combined effects of these variables on toy production?

Data are available in Toys_production.csv

---

✨ Elf Socks and Sizes
Santa wants to ensure all his elves are comfortable and stylish, so he's analyzing their preferences for sock colors and their sizes. Consider that all this dataset includes all elves polpulation.

Dataset Information:
Elf_Name: ID of each elf (for ethical reason the elf ìname has been anonimised).
Sock_Color_Preference: The elf’s preferred sock color (Stripe, Plain Red, Plain White).
Elf_Size_cm: The height of the elf in centimeters.
Tasks:
Analyze Sock Color Preferences:
Count the number of elves who prefer each sock color.
Visualize the preferences using a bar chart.
Analyze Elf Sizes:
Calculate the average height of elves.
Find the tallest and shortest elves.
Create a histogram of elf sizes.
Relate Sock Preferences to Sizes:
Compare the average height of elves who prefer each sock color.

---

###🎄 Fulmine and Rudolf's Favorite Food

Fulmine and Rudolf are two of Santa’s trusted reindeer, but they seem to have different preferences when it comes to food. Santa wants to analyze whether there is an **association** between the reindeer's name (Fulmine or Rudolf) and their food preference.


Use a test to determine if there is a relationship between the reindeer (Fulmine or Rudolf) and their food preference.  

Dataset:
The dataset includes the following columns:
1. **Reindeer**: The name of the reindeer (Fulmine or Rudolf).  
2. **Food_Preference**: The reindeer's preferred food, which can be:
   - **Carrots**  
   - **Apples**  
   - **Hay**  

The dataset file is Fulmine_Rudolf_Food.csv

---

## 💵 Scrooge Company Bias Investigation
Scrooge Company suspects that Santa may be biased in distributing gifts across the continents. They want to analyze whether Santa's distribution matches the expected proportion of children in each continent.

Objective:
Use a test to determine if the number of gifts distributed across continents aligns with the expected proportions.

Dataset:
The dataset includes the following columns:

Continent: The continent where the gifts were delivered (Asia, Africa, Europe, North America, South America, Oceania).
Gifts_Delivered: The count of gifts delivered to children on that continent.
Expected Proportions:
Scrooge Company provides the expected proportions of children in each continent:

Asia: 40%
Africa: 20%
Europe: 15%
North America: 10%
South America: 10%
Oceania: 5%

File: Scrooge_Company_Bias.csv

---

## 🎅🏻 Santa’s Fireplace Size vs Belly Size
Santa is concerned that his growing belly might make it harder to fit through chimneys. To prepare for Christmas Eve, he wants to compare the sizes of fireplaces in sampled households with his current belly size to determine if he needs to go on a diet.

Objective:
Use a test to determine if Santa’s belly size is significantly larger than the average fireplace size.

Dataset:
The dataset includes the following columns:

Household: The name or ID of the household.
Fireplace_Size_cm: The size of the fireplace opening in centimeters.
Santa_Belly_Size_cm: Santa’s belly size for comparison (assume Santa’s belly size now is 130 cm).

File: Fireplace_vs_Belly.csv
