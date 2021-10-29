# Life-Expectancy
Linear Regression in Julia

Linear Regression is a fundamental machine learning algorithm used to predict a numeric dependent variable based on one or more independent variables. The dependent variable (Y) should be continuous.

Linear Regression is one of the most basic machine learning algorithms that is used to predict a dependent variable based on one or more independent variables. The dependent variable (Y) should be continuous. Linear regression finds the mathematical equation that best describes the Y variable as a function of the X variables (features). Once the equation is formed, it can be used to predict the value of Y when only the X is known.

This mathematical equation can be generalized as follows:

𝑌=𝛽1+𝛽2𝑋+𝜖

where 𝛽1 is the intercept and 𝛽2 is the slope. If there is only one X variable, it is called ‘Simple Linear Regression’. If more than one predictor (X) is involved, it is called ‘Multiple Linear Regression’.

# PROJECT TITLE: LIFE EXPECTANCY
# AIM: 1. Import Packages and setup environment in Julia

![image](https://user-images.githubusercontent.com/62717424/139497329-569cbb16-f121-43da-928a-d2c498f14996.png)

# 2. Load Data

![image](https://user-images.githubusercontent.com/62717424/139497430-7850b2da-4775-47a2-9915-a88f38958a7d.png)

![image](https://user-images.githubusercontent.com/62717424/139497504-5bc18d81-e516-4cdf-a358-eeedfc084fde.png)

# 3. Summary of the dataframe

![image](https://user-images.githubusercontent.com/62717424/139497603-916d19dd-b0e8-4b68-8b0e-f9e1ac3a8d8a.png)

![image](https://user-images.githubusercontent.com/62717424/139497808-d7e68283-bf6c-4725-aee7-e775746c0dee.png)

![image](https://user-images.githubusercontent.com/62717424/139497854-194d3407-32e8-41da-bc75-e79c4b0e499d.png)

![image](https://user-images.githubusercontent.com/62717424/139497923-46275985-b1bf-441d-99df-deb79c4f7430.png)

# 4. Outlier Analysis using Box Plot
Outlier is a data point or set of data points that differ significantly from other observations in the complete dataset.

Linear Regression works well when there aren’t any outliers present in the data. Let’s check out the outliers in y variable i.e. Life Expectancy

![image](https://user-images.githubusercontent.com/62717424/139498018-a8744c7b-b928-45e2-adfd-99b5ff04ceb5.png)

![image](https://user-images.githubusercontent.com/62717424/139498064-139047dc-747e-4f61-8fde-8cd25bed09ba.png)

![image](https://user-images.githubusercontent.com/62717424/139498249-ff9f26e9-54b4-43d5-beaf-6a15632aec3b.png)

Outlier is a data point or set of data points that differ significantly from other observations in the complete dataset.

Linear Regression works well when there aren’t any outliers present in the data. Let’s check out the outliers in y variable i.e. Life Expectancy

# 5. Distribution Analysis using Density Plot
Linear Regression works well when the y variable is normally distributed or close to normal distribution. Let’s check out the distribution of y variable i.e. Life Expectancy
![image](https://user-images.githubusercontent.com/62717424/139498382-68123bd3-7d00-4c47-ad13-18684a2ccaaa.png)

![image](https://user-images.githubusercontent.com/62717424/139498447-77dfcc76-4aa1-4a2f-89db-788aea4703d7.png)

The distribution does have a couple of mini peaks, which is indicative of a mixture of distributions. However, the overall distribution does have a bell curve.

# 6. Correlation Analysis using Scatter Plot
Linear Regression works well when the y variable is linearly correlated to the x variable.

![image](https://user-images.githubusercontent.com/62717424/139498531-3034725c-193b-4cd0-94f4-88bb0103ed27.png)

![image](https://user-images.githubusercontent.com/62717424/139498582-757183ce-33b8-4109-9b29-2dfd250bbbaf.png)

The two features look linearly correlated. There are still a few chunk of points which are having different behaviour.

