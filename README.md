# Real-Estate--Multiple-Linear-Regression
This project's objective is to construct a multiple linear regression model for a housing dataset, enabling the prediction of house prices using various potential predictor variables. 

The process begins by reading and visualizing the data, followed by data preparation for linear modeling, addressing challenges such as categorical variable handling, dummy variable introduction, and scaling techniques. The model will be systematically developed, employing a bottom-up approach starting with a single variable and progressively incorporating more. Once all variables are included, the project covers manual feature elimination, residual analysis, and prediction methods. 

**Problem Statement:**

Considering a real estate firm possesses data on property prices in Delhi. The goal is to enhance the selling prices of these properties by optimizing crucial factors like area, bedrooms, parking, and more. In this study, our primary aim is to delve into the pivotal factors influencing real estate sales. We aim to address the question of whether specific elements such as apartment size, the number of rooms and bathrooms, and other relevant factors impact sales.

**Approach:**

1. Identify the variables influencing house prices, including aspects like area, room count, bathrooms, by doing  correlation analysis and other visualization methods
2. Develop a quantitative linear model that correlates house prices with these variables.
3. Evaluate the model's accuracy, gauging how effectively these variables predict house prices.

**Findings:**

The equation for our best-fitted line is as follows:
**Price = 0.236 × Area + 0.202 × Bathrooms + 0.11 × Stories + 0.05 × Mainroad + 0.04 × Guestroom + 0.0876 × Hotwaterheating + 0.0682 × Airconditioning + 0.0629 × Parking + 0.0637 × Prefarea - 0.0337 × Unfurnished**

The adjusted r square is 0.667 with the VIF values being less than 5 as followed in the norm. This means that the variables that are currently selected are independent of each other and also able to describe the relationship between the target varoable Price to its dependent variables to some good extend. This means, we have a reasonably good model, but there's some room for improvement in the r square.

We have a couple of options:
1. Incorporate new features
2. Explore the possibility of building a non-linear model.
