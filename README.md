GUI Calculator
------------------
A simple calculator built with Python and Tkinter — one of my beginner GUI projects.
What it does
Basic arithmetic — addition, subtraction, multiplication, division, percentages, and decimal support. Nothing fancy, just a clean clickable calculator window.

Built with
----------
Python

Tkinter (built-in, no extra installs needed)

How to run
-----------

Make sure you have Python installed, then just:
bashpython "GUI Calculator.py"
A window will pop up and you're good to go.
What I learned
This was my first time building a GUI app in Python. Got to understand how Tkinter widgets work, how to handle button events with lambdas, and how eval() can do the heavy lifting for math expressions (even if it's a bit sketchy in production).

Known issues
------------

No keyboard input support yet.

eval() is used for solving expressions — fine for personal use but not something you'd ship in a real app.

Button layout uses hardcoded place() coordinates so resizing the window looks a bit off.

