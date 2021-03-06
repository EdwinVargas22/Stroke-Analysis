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
Using Tableau, we analyzed the top five ages who are already diagnosed with cardiovascular disease. We explored their specific health data to help us understand how the key factors have a role in increasing the chance of getting cardiovascular diseases among those people. 

Key factors that increase the risk of getting cardiovascular diseases:

<img width="487" alt="key_factors" src="https://user-images.githubusercontent.com/70189344/109913954-c7c33e00-7c63-11eb-88a8-b3652f46f720.png">

Top 5 ages with cardiovascular diseases:

<img width="698" alt="top_5_ages" src="https://user-images.githubusercontent.com/70189344/109913981-d7db1d80-7c63-11eb-8276-06d9a2d536ed.png">

Stroke mortality by states:

<img width="519" alt="stroke_mortality_map" src="https://user-images.githubusercontent.com/70189344/109913989-dad60e00-7c63-11eb-89ea-fde638df30bd.png">

## Data Exploration
![Avg_Stroke_Heart_Disease](https://user-images.githubusercontent.com/60836219/109912056-356d6b00-7c60-11eb-9ff5-374304f822a8.png)

This is one example of the bar charts we created. We separated by gender and then we wanted to compare if having heart disease versus not having heart disease will lead you to have a higher chance of having a stroke. From this bar chart, it appears people who do have heart disease have a higher chance of getting a stroke.

![Correlation_Age_Stroke](https://user-images.githubusercontent.com/60836219/109912062-38685b80-7c60-11eb-8dcd-72506a47f53e.png)

This is one example of the boxplot we created. This boxplot was also separated by gender and we wanted to see if age is a major factor of having a stroke. For this boxplot it tells us people who are holder have a higher chance of having a stroke compared to people who don't.

![Correlations](https://user-images.githubusercontent.com/60836219/109912072-3bfbe280-7c60-11eb-8bdc-1b5d243f83a6.png)

For this heatmap correlation we wanted to see if there was any strong correlations with the other factors that were in the stroke dataset. It appears there isn't any strong correlation but we did come into conclusion that all the factors are dependent of each other for someone having a higher chance of having a stroke which explains why the heatmap correlation wasn't strong.

## Machine Learning


## Conclusion/Take Away
The outcome was something different than we originally thought. We learned there are a lot of factors that contribute to having a stroke and these factors are dependent of each other. If you have heart disease it does not necessarily mean you will have a stroke because your average glucose levels and other factors could fall in the recommended healthy levels. With a larger dataset and balancing our desired output before training the model, we could have better results to work with. With a more viable dataset, our machine learning model would have been able to predict accurately whether or not patient's would be at risk or not for stroke. Also, implementing more algorithms besides logistic regression would have been able to see if other models would have been fit for our situation.




