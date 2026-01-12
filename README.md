# Personal Expense Tracker

This is a basic personal expense tracker implmeneted in Python. The ExpenseTracker class is designed to help users manage their personal finances by tracking expenses and monitoring spending against a set budget. It allows users to record their expenditures, categorize them, and see how much they are spending over time.

· The ExpenseTracker class is designed to manage personal expenses using a pandas DataFrame to store details like ID, Date, Description, Amount, and Category.

· The tracker includes functionality for loading and saving data from/to CSV and text files for expenses and budget, respectively.

· Core features include adding, viewing, tracking against a budget, deleting expenses, and viewing monthly spending summaries.

· A menu-driven interface is implemented for user interaction, including a main menu and a dedicated budget menu.

The following features were implemented.

· Saving and Loading Budget: The code includes functionality to save and load the budget from a separate text file (budget.txt).

· Monthly Spend View: The view_monthly_spend method calculates and displays spending per month, indicating if each month is over or under budget. This provides a more detailed breakdown than just the total spending vs. budget.

· Delete Expense Functionality: The delete_expense method allows the user to remove a previously entered expense.

· Budget Menu: The code includes a dedicated budget_menu to organize budget-related actions, providing a clearer user interface.

· Icons for Budget Status: The view_monthly_spend method uses icons (, , ) to visually indicate the budget status for each month.

· Welcome Message: A welcome message is displayed when the application starts.

· File Not Found Handling: The load_csv and load_txt methods include specific messages when the expense or budget files are not found.

· Alternate Exit: An option to save and exit is available on the main menu.
