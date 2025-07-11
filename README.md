# DataXact

The clarity of the documentation- Studying the dataset

In the dataset under consideration, there were initially five distinct files. Among these files, three of them shared a common row labeled as "295719," while the remaining two files contained identical rows labeled as "295881." Consequently, we merged the three files with the matching row label into a single dataset.
Upon examining the merged data, we discovered that out of the total 295881 rows present in the two aforementioned files, (295881- 295719= 162), 162 rows consisted entirely of null values. Subsequently, we proceeded to remove these 162 rows from the dataset. Following this data cleansing step, we combined all five files together, resulting in a comprehensive dataset.
The subsequent slide illustrates the composition and characteristics of each individual file within the dataset.




How our Dataset looks?

The data which we made by joining the 5 files is composed as:
Book1       -  From this dataset we have included the column R5, R6, R7 and R8 and eliminated R13    
                    and R14.
Book(i48) - From this dataset, all the columns are taken.
Book3      - From this dataset, all the columns are taken.
Book(i4)   - From this dataset, all the columns are taken.
Book5      -  From this dataset we have included the column R13 and R14, and eliminated Flow rate 
                    and Heater Voltage.




Model Selection

Model selection is the process of choosing one among many candidate models for a predictive modeling problem.
There may be many competing concerns when performing model selection beyond model performance, such as complexity, maintainability, and available resources.
The two main classes of model selection techniques are probabilistic measures and resampling methods.
For our model since it is Supervised and values to be predicted are continuous data we are going with Multiple Linear Regression.
Multiple linear regression is a regression model that estimates the relationship between a quantitative dependent variable and two or more independent variables using a straight line.
The dataset includes various independent variables such as Time (s), Humidity (%r.h.), Temperature (C), Flow rate (mL/min), Heater voltage (V), and multiple resistance values (R1 to R14). The output variable of interest is the CO concentration (ppm).
Prior to training the model, it is crucial to examine the relationship between the independent variables and the target variable. Visualizations can help identify any patterns or correlations between the independent variables and the CO concentration. This step aids in understanding the data and assists in making informed decisions during feature selection.
