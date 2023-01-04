In this project, we will be working with medical examination data from patients to explore the relationship between cardiac disease and various factors such as body measurements, blood test results, and lifestyle choices.

Our first task will be to create a chart showing the counts of good and bad outcomes for the cholesterol, gluc, alco, active, and smoke variables for patients with cardio=1 and cardio=0 in different panels. To do this, we will need to use matplotlib, seaborn, and pandas to visualize and manipulate the data.

Next, we will add an overweight column to the data by calculating each patient's Body Mass Index (BMI) and using this value to determine whether they are overweight or not. We will then normalize the data by making 0 always good and 1 always bad for the cholesterol and gluc variables.

We will then convert the data into long format and use seaborn's catplot() function to visualize the value counts of the categorical features, split by the 'Cardio' column.

After that, we will clean the data by filtering out any patient segments that represent incorrect data. This will include removing any rows where the diastolic pressure is higher than the systolic pressure, as well as rows where the height or weight is outside of certain percentiles.

Finally, we will create a correlation matrix using the cleaned dataset and visualize it using seaborn's heatmap(). We will mask the upper triangle of the matrix to focus on the relationships between the variables.

Overall, this project will involve using various data visualization and manipulation techniques to better understand the relationships between cardiac disease and various other factors in the medical examination data.
