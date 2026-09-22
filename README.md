# PyCalc-CLI

A simple, interactive terminal-based calculator written in Python. It demonstrates basic core programming fundamentals including continuous `while` loops, user input parsing, mathematical evaluations, and run-time error prevention.

##  Features

* **Core Math Operations:** Supports addition (+), subtraction (-), multiplication (*), and division (/).
* **Floating-Point Precision:** Automatically handles decimal computations by parsing inputs into floating-point numbers.
* **Zero-Division Safeguard:** Features active conditional checks to handle division-by-zero errors gracefully without crashing the application.
* **Persistent Session Loop:** Keeps the terminal session running for consecutive calculations until explicitly terminated by the user.

##  How it Works

1. **Menu Prompt:** The application displays a clear numerical menu of operational choices.
2. **Input Sanitation:** It evaluates if the chosen operation is valid before prompting the user for numeric inputs.
3. **Conditional Logic:** Utilizes an `if-elif-else` control flow structure to map the selected menu item to its corresponding mathematical operator.
4. **Session Control:** Evaluates string inputs (`y`/`n`) to determine whether to break or continue the active execution loop.

## Prerequisites & Execution

You only need Python 3.x installed to run this script.

```bash
python calculator.py
```


</div>
