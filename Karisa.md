# Personal Project
This is a documentation that will be used for a personal project to test end to end understanding of the just conclued training at Moringa. 


## Problem Statement
We earn money from different sources, different times, for different purposes. However, we cannot track the usage for our money. 
If I ask you to account for the money you earned last month, can you account to a granular level? 

## Solution
Create a system that will achieve the following:
- Create category of expenses, for example Food, Cloths, Rent, Medication, Family, Recreation ...
- Create category of revenue sources, for example job salary, side hustle business, family sources, debt repayment from friends, farming...
- The system should be able to determine each of the above categories if it should debit or credit account. 
- User should be able to create above categories
- User should be able to create new expense and attache to above category. For example next weekend when you go out to treat yourself you should record the expenses as recreation
- user should be able to create a new earning and attach to revenue categories above - for example ukilipwa 25th you should go to your system and add salary revenue.
- User can edit, view, delete and add categories
- User can edit, view, delete and add expenses
- User can edit, view, delete and add revenues
- There should be a dashboard to show our real time account balance
- User should be able to go back on history to see all transactions on the system - both expenses and revenues
- Login is key, add user authentication to login to the system. 
- user types can also be implemented for exampl admin and normal user. Why this? Imagine in future you want to train your little babies to know to keep track of expenses and revenues. Can they log in and be the ones updating the system after that Supermarket visit? But they should not see your balance, or watakusumbua knowing mum has money, hehe.


## Technical Specifications
The system will have the following technical items
- React JS: Will be used to create front end 
- Node JS / Express: The backend will be created using Express running on Node JS
- MongoDB: Store all details on MongoDB database. 
- Have a look at Boostrap to make UI look good. 
- Separate frontend and backend
- They should have different repositories
- Create docker containers / images for frontend and backend
- Push to registry after creating the images - check how you can achieve this using Jenkins. We can see how to buy a cheap droplet from digital ocean (Sister to kina GCP/AWS) and install jenkins there. 
- we shall see how to run minikube using image pushed to registry.

## Strategy for development
I am suggesting you use the following:
 

- Put down all the possible kind of data you need. For example:
    * Category - will need id, category_name, operation_type(credit or debit). This will infor the kind of schema you will create for category
    * Transaction - will need id, transaction_name, transaction_description, category, amount, date
    * User - to keep info on who can login - will have id, username, phone, password...

- Once you have determined the data you might need, create a postman collection for this. Incase of any chalenge reach out. 

- Once postman icollection is completed, implement the backend with express. Test all backend endpoints from postman to ensure you getting the required response. I prefer all respnses to be on JSON format. 
- Once do go to implement the frontend using React. 


## Time
Can we complete this in 2 months? 
Shall be available every Friday for progress update. Feel free to share and ask idea any time

## Finally 
***happy coding***