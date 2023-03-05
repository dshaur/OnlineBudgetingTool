# Online Budgeting Tool

-----------
 ## Table of Contents
 1. [Overview](https://github.com/dshaur/OnlineBudgetingTool#overview)

 2. [User Stories](https://github.com/dshaur/OnlineBudgetingTool#user-stories)

 3. [Use Cases](https://github.com/dshaur/OnlineBudgetingTool#use-cases)

 4. [Architecture Diagram](https://github.com/dshaur/OnlineBudgetingTool#architecture-diagram)

 5. [Drafts](https://github.com/dshaur/OnlineBudgetingTool#drafts)
 * [Home Page](https://github.com/dshaur/OnlineBudgetingTool#home-page)
 * [Transactions Page](https://github.com/dshaur/OnlineBudgetingTool#transactions-page)
 * [Budget Page](https://github.com/dshaur/OnlineBudgetingTool#budget-page)
 * [Reports Page](https://github.com/dshaur/OnlineBudgetingTool#reports-page)
 * [Settings Page](https://github.com/dshaur/OnlineBudgetingTool#settings-page)

 6. [Use Case Diagram (UML)](https://github.com/dshaur/OnlineBudgetingTool#use-case-diagram-uml)
 
 7. [Requirements Table](https://github.com/dshaur/OnlineBudgetingTool#requirements-table)

 8. [Entity Relationship Diagram (ERD)](https://github.com/dshaur/OnlineBudgetingTool#entity-relationship-diagram-erd)

 9. [Updated Use Case Diagram (UML)](https://github.com/dshaur/OnlineBudgetingTool#updated-use-case-diagram-uml)

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

![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Online_Budgeting_Tool_Architecture_Diagram.png "Architecture Diagram 1")

The application has been decomposed into multiple components:

* Presentation Layer: This component will be responsible for rendering the user interface and receiving user input.

* Data Access API: This component will handle the communication between the application and the database.

* Database: The database will store the users' budgets, expenses, and income.

* Admin Application: This component will provide an interface for the administrators to manage the application and its data.

The different components will be linked by APIs and will communicate with each other to provide the desired functionality. The architecture is simple, scalable, and can be easily maintained and extended in the future.

## Drafts

### Home Page
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Wireframe1_Homepage.png "Wireframe 1 Home Page")

* This page serves as the main landing page for the web budgeting tool.

* It displays a summary of the user's current financial status, including their total income, expenses, and savings.

* The page also includes links to other areas of the application, such as the transactions page, budget page, and reports page.

### Transactions Page
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Wireframe2_Transactions.png "Wireframe 2 Transactions Page")

* This page allows users to view a list of all their financial transactions, including income and expenses.

* Users can filter transactions by category, date, or search for specific transactions.

* Users can also add new transactions by clicking a button that opens a modal form for entering transaction details.

### Budget Page
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Wireframe3_Budget.png "Wireframe 3 Budget page")

* This page allows users to view and manage their budget.

* It displays a pie chart that shows how their income is divided among different categories (e.g. housing, food, transportation, etc.).

* Users can adjust the budget for each category by sliding a bar or entering a specific amount.

* The page also shows the user's current progress against their budget for each category.

### Reports Page
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Wireframe4_Reports.png "Wireframe 4 Reports Page")

* This page allows users to view financial reports for their transactions and budget.

* Users can choose from several report types, such as monthly or annual reports.

* The reports are displayed in the form of line or bar graphs and can be downloaded as PDF or CSV files.

### Settings Page
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Wireframe5_Settings.png "Wireframe 5 Settings Page")

* A form to update personal information, with fields for "Full Name", "Email", and "Password"

* A "Save Changes" button to submit the updated information

* A "Back" button to return to the Budget Overview page

This is just a rough approximation of what the wireframe sketches could look like. The actual sketches can be adjusted and refined based on feedback and design considerations.

## Use Case Diagram (UML)
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/Use_Case_Diagram_v1.png "Use Case Diagram version 1")

In this diagram, the Web User actor is able to perform the actions of creating an account, logging in, viewing transactions, adding transactions, updating transactions, deleting transactions, viewing budget, and updating budget. 

The System actor is responsible for storing user data, validating the login, displaying transactions, storing transactions, updating transactions, deleting transactions, displaying budget, and updating budget. The arrows between the User and System actors indicate the flow of interactions between them.

## Requirements Table

| ID	| Requirement |
| --- | ----------- |
| 1	  | The system shall allow users to create a budget by setting a limit for their monthly expenses. |
| 2	| The system shall allow users to add and manage their income and expenses by providing details such as amount, date, and category. |
| 3	| The system shall provide a graphical representation of a user's spending habits over time. |
| 4	| The system shall allow users to categorize their expenses into categories such as food, entertainment, transportation, etc. |
| 5	| The system shall send alerts to users when they are close to reaching their budget limit. |
| 6	| The system shall allow users to view their expenses and income by date. |

Each of these requirements can be objectively tested by verifying that the specified functionality exists and works as expected within the system. 

For example, the test for requirement 1 could involve attempting to create a new budget and verifying that the user is able to set a limit for their monthly expenses. Similarly, the test for requirement 5 could involve setting up an alert for a specific budget and verifying that the user receives a notification when they approach the limit.

## Entity Relationship Diagram (ERD)
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/ERD.png "Entity Relationship Diagram version 1")

The ERD consists of four entities: User, Budget, Category, and Transaction.

The User entity represents a user account, with attributes for UserId (primary key), Username, Password, FullName, and Email.

The Budget entity represents a budget created by a user, with attributes for BudgetId (primary key), UserId (foreign key), and Limit. Each user can have multiple budgets, so there is a one-to-many relationship between User and Budget.

The Category entity represents a category that an expense can be classified into, with attributes for CategoryId (primary key) and Name. Each category can have multiple transactions associated with it, so there is a one-to-many relationship between Category and Transaction.

The Transaction entity represents a financial transaction, with attributes for TransactionId (primary key), UserId (foreign key), Amount, Date, and CategoryId (foreign key). Each transaction is associated with one category and one user, and there can be multiple transactions associated with a user, so there is a one-to-many relationship between User and Transaction.

## Updated Use Case Diagram (UML)
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/images/UMLv2.png "Use Case Diagram version 2") 

In this updated class diagram, we have four classes: User, System, Transactions and Budget. The User class represents the user of the online budgeting tool, and the System class represents the system that the user interacts with.

The User class has attributes id, username, and password, which are all private (- visibility). It also has several methods that correspond to the actions the user can perform in the online budgeting tool, including createUser(), viewTransactions(), addTransaction(), updateTransaction(), deleteTransaction(), viewBudget(), and updateBudget(). These methods have different return types, parameters, and visibility based on their specific functionality.

The System class has three private attributes, users, transactions, and budgets, which are all represented as lists of User, Transaction, and Budget objects, respectively. It also has several methods that correspond to the system's functionality, including validateLogin(), displayTransactions(), storeTransaction(), updateTransaction(), deleteTransaction(), displayBudget(), and updateBudget(). These methods have different return types, parameters, and visibility based on their specific functionality.
