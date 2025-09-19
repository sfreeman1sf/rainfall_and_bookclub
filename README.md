# Rainfall and Book Club Programs

This repository contains two Python programs for CSU Global coursework.  

- **Part 1:** Average Rainfall Program  
- **Part 2:** Book Club Points Program  

Both programs are written in Python 3.

---

## Part 1: Average Rainfall

### Pseudocode
Start
Ask user for number of years
Set total_rainfall = 0
Set total_months = 0

For each year in number of years:
For each month in 12:
Ask user for inches of rainfall
Add rainfall to total_rainfall
Increase total_months by 1

Calculate average = total_rainfall / total_months
Display total_months, total_rainfall, average
End

### Python File
`rainfall.py`

---

## Part 2: Book Club Points

### Pseudocode
Start
Ask user for number of books purchased
If books = 0 → points = 0
If books = 2 → points = 5
If books = 4 → points = 15
If books = 6 → points = 30
If books >= 8 → points = 60
Display points
End

### Python File
`bookclub.py`

---

## How to Run

Make sure Python 3 is installed. Run in terminal:

```bash
python rainfall.py
python bookclub.py
Example Outputs
Rainfall Program

Enter the number of years: 1

Year 1
Enter the inches of rainfall for month 1: 2
Enter the inches of rainfall for month 2: 3
...
--- Rainfall Report ---
Total months: 12
Total rainfall (inches): 30.00
Average rainfall per month: 2.50
Book Club Program

Enter the number of books purchased this month: 4

--- Book Club Points ---
Books purchased: 4
Points awarded: 15

rainfall.py
bookclub.py

