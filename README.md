# insurance-claimed-benefits

**The Aim** - We have information on 5000 fake customers that have an insurance plan. It includes information on the customer demographics, as well as if they have claimed insurance benefits or not. The goal of this project is to create a model designed to predict whether or not customers will likely claim insurance benefits or not.

The following tasks are achieved in this project:
- We will find customers who are similar to a given customer
- We will predict whether a new customer is likely to receive an insurance benefit
- We will predict the number of insurance benefits a new customer is likely to receive using a linear regression model
- We will protect clients' personal data without breaking the model from the previous task with data obfuscationso that the quality of machine learning models doesn't suffer

Strategies include:
- Data preprocessing
- Exploratory Data Analysis
- k-Nearest Neighbors Classification
- Regression from scratch
- Data Obfuscation

**The Data** - The data files below is where our input for the project comes from. The files contain different non-identifying information on people with insurance plans. The following characteristics are in the file:

The `insurance_us.csv` dataset:  
`gender`: Whether the customer was male or female  
`age`: The age of the customer  
`income`: The income of the customer  
`family_members`: The number of family members on the customer's plan  
`insurance_benefits`: Whether or not the customer has made a claim  