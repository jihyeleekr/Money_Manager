# Money_Manager

Money Manager is a command-line personal finance tracking tool that helps users manage income, expenses, and savings. It allows users to add and edit transactions, view summaries of income and expenses, visualize spending by category, and save financial data to a CSV file for future reference.

## Features

- **Add Income and Expenses**: Record your income and categorize expenses (e.g., food, subscriptions, education).
- **Edit Transactions**: Modify transaction details such as amount, category, and date.
- **View Summary**: Display total income, expenses, and net savings.
- **Expense Chart**: Visualize spending distribution by category using a pie chart.
- **Save and Load Data**: Save transactions to a CSV file and load them automatically on startup.

## Getting Started

### Prerequisites

- **Python 3.x**
- **matplotlib** (for expense chart visualization)

Install `matplotlib` using pip if not already installed:
```
pip install matplotlib
```

### Running the Program

1. Clone this repository:
   ```
   git clone https://github.com/jihyeleekr/Money_Manager
   cd MoneyManager
   ```
2. Run the Python script:
   ```
   python MoneyManager.py
   ```

### Usage

The program provides a menu with options:
1. **Add Income**: Enter income amount and date.
2. **Add Expense**: Enter expense amount, category, and date.
3. **Edit Transaction**: Choose and edit a previous transaction.
4. **View Summary**: Display total income, expenses, and net savings.
5. **View Expense Chart**: Show a pie chart of expenses by category.
6. **Save Data**: Save transactions to `finance_data.csv`.
7. **Exit**: Save and exit the program.

### Example

After starting the program, you can select an option by entering the corresponding number:
```plaintext
Personal Finance Tracker
1. Add Income
2. Add Expense
3. Edit Transaction
4. View Summary
5. View Expense Chart
6. Save Data
7. Exit
Choose an option: 1
```

## Data Storage

Transactions are stored in `finance_data.csv` with the following columns:
- **Transaction Type**: "Income" or "Expense"
- **Amount**: Transaction amount
- **Category**: (For expenses only)
- **Date**: Transaction date in MM/DD/YYYY format

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and commit them.
4. Open a pull request.
```
