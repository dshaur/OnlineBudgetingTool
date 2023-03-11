# Online Budgeting Tool: Budget Page Prototype

## Mock Examples
![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/prototype/images/Budget-page-prototype.png "Budget Prototype Example 1")


![alt text](https://github.com/dshaur/OnlineBudgetingTool/blob/main/prototype/images/Budget-page-prototype-2.png "Budget Prototype Example 2")

The Budget page has two main sections: Budget and Expenditure.

The Budget section allows the user to enter the total amount of their budget for a specific period (chosen from a dropdown list) and click the "Set Budget" button to save the value. The total budget amount is displayed in the output section, along with a breakdown of expenses and balance.

The Expenditure section allows the user to enter a title and cost for an item they wish to purchase and click the "Check Amount" button to add the item to the expense list. The expense list is displayed in the List section of the page.

A pie chart of expenses is displayed in the Charts section, created using the AnyChart library.

JavaScript is used to handle user input and display the output on the page. If the user enters an invalid or empty input, an error message is displayed. The chart is drawn using the AnyChart library, and data is inputted in the JavaScript code.
