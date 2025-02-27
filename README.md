# Telegram Finance Tracker and Budget Visualization System

The Monthly Budget Tracker is a user-friendly financial management through Telegram Bot created to help users keep track of their expenses, compare spending with their budget, and providing visualizations and insights into their finance through Dash web interface.

This app is integrated with a Telegram bot, allowing users to easily enter data and receive summaries in real-time.

This Dash-based website provides a clear, interactive dashboard where users can see and therefore control their monthly spending, compare it to their set budget, and analyze the balance between income and expenses or monthly summaries or category-specific analysis.
## Features

**Telegram Bot**:

-   Enter income and expense or budget data and many commands.

-   Check your monthly budget summary using commands.

-   Access the Dash web app link for visualizations.

**Dash Visualization**:

-   Overall Spending vs. Budget:

    -   A pie chart showing total spending versus the remaining budget.

    -   Category-Specific Analysis: Bar charts showing category-wise
        budget versus spending.

    -   Remaining Budget Analysis:

        -   Bar chart with remaining budget for each category,
            displaying values on the bars.

**Database Integration**:

-   Stores budgets, expenses, and income in an SQLite database
    (expenses.db).

**Comprehensive Summaries**:

-   Provides text-based analysis of overspending, percentages spent, and
    remaining budgets.

**Visualizations**:

-   Pie charts for total spending and category-specific spending. -

-   Bar charts for income vs spending and remaining budget by category.

**Dash Tables**:

-   Displays detailed data for overall and category-specific budgets and
    spending.

## Technology Stack

-   **Backend**: SQLite database for storing expense data.
-   **Frontend**: Dash for interactive UI and Plotly for data
    visualizations.
-   **Data Processing**: Custom Python modules (`Expense`, `Income`,
    `Budget`, `Data_Processing`) for retrieving and calculating budget
    and spending metrics.

## Prerequisites

-   Python 3.8 or later
-   SQLite installed (if not already available)
-   Read more in requirements.txt
## Screenshots Preview:

![Screenshot 2025-01-19 230304](https://github.com/user-attachments/assets/16d3a8af-90c4-4916-b8da-711274c76068)
![Screenshot 2025-01-17 221039](https://github.com/user-attachments/assets/25bc3983-88f2-4b62-a741-989329d95716)
![Screenshot 2025-01-17 221024](https://github.com/user-attachments/assets/35e4f2b1-c84e-442c-b093-fe8dad643f10)


## Installation

1.  Clone the repository: \`\`\`bash git clone
    <https://github.com/felixxvo7/Budget-Tracking-Dashboard.git>

Open the dashboard report application in your browser:

Navigate to <http://127.0.0.1:8057> in your web browser.

## Project Structure
```         
Telegram-Finance-Tracker-and-Budget-Visualization-System/
│
├── BotHandler.py
├── Clean_Data.py
├── Data_Processing.py
├── Budget.py     # Budget Class and Database Management
├── Expense.py    # Expense Class and Database Management
├── Income.py     # Income Class and Database Management
├── Visualization.py
```
## Installation

Clone the repository: \`\`\`bash git clone
    <https://github.com/felixxvo7/Budget-Tracking-Dashboard.git>

Open the dashboard report application in your browser:

Navigate to <http://127.0.0.1:8057> in your web browser.

## Running the Application

1.  Start the Telegram Bot Run the bot to interact with it on Telegram:
    python BotHandler.py
2. Go to Telegram Bot through Telegram share link: https://t.me/trackingBudgetBot

3. Command Description:

/start Welcome message and bot introduction.

/about - Tell you more about the bot

/spend Log your spending data.

/earn Log your income data.

/setbud Set your monthly budget by categories.

/last_expense - To view last 5 transactions of Expense

/last_income - To view last 5 transactions of Income

/budget Shows the total budget and category-specific budgets.

/delete [id] Deletes an income entry by its ID.

/report Get a summary of your current month's financial data.

/help Lists all available commands and their descriptions.

/view - show last 5 transactions in either Expense data or Income data

/check_budget show me the remaining budget for all category current
month

/summarize Provides the Dash visualization link
(<http://127.0.0.1:8057/>).

4.  Start the Dash Visualization Run the Dash app to view
    visualizations: python Visualization/app.py
    -   Access the Dash app at <http://127.0.0.1:8057/>.


### Author

Felix Vo

------------------------------------------------------------------------

Let me know if you need further assistance!
