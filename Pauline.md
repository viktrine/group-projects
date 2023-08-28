# After Moringa Project
Hello and hopping you are doing good. No relaxing after Moringa. Allow me challenge you a bit with something small. 

## Problem statement
We know we have customers who visit our shop for various services. There are some service that might not really need customer to physically come to the office. For example checking progress for phone that they brought for repair and any other service you might think of. 


## Solution
Let's create a self service portal to allow customer periodically check progress for a service they requested. Even the customers in the shop can login and keep checking on the progress. They don't have to keep waving/winking at you to get response on how far their request is gone. 


From the skillls we have learnt from Moringa, I want you to come up with the following system. 

Create a system that will do the following:
- As a user I should be able t0 login into the system.
- login can be as a customer / admin
- As user I should authenticate myself during login and be authorized as a user or admin
- As a customer I should be taken to a landing page that shows the following
    * My requests - active/Completed/dropped
    * Service person
    * progress of my requests

- As a admin I should be taken to a landing page that shows the following
    * Requests in the shop currently
    * Requests I have closed
    * I can take a request and work on
    
    * As an admin I can progress requests
    * ensure vrious CRUD operations on the system


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
    * User - to keep info on who can login - will have id, username, phone, password...
    * Customer - name, phone, time in, timeout, issue reported...
    * Any other info that you might need


## Time
Can we complete this in 2 months? 
Shall be available every Friday for progress update. Feel free to share and ask idea any time

## Finally 
***happy coding***