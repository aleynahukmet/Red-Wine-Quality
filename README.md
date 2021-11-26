# Red-Wine-Quality
<p align="center"> 
   <img alt="https://user-images.githubusercontent.com/87663976/143587865-0353804c-4e63-403f-9377-a87a10f3eb3f.jpg">
</p>

In this project we trying to predict the quality of red wine. We are having data analysis and visualization to understand the relationship between some features and wine quality.

# Dataset
Input variables:

1 - fixed acidity: most acids involved with wine or fixed or nonvolatile (do not evaporate readily)
2 - volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste
3 - citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines
4 - residual sugar: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet
5 - chlorides: the amount of salt in the wine
6 - free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine
7 - total sulfur dioxide: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine
8 - density: the density of water is close to that of water depending on the percent alcohol and sugar content
9 - pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale
10 - sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant
11 - alcohol: the percent alcohol content of the wine

Output variable (based on sensory data):
12 - quality (score between 0 and 10)

# Exploratory Data Analysis
There were no missing values on the dataset so I straight up started data visualization. I firstly wanted to see correlation so I used correlation heatmap and later used scatter plot for quality and other features.And then I used a count plot for distribution visualization.
<p align="center"> 
   <img alt="Ekran Resmi 2021-06-28 01 15 28" src="https://user-images.githubusercontent.com/87663976/143588844-924fac8e-f68d-47cc-9c72-c3e11bd2362d.png">
</p>

<p align="center"> 
   <img alt="Ekran Resmi 2021-06-28 01 15 28" src="https://user-images.githubusercontent.com/87663976/143588744-ec34f1bb-5616-4007-bd00-dc0a4db00c53.png">
</p>

# Models 
I trained six different models for this prediction(Logistic Regression,Random Forest, KNN,Gradient Boosting Regressor and SGB) to see which one is the giving best results. Then I plotted the results of the different models for comparison.

<p align="center"> 
   <img alt="Ekran Resmi 2021-06-28 01 15 28" src="https://user-images.githubusercontent.com/87663976/143589235-e8df3041-6f1d-4a15-93d6-2b6f636fc498.png">
</p>

