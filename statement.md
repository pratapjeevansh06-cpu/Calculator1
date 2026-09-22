# 🧮 Calculator Project

A lightweight, user-friendly **Calculator application** built to perform fundamental mathematical operations. This project provides a clean user interface and robust logic to handle everyday calculations seamlessly.

---

## 📋 Problem Statement

Traditional manual calculations are prone to human error, especially when handling multi-step arithmetic expressions. This project aims to solve this issue by developing a responsive, digital calculator that executes arithmetic tasks instantaneously and accurately following standard mathematical order of operations (**PEMDAS/BODMAS**).

### Core Requirements:
1. **User Interface:** Provide an interactive display showing current inputs and calculation results.
2. **Input Processing:** Support mouse clicks/taps as well as physical keyboard inputs.
3. **Accuracy:** Handle decimal precision correctly and manage edge cases (like division by zero) without crashing.

---

## ✨ Features

- **Basic Arithmetic:** Supports Addition (`+`), Subtraction (`-`), Multiplication (`×`), and Division (`÷`).
- **Advanced Operators:** Percentage (`%`), Square Root (`√`), and Exponential Powers (`xʸ`).
- **Memory Operations:** Clear Last Entry (`CE`), Clear All (`C`), and Backspace logic.
- **Responsive Design:** Optimizes instantly for desktop, tablet, and mobile screens.
- **Theme Support:** Clean, modern interface with native dark/light mode toggle.

---

## 🚀 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+) *[Or substitute with React, Python, Java, etc.]*
- **Version Control:** Git & GitHub

---

## 🛠️ Getting Started

Follow these steps to set up and run the project locally:

### Prerequisites
Make sure you have a modern web browser installed (e.g., Chrome, Edge, Safari, Firefox).

### Installation & Execution
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com
   ```
2. Navigate into the project folder:
   ```bash
   cd calculator
   ```
3. Open the main file in your preferred web browser:
   ```bash
   # For HTML/JS projects
   open index.html 
   ```

---

## 🧪 Edge Cases Handled

- **Division by Zero:** Displays a graceful error statement (`"Error: Cannot divide by zero"`) instead of crashing or returning `Infinity`.
- **Decimal Control:** Prevents users from inputting multiple consecutive decimal points (e.g., `4.5.6`).
- **Large Numbers:** Implements responsive text resizing or exponential notation for overflow string.
