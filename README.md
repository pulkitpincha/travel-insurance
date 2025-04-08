# travel-insurance

Dataset: https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data

## Predicting Travel Insurance Purchases

This dataset contains past data on the factors that are involved in a customer’s likelihood of 
purchasing travel insurance from the given company during the year 2019.
The dataset provides us with valuable information of the decision making of customers in the 
case of purchasing travel insurance. Using this dataset, we can answer questions like:
• Does income play an important role in the purchase of travel insurance?
• Does the size of the family hinder or aid the willingness of a purchase?
• Is it more likely that they will purchase travel insurance if they have travelled abroad 
before?
• Does age play an important role with the insurance purchase?
By using the data from this dataset, we can find answers to these questions and gain a better 
insight of the consumer’s purchase patterns with regard to travel insurance. This can be used 
by travel insurance providers/companies.

## The Independent Variables are:

• Age- Age of the customer
• Employment Type- The sector in which customer is employed
• Graduate Or Not- Whether the customer is a College Graduate or Not
• Annual Income- The Yearly Income Of The Customer In Indian Rupees [Rounded To 
Nearest 50 Thousand Rupees]
• Family Members- Number of members in customer's family
• Chronic Disease- Whether the Customer suffers from any major disease or conditions 
like Diabetes/High BP or Asthma, etc.
• Frequent Flyer- Derived data based on customer's history of booking air tickets on at 
least 4 different instances in the last 2 years [2017-2019].
• Ever Travelled Abroad- Has the customer ever travelled to a foreign country [Not 
Necessarily Using the Company's Services]

**The dependent variable is the travel insurance.** The goal is to find out if we can predict if a 
customer is likely to purchase the travel insurance based from the independent variables.

## Research Question:

Which factors play an important role in the purchase of travel insurance? And can a model be 
built to provide estimates of the critical values of these factors?

## Procedure:

In this data analysis, the first step was to create dummy variables and then making a linear 
regression model to check which variables had a significant effect on the purchase of travel 
insurance. After this we could tell that the most important variables were Age, Income, 
Number of Family Members, Flight History, and Travel Abroad History.
Using these variables, a decision tree is built and measured using a Confusion Matrix. After 
this the data is split up into a train and test datasets. This is then used to make one more 
Linear Regression model as well as another Decision Tree which is measured again with a 
Confusion Matrix.

## Final Result:

In the end of the analysis we can see that Decision Tree is a more accurate method, with an 
accuracy of 83.14%; while the Linear Regression model only predicted 25.93% accurately.
The model also tells us which variables the firm needs to pay attention to if they would like to 
increase their number of clients for Travel Insurance.
