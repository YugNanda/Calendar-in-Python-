# Calendar-in-Python-
# 📅 Monthly Calendar Display in Python

This is a simple Python script that displays the calendar for a specific month and year using Python’s built-in `calendar` module. No external libraries needed — clean and beginner-friendly!

## ✨ Features
- ✅ Displays the monthly calendar with proper formatting.
- 🧠 Great for beginners learning Python.
- 📦 Uses Python’s built-in library (no installation required).

## 🧾 How It Works
The script sets the desired year and month, then uses the `calendar.month()` function to print the calendar for that period.

### 🧩 Code Snippet:
```python
import calendar

yy = 2025  # Year
mm = 2     # Month

# Display the calendar for the given month and year
print(calendar.month(yy, mm))
