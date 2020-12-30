# Project_2020-Fundamentals-of-Data-Analysis
This repository includes all files and details relating to the Fundamentals of Data Analysis Project 2020. The goal of the project was to accurately predict wind turbine power output from wind speed values using the data set as a basis. 

Included in the repository is a jupyter notebook titled *'Project_2020-Fundamentals-of-Data-Analysis.ipynb'* This notebook starts off by investigating simple linear regression. As part of the initial investigation two different types of relationships are researched, they are;

- Deterministic
- Statistical

The research for the aforementioned relationships includes applied examples for both. Ohms law is used for deterministic and a weight-height relationship is used to demonstrate the statistical relationship. It is concluded that deterministic is outside the scope of this project and the focus from this point forward is on statistical regression analysis. Statistical simple linear regression is researched. As part of this research important considerations and assumptions are determined which are key for the completion of analysis within this notebook. That concluded the research part of the project, focus now switched to development section.

In the development section of this notebook there are two data sets considered;

- weight-height data set (linear relationship)
- power_production data set (curvelinear relationship)

The initial development analysed the simpler of the two data sets, namely the weight-height data set. This analysis included defining the coefficients which resulted in the straight line equation for the line of best fit for the data. The data was plotted inclusive of the newly defined line of best fit. The R-squared value was then calculated for the model. The obvious question then was if the line was a 'good' fit. To answer this question research was conducted to determine what qualified as a 'good' fit. This concluded the analysis of the weight-height data set.

Having completed the analysis on the weight-height data set and gaining important knowledge the more complex data set, namely the power_production data set was analysed. This analysis was split into 3 sections;

- Simple linear regression analysis
- Degree of the fitting polynomial set to 2
- Degree of the fitting polynomial set to 3

The first section repeated the steps from the weight-height data set analysis but a linear line did not fit the data set as good as a curved line would because the data had curvature. That said the analysis was still complete with the coefficients and the R-squared values determined.

The next section set the degree of the fitting polynomial to 2. This was a slight improvement on the linear line of best fit but still left room for improvement. Although the line wasn't the best fit the analysis was still complete with the coefficients and the R-squared values determined, it was possible to make comparisons with the linear model and this model to see which model was better, this was complete by comparing the R-squared values.

The third and final section set the degree of the fitting polynomial to 3. This was a significant improvement on both the linear and the polynomial degree of 2. With this model looking good the analysis was complete with the coefficients and the R-squared values determined. Again, it was possible to make comparisons with the linear model, the 2 degree model and this model to see which model was better, this was complete by comparing the R-squared values.

The R-squared values for the three sections were as follows;

- 72.89% - Simple linear regression analysis
- 73.52% - Degree of the fitting polynomial set to 2
- 87.97% - Degree of the fitting polynomial set to 3

From the results it can be seen that there was a significant improvement when the polynomial degree was set to 3 to allow for a good fit to the curvature of the data. This was no surprise having seen how improved the line fit the data in the plot when compared to the two previous models.

The model for the degree of the fitting polynomial set to 3 resulted in a R-squared value of 87.97% and was deemed sufficient for the this project and so the analysis was complete.

The goal of the project was to accurately predict wind turbine power output from wind speed values using the data set as a basis. Using the developed model with the degree of the fitting polynomial set to 3 it is felt that power output can indeed be accurately predicted.

*__Note:__ This README includes a high level overview of the tasks completed as part of this project, for full detail of all four tasks refer to the 'Project_2020 Fundamentals of Data Analysis.ipynb' jupyter notebook available within this repository.*