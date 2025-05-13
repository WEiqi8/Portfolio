# 💸 Terminal Expense Tracker

A beautiful terminal-based expense tracking application with rich visual formatting and graphical visualization capabilities.

## Overview

Terminal Expense Tracker is a Python command-line application that helps you keep track of your expenses with a clean, colorful interface. The application uses the rich library for beautiful terminal formatting and matplotlib for expense visualization.

## Features

- **User-Friendly Interface**: Colorful and intuitive terminal UI using rich
- **Complete Expense Management**:
  - Add new expenses with names and amounts
  - View all expenses in a formatted table
  - Edit existing expenses
  - Delete unwanted expenses
- **Data Visualization**: Display expenses in a graphical bar chart
- **Interactive Prompts**: Enhanced user experience with interactive prompts and confirmations

## Screenshot

```
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)

```

## Requirements

- Python 3.6+
- Required packages:
  - rich
  - matplotlib

## Installation

1. Ensure you have Python 3.6+ installed on your system
2. Install the required packages:

```bash
pip install rich matplotlib
```

3. Download the `expense_tracker.py` file
4. Run the application:

```bash
python expense_tracker.py
```

## Usage Guide

### Adding an Expense

1. Select option `1` from the main menu
2. Enter the expense name when prompted
3. Enter the expense amount when prompted
4. The expense will be added to your list

### Viewing Expenses

1. Select option `2` from the main menu
2. A formatted table will display all your expenses

### Editing an Expense

1. Select option `3` from the main menu
2. View the list of expenses and note the number of the expense you want to edit
3. Enter the expense number when prompted
4. Enter the new name and amount (or press Enter to keep the current values)

### Deleting an Expense

1. Select option `4` from the main menu
2. View the list of expenses and note the number of the expense you want to delete
3. Enter the expense number when prompted
4. Confirm the deletion when prompted

### Visualizing Expenses

1. Select option `5` from the main menu
2. A bar chart will be displayed showing all your expenses
3. The chart window must be closed before returning to the application

### Exiting the Application

Select option `6` from the main menu to exit the application

## Technical Details

### Dependencies

- **rich**: Used for terminal UI formatting, tables, panels, and interactive prompts
- **matplotlib**: Used for generating expense bar charts
- **time**: Used for simulating loading effects

### Data Structure

Expenses are stored in a simple list of dictionaries with the following structure:

```python
{
    "name": "Expense Name",
    "amount": 100.00
}
```

### Code Structure

- `show_welcome()`: Displays the welcome message
- `show_menu()`: Displays the main menu options
- `add_expense()`: Handles adding new expenses
- `view_expenses()`: Displays all expenses in a table
- `edit_expense()`: Handles editing existing expenses
- `delete_expense()`: Handles deleting expenses with confirmation
- `show_graph()`: Generates and displays a bar chart of expenses
- `main()`: Main application loop

## Limitations

- Data is not persisted between sessions (stored in memory only)
- No categorization of expenses
- No date tracking for expenses
- No export/import functionality

## Future Enhancements

- Add data persistence using CSV or SQLite
- Add expense categories
- Add date tracking for expenses
- Add expense statistics and summaries
- Add import/export functionality
- Add budget tracking and alerts

## License

This project is available under the MIT License.

---

Created with ❤️ using Python and rich