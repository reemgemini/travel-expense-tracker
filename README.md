# travel-expense-tracker
An interactive Python project for tracking travel expenses and checking spending by city and category.

## Features

* Add cities and prevent duplicate city entries.
* Record positive expense amounts, including decimals.
* Categorize expenses as Food, Transportation, Accommodation, or Activities.
* Retry invalid categories or cities without re-entering the amount.
* Calculate total spending overall, by category, or by city.
* Find the highest and lowest individual expenses.
* Display logged expenses in a pandas table.
* Clear all cities and expenses.
* Return to the main menu during expense entry.

## Tools

* Python
* Jupyter Notebook
* pandas

## How to Run

1. Download or clone this repository.
2. Install the required packages:
3. pip install pandas notebook
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `travel_expense_tracker.ipynb` and run the project cell.
6. Add a city using option `1`, then record expenses using option `2`.

Enter `0` at the main menu to stop the program. During entry, use the indicated `0` option to return to the menu.

## Data Structure

Expenses are stored in a nested dictionary:

```python
expenses = {
    "Food": {
        "Tokyo": [100.0, 50.0]
    },
    "Transportation": {
        "Tokyo": [20.0]
    }
}
```

Each category contains city names, and each city holds a list of expense amounts.

## What I Practiced

- Lists and nested dictionaries
- Functions and variable scope
- Loops and conditional statements
- Input validation and exception handling
- `break`, `continue`, and `return`
- Calculations across nested data
- Basic DataFrame display with pandas

## Future Improvements

- Save and reload expenses from a file.
- Add expense dates and descriptions.
- Calculate average spending.
- Edit or delete individual expenses.

## Author

Reem Elshorbagy
