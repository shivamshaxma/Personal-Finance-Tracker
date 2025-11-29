# Personal-Finance-Tracker

# 1. Project Overview
This project is a command-line finance tracker that:
Tracks income and expenses
Generates summaries by category or month
Saves all data to a CSV file (finance_data.csv)
# 2. Prerequisites
Make sure you have the following installed:
# Software
Python 3.8+
Pandas library
Install dependencies:
pip install pandas
# 3. Project Structure
Create a folder for your project:
personal-finance-tracker/
│
├── finance_tracker.py      # Your main script
└── finance_data.csv        # (auto-created when you add entries)

Paste your full code into finance_tracker.py.
# 4. How the Code Works
Component	Description
FinanceTracker Class	Handles all logic: data loading, adding entries, summaries, and export.
init	Loads finance_data.csv or creates an empty DataFrame.
add_entry()	Adds income or expense entries with validation.
view_balance()	Shows total income, expenses, and net balance.
category_summary()	Shows spending breakdown by category.
monthly_summary()	Summarizes income, expenses, and balance per month.
export_to_csv()	Saves data to finance_data.csv.
run()	Provides a command-line menu loop.
# 5. How to Run the App
In your terminal or command prompt, navigate to your project folder:
cd path/to/personal-finance-tracker
python finance_tracker.py

You’ll see a menu like this:
==== Personal Finance Tracker ====
1.	Add Income
2.	Add Expense
3.	View Balance
4.	Category Summary
5.	Monthly Summary
6.	Export to CSV
7.	Exit
# 6. Example Usage
➕ Add Income
Choose an option: 1
Enter income category: Salary
Enter description: October paycheck
Enter amount: 50000
Enter date (YYYY-MM-DD) or leave blank for today:
Income added successfully!
➖ Add Expense
Choose an option: 2
Enter expense category: Groceries
Enter description: Weekly shopping
Enter amount: 2500
Enter date (YYYY-MM-DD) or leave blank for today:
Expense added successfully!
# View Balance
Choose an option: 3
# ---- Current Financial Summary ----
Total Income:   ₹50,000.00
Total Expenses: ₹2,500.00
Current Balance: ₹47,500.00
# 7. Data Storage
Your data is automatically saved in finance_data.csv (same folder).
You can open it anytime in Excel or Google Sheets.
# Example CSV:
Date	Type	Category	Description	Amount
2025-10-01	Income	Salary	October paycheck	50000
2025-10-02	Expense	Groceries	Weekly shopping	2500
# 8. Optional Improvements
Here are some ideas to enhance the project:
✅ Add data visualization (using matplotlib or seaborn)
✅ Add input validation loops (instead of returning early)
✅ Convert to a Tkinter GUI or Streamlit web app
✅ Add JSON backup or cloud sync option
✅ Add search and filter features (by date or category)
🚀 9. Run & Test

