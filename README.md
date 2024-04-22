# Red-Wine-Quality

## INTRO
On 22nd of April 2024, I have downloaded a Kaggle dataset named Red Wine quality (you can access it here https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009), and wanted to perform an EDA - Explorative Data Analysis. The dataset itself is not balanced, meaning that there is more normal wines, than excellent or poor ones. We can call that a normal picture of the population itself - you don't encounter an excellent or a very poor wine that often, as much as you do with normal wines.

## ABOUT THE DATASET AND VARIABLES

There is 11 input variables, and 1 output variable:
1) fixed acidity - I
2) volatile acidity - I
3) citric acid - I
4) residual sugar - I
5) chlorides - I
6) free sulfur dioxide - I
7) total sulfur dioxide - I
8) density - I
9) pH - I
10) sulphates - I
11) quality - O (score between 0 and 10)

Additional citation - P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## USED TOOLS AND GOALS

For this analysis, I'm going to use the following tools:
1) Excel - to convert CSV file into Excel file
2) Tableau - to show graphic part of the analysis
3) R (R Studio) - for programming/coding and graphic part of the analyis using ggplot2 package

## GOAL OF THE ANALYSIS

The goal of this analyis is to see which of these 11 input variables have the most influence on the output variable, aka quality of the wine at the end.
