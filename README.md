# Online Budgeting Tool

## Overview

  This project aims to create an online budgeting tool that allows users to manage their expenses and income in a simple and efficient way. The application will be built using ASP.NET Core and will be hosted on Microsoft Azure. The project will have a simple user interface that allows users to create and manage their budgets and track their expenses and income. The application will use Microsoft Azure's cloud services to store and retrieve data, making it scalable and accessible from anywhere with an internet connection.

## User Stories

* As a user, I want to create a budget and set a limit for my monthly expenses.

* As a user, I want to add and manage my income and expenses.

* As a user, I want to see a graphical representation of my spending habits over time.

* As a user, I want to be able to categorize my expenses and view them by category.

* As a user, I want to be able to receive alerts when I am close to reaching my budget limit.

* As a user, I want to be able to view my expenses and income by date.

## Use Cases

* Creating a Budget: A user will be able to create a new budget by setting a limit for their monthly expenses.

* Adding Expenses and Income: A user will be able to add their expenses and income by providing details such as amount, date, and category.

* Viewing Budget Report: A user will be able to view a graphical representation of their spending habits over time.

* Categorizing Expenses: A user will be able to categorize their expenses into categories such as food, entertainment, transportation, etc.

* Budget Alerts: A user will receive alerts when they are close to reaching their budget limit.

* Viewing Transactions: A user will be able to view their expenses and income by date.

## Architecture Diagram

![alt text](https://github.com/dshaur/markdown-here/blob/main/Online_Budgeting_Tool_Architecture_Diagram.png "Architecture Diagram 1")

The application has been decomposed into multiple components:

* Presentation Layer: This component will be responsible for rendering the user interface and receiving user input.

* Data Access API: This component will handle the communication between the application and the database.

* Database: The database will store the users' budgets, expenses, and income.

* Admin Application: This component will provide an interface for the administrators to manage the application and its data.

The different components will be linked by APIs and will communicate with each other to provide the desired functionality. The architecture is simple, scalable, and can be easily maintained and extended in the future.

## Wireframe Sketches

### Homepage
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Wireframe1_Homepage.png "Wireframe 1 Homepage")

* This page serves as the main landing page for the web budgeting tool.
* It displays a summary of the user's current financial status, including their total income, expenses, and savings.
* The page also includes links to other areas of the application, such as the transactions page, budget page, and reports page.
