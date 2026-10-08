PLP Python Week 6 - Safe Functions
Files
safe_tools.py - Contains three safe functions that handle division, number conversion, and dictionary lookups using try/except.
README.md - Describes the assignment and explains why an if check cannot catch invalid integer input.
An if check cannot catch "abc" on its own because the error happens when int("abc") is executed. Python raises a ValueError during the conversion, so try/except is needed to catch that error and keep the program running.
