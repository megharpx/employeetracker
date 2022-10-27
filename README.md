# MySQL-Employee-Tracker

## Description

A SQL database that tracks employees, their roles, and their respective department.

## Table of Contents
- [Code Utilized](#code-utilized:)
- [User Story](#user-story)
- [Installation](#installation)
- [Usage](#usage)
- [What to Expect](#what-to-expect:)
- [License](#license:)


## Code Utilized

This application was made using JavaScript, NPM, and MySQL.

## User Story
```
As a business owner
I want to be able to view and manage the departments, roles, and employees in my company
So that I can organize and plan my business
```

## Installation
1. Clone from GitHub
2. Open project directory, then npm install to install all required dependencies 

## Usage
1. install npm init -y to create a new .json file
2. npm i
3. npm i inquirer
4. npm i mysql
5. npm i console.table
6. make sure to run .sql file in mySQL workbench before running server.js so that tables are able to render correctly
7. run node server.js
8. make sure server.js is connected to SQL before continuing
9. run through prompts as required 

## What to Expect

When the user runs the application in Terminal:
- The user is presented with the title of the application.
- The user is then presented with a list of options for what they would like to do first.
- Once the user selects the desired action, they are presented with a response based on their selection.
- Selecting "view employees" will present the user with a table of all employees currently in the database.
- Selecting "view roles" will present the user with a table of all roles currently in the database.
- Selecting "view departments" will present the user with a table of all orles currently in the database.
- Selecting "add employee" will present the user with prompts to add the employee accurately.
- Selecting "add role" will present the user with prompts to add a role to the database.
- Selecting "add department" will present the user with prompts to add a department to the database.
- Selecting "update employee" will present the user with a list of employees which they will chose from to update.

## License

This application is using MIT.
