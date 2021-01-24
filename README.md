# Laravel Code Challenge 1

## Philosophy

The goal of this challenge is to get insight on how you approach an everyday application in Laravel. 

Complete the challenge by writing code that you would write again any day and pick up with ease 5 years from now. Basically, write code you're proud of.

### How to Submit your work

Please submit your work by the deadline provided and please send us a github link for your work.

## Assessment

This assessment will be reviewed based on:
* Solving the task
* Cleanliness and readability of your code
* Organisation and structure
* Documentation

## The Task

The main focus of the task will be to create a set of APIs in laravel.

We would like you to develop some APIs as follows:
* Create the standard structure of the application
* Integrate Laravel Passport to secure your apis - make it use a client called "Bright Creations Challenge Client"
* Use database seeds to create first user with email admin@admin.com and password “password”
* Create new data model for Company & Employee:
  * Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website url
  * Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone
  * Use database migrations to create those schemas above
* Create a relationship between Companies and Employees - with a one to many relationship between Company and Employee (and create the reverse directional relationship)
* Update the Employee schema to have a field called Full Name which is generated from the first and last name fields
* Create APIs to CRUD company and employees
  * Ensure that the API for Employee also returns the auto generated Full Name of the employee
  * Store companies logos in storage/app/public folder and make them accessible from public
  * Use basic Laravel resource controllers with default methods – index, create, store etc.
  * Use Laravel’s validation function, using custom Request classes
  * Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
* Rewrite the above code using the Repository Pattern for the company and employee data access
* Write a README.md file in the root of the project directly - this should include directions to setup your project

