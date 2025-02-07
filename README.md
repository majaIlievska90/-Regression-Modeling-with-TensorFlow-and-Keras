# -Regression-Modeling-with-TensorFlow-and-Keras

**Description** 

This project demonstrates my practice with TensorFlow and Keras by training regression models, both linear and nonlinear, using deep neural networks. I queried the World Nations database from the DataCamp platform using SQL to extract data on the population and the number of languages spoken in European countries.

The dataset was then used to train regression models with both single and multiple variables, highlighting key concepts such as feature selection and model evaluation. The project showcases the application of machine learning techniques to real-world data, providing insights into model performance and regression analysis.

**Libraries used**

` pandas, tensorflow, matplotlib, plotly, numpy, seaborn `

**Results**

I used **Mean Absolute Error (MAE)** as the loss function to evaluate the performance of each model. During training, the model calculates the difference between its predictions and the true training labels, minimizing the loss function accordingly. MAE measures the average magnitude of errors in a set of predictions, without considering their direction.

Once the models were trained, I used MAE on the test set to evaluate their performance and compare them. The following are the MAE values for each model on the test set:

**Population Model**: 1.35 <br>
**Linear Model**: 1.41    <br>
**DNN Population Model**: 1.46 <br>
From these results, we can conclude that the Linear Model with one variable produced the lowest MAE, meaning that there is a relatively simple linear relationship between the population size and the number of languages spoken in a country.

While the linear model performs well, there is potential for improvement by addressing issues such as overfitting and exploring additional features. One other metric that could be considered in future work is R-squared (R²), which quantifies the percentage of variance in the data explained by the model.

