Linear regression is used in various fields such as real estate, telecom, e-commerce, etc. to build predictive models. Let's look at one such example from the real estate industry. Here, you will predict the price of a house on the basis of some predictor variables, such as floor area, number of bedrooms, parking space, etc.

 

Problem Statement:

Consider that a real estate company has the data of real estate prices in Delhi. The company wants to optimise the selling price of the properties, based on important factors such as area, bedrooms, parking, etc.

 

Essentially, the company wants:

To identify the variables affecting house prices, e.g., area, number of rooms, bathrooms, etc.
To create a linear model that quantitatively relates house prices with variables, such as the number of rooms, area, number of bathrooms, etc.
To know the accuracy of the model, i.e. how well do these variables predict the house prices

Approach and Methodologies:

- Feature Selection: Applied Recursive Feature Elimination (RFE) to identify the most significant variables impacting house prices. This method helped in refining the model by keeping only the most influential factors.
- Multicollinearity Check: Employed Variance Inflation Factor (VIF) analysis to detect and address multicollinearity in the dataset, ensuring that our model’s predictors were independent and reliable.
- Model Development: Built a Multiple Linear Regression model to establish a quantitative relationship between house prices and selected variables. This model served as a tool for predicting prices and understanding the weightage of different features.
- Model Validation and Accuracy: Rigorously tested the model's performance on unseen data, ensuring its effectiveness and accuracy in real-world scenarios.
