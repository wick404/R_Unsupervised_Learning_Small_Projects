# R_Unsupervised_Learning_Small_Projects
During the first semester of my Data Science MSc studies at the University of Warsaw, as part of the Unsupervised Learning course, I completed 3 small projects in the following areas:
- Clustering
- Dimension Reduction
- Association Rules

Since these projects are not too long and advanced, I provide a short description to each and the link to view the uploaded R Markdown files as HTML.

## F1 Qualyfing 2022 Clustering
### Introduction:
In this project, I analyze and cluster the 2022 Formula 1 season’s qualifying results to understand how drivers and teams would fit into clusters based on their qualifying performance. The analysis begins with a single qualifying session and then extends to each race weekend of the season to evaluate drivers' and teams' performance throughout the year.

### Results:
After determining that hierarchical clustering is the most appropriate, based on the whole season's qualyfing performances, the teams are ranked from best to worst in qualyfing in the following order:
1. Ferrari
2. Red Bull Racing RBPT
3. Mercedes
4. Alpine Renault
5. McLaren Mercedes
6. Alfa Romeo Ferrari
7. Alpha Tauri RBPT
8. Haas Ferrari
9. Aston Martin Aramco Mercedes
10. Williams Mercedes


Link to the exported HTML of the project: 
- https://htmlpreview.github.io/?https://github.com/wick404/R_Unsupervised_Learning_Small_Projects/blob/main/Viktor%20Sas%20Clustering.html





## Dimension Reduction - Diabates Dataset
### Introduction:
The goal of this dimension reduction project is to optimize the analysis of a diabetes dataset collected from the Iraqi society. The dataset includes essential medical laboratory data such as Blood Sugar Level, Age, Gender, Creatinine ratio (Cr), BMI, Urea, Cholesterol (Chol), Fasting lipid profile, HBA1C, and more.

### Results:
Through dimension reduction, we have successfully reduced the original 10 dimensions to 4, preserving almost 60% of the variance. This reduction facilitates a more efficient and insightful analysis of the diabetes dataset.

##### The variables contributing the most to each component are as follows:
- Component 1: CLASS, HbA1c, BMI, Age
- Component 2: Cr, Urea, Gender
- Component 3: Chol, LDL, TG
- Component 4: VLDL, Gender, HDL, Chol

Link to the exported HTML of the project: 
- [https://htmlpreview.github.io/?https://github.com/wick404/R_Unsupervised_Learning_Small_Projects/blob/main/Viktor%20Sas%20Clustering.html](https://htmlpreview.github.io/?https://github.com/wick404/R_Unsupervised_Learning_Small_Projects/blob/main/Viktor%20Sas%20Dimension%20reduction.html)




##  Association Rule Analysis in Supermarkets and Convenience Stores
### Introduction:
This project analyzes the association rules between products in supermarkets and convenience stores to determine how the purchase of certain products impacts the likelihood of purchasing other goods.

### Results:
By using association rule mining, we gain insights into customer purchasing behaviors and discover which products are likely to trigger the purchase of other products. These insights can help supermarkets and convenience stores make informed decisions about product organization and marketing strategies.

##### Finding Rules Based on Specific Products:
In supermarkets, purchasing Pancake Mix is often associated with buying Chips, Light Bulbs, and Onions. In convenience stores, buying Shampoo is linked to purchasing Toothpaste, Shaving Cream, Trash Bags, and Dish Soap.

##### Inspecting Rules by Confidence:
In supermarkets, there is over a 10% probability of buying Toothpaste if Extension Cords or Broom are in the basket. In convenience stores, the probability of purchasing Toothpaste is over 12% if Dustpan or Bath Towels are in the basket.

##### Inspecting Rules by Lift:
The highest lift in supermarkets is between Syrup and Tea, indicating a strong association. In convenience stores, strong lifts are observed between Cleaning Spray + Salmon, Paper Towels + Tea, and Hygiene Products + Pasta.

##### Inspecting Rules by Support:
Toothpaste frequently appears in transactions with Extension Cords, Broom, and Trash Cans in supermarkets, and with Dustpan, Bath Towels, and Carrots in convenience stores.

Link to the exported HTML of the project: 
- https://htmlpreview.github.io/?https://github.com/wick404/R_Unsupervised_Learning_Small_Projects/blob/main/Viktor%20Sas%20association%20rules.html

