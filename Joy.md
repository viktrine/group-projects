# After Moringa Project
Hello and hopping you are doing good. No relaxing after Moringa. Allow me challenge you a bit with something small. 

## Problem statement
Just imagine you have a list of plan on what you want to study over time, say in 5 years to come. For example want to learn HTML, CSS, JS, React JS, Node JS, K8S, Jenkins pipeline. 
Unfortunately you keep planning but you forget because you have nowhere to keep your plans. 

## Solution
From the skillls we have learnt from Moringa, I want you to come up with the following system. 

Create a system that will do the following:
- As a user I should be able t login into the system.
- As user I should authenticate myself during login and be authorized as a user
- As a user I should be taken to a landing page that shows the following
    * Number of Current plans in progress
    * Number of plans in hold
    * Number of plans completed

- As a user I should be able to add new plans
- As a user I should be able to pregress or complete a plan
- As a user I should be able to edit, view, delete a plan
- As a user I can share my plans with my accountability partner

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
    * Plan - plan name, description, expected start date, expected end date,  actual start date, actual end date, status(started, hold, in progress, completed)


## Time
Can we complete this in 2 months? 
Shall be available every Friday for progress update. Feel free to share and ask idea any time

## Finally 
***happy coding***