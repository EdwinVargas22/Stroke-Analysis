# Stroke-Analysis
![iStock-1168179082](https://user-images.githubusercontent.com/60836219/109908654-829a0e80-7c59-11eb-89e6-eb4c78c955c3.jpg)

Stroke affects 15 million people worldwide each year and out of those 15 million people, about 5 miliion die.

Two of our datasets were found in Kaggle and the third dataset was found in the Centers for Disease Control and Prevention.

In our analysis, we found a stroke and cardiovascular disease dataset that provides patient demographics, life-style habits and specific health indicators that can identify if they are likely to experience a cardiovascular disease, specifically a stroke. The mortality dataset provides information of the total number of people who died from a stroke in each state. Our objective here is to analyze what factors could lead to someone having a stroke and the likelihood of that person having a stroke. 

## Cleaning Dataset

### HealthCare Dataset
* Removed the column id
* Drop NaN values in the bmi column
* Removed "Other" in the gender column and removed "children" in the work type column
* Used count() function to check if each column had the same number of values
* After all of this was done, saved the clean dataset.

### Cardiovascular Dataset
* Renamed the column names
* Changed the object type for certain columns
* Changed the age values to years
* After all of this was done, saved the clean dataset.

## Tableau


### Data Exploration
![Avg_Stroke_Heart_Disease](https://user-images.githubusercontent.com/60836219/109912056-356d6b00-7c60-11eb-9ff5-374304f822a8.png)

![Correlation_Age_Stroke](https://user-images.githubusercontent.com/60836219/109912062-38685b80-7c60-11eb-8dcd-72506a47f53e.png)

![Correlations](https://user-images.githubusercontent.com/60836219/109912072-3bfbe280-7c60-11eb-8bdc-1b5d243f83a6.png)

Used Matplotlib and Seaborn to create the catplots, boxplots, and heatmap charts.

