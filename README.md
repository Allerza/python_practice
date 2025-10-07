🧮 Simple Tkinter Calculator

This is a basic calculator app built using Python’s built-in `tkinter` library.  
It supports simple arithmetic operations like addition, subtraction, multiplication, and division — wrapped in a clean and minimal GUI.

🚀 Features

- Responsive button layout similar to a standard calculator  
- Basic arithmetic: `+`, `-`, `×`, `÷`  
- Additional functions:
  - `AC` — Clear all
  - `+/-` — Toggle sign
  - `%` — Percentage
  - `√` — (Planned feature)
- Real-time display updates
- Centered, resizable window with styled color scheme (look is inspired by the apple calculator)
  
🧠 How It Works

- The calculator uses a global variable system (`A`, `B`, `operator`) to handle operations.  
- Button clicks are captured by the `button_clicked()` function, which updates the display label dynamically.
- The GUI layout is generated automatically from a 2D list (`button_values`).

💻 Requirements

- **Python 3.10 or newer**  
- No external libraries required — `tkinter` comes built-in with Python
