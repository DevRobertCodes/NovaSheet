# NovaSheet

Welcome to **NovaSheet** — a lightweight, powerful spreadsheet engine built with JavaScript, designed to evaluate complex formulas and functions dynamically.

---

## 🚀 Project Overview

NovaSheet is a functional spreadsheet parser and evaluator that supports:

- Arithmetic operations with proper operator precedence (multiplication, division, addition, subtraction)
- Custom spreadsheet functions like SUM, EVEN, FIRSTTWO, LASTTWO, HAS2, INCREMENT, and more
- Recursive formula evaluation allowing nested function calls
- Array manipulations with utilities for filtering, incrementing, checking conditions, and removing duplicates
- Easy extensibility for adding new spreadsheet functions

---

## 🛠️ Features

- **Recursive formula parsing:** Ensures formulas are fully evaluated step-by-step until completion.
- **Function parsing:** Recognizes and executes spreadsheet-style functions (e.g., `SUM(1, 2, 3)`).
- **Operator precedence handling:** Handles multiplication and division before addition and subtraction.
- **Extensible function set:** Easily add new spreadsheet functions for powerful computations.
- **Robust input parsing:** Supports decimal numbers, nested functions, and edge cases.
- **Clean, modular code:** Designed for readability and easy enhancement.

---

## 💡 How to Use

1. Clone this repository.
2. Open the main HTML file in your browser.
3. Enter spreadsheet formulas starting with `=` in the cells (e.g., `=SUM(1, 2, 3)` or `=2+3*4`).
4. The spreadsheet evaluates and displays the results dynamically.

---

## 🔗 Live Demo

[https://devrobertcodes.github.io/NovaSheet/]

---

## 📁 Repository Structure

- `index.html` — Main UI and spreadsheet layout
- `script.js` — Core spreadsheet evaluation logic
- `styles.css` — Optional styles for UI
- `README.md` — This documentation file

---

## 📈 Future Improvements

- Add support for more complex functions and logical operators
- Enable referencing between cells (e.g., `=A1 + B2`)
- Build UI enhancements for a better spreadsheet experience
- Add persistent saving/loading of sheets

---

## 🙌 About Me

I'm WebNova, a passionate web developer on a mission to build meaningful projects while growing consistently. This project reflects my journey and dedication to mastering JavaScript and functional programming.

---

## 📜 License

This project is open source and free to use.

---

**Thank you for checking out NovaSheet!**


