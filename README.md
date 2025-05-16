# 📟 Smart Calculator 

This project is a **Natural Language-Based Smart Calculator** built with Python's `tkinter` GUI toolkit. It allows users to perform basic arithmetic and mathematical operations by typing natural language commands such as "add 5 and 7" or "what is the LCM of 12 and 18".

## 🎯 Objective

To create a user-friendly calculator that can:
- Interpret natural language inputs.
- Perform arithmetic operations (addition, subtraction, multiplication, division, modulus).
- Calculate LCM and HCF.
- Return results interactively via a graphical user interface.

## 🧰 Technologies Used

- **Python 3**
- **Tkinter** – for building the GUI
- **String parsing** – for extracting numbers and keywords from user input

## ⚙️ Features

- 🗣️ Accepts commands in simple English like:
  - `add 5 and 3`
  - `subtract 10 from 20`
  - `multiply 7 and 8`
  - `divide 40 by 5`
  - `lcm 4 and 6`
  - `hcf 12 and 18`
- 📤 Returns the result directly in a Listbox.
- 🎨 Clean and simple GUI interface using Tkinter.
- 🔁 Basic error handling and feedback for invalid inputs.

## 🧠 How It Works

- Extracts numbers from user input.
- Matches keywords (like "add", "multiply", "hcf") with corresponding functions.
- Performs the operation using those functions.
- Displays the result in a GUI output box.

## ▶️ How to Run

1. Clone or download the repository.
2. Ensure you have Python 3 installed.
3. Run the script using:
   ```bash
   python Smart_Calculator.py
   ```
4. Type a natural language command in the input field and press `Execute`.

## 📸 Application Preview

Below is a screenshot of the Smart Calculator GUI in action:
![1](https://github.com/user-attachments/assets/9995fefb-c71a-4700-9a46-377df2844d62)
Example output after entering LCM of 78, 47 and 14:
![2](https://github.com/user-attachments/assets/04d3e286-a73f-48b7-a59b-03d1d3a779d4)

## 📦 Example Inputs

- `What is the sum of 23 and 77?`
- `Find the HCF of 36 and 60`
- `Multiply 9 and 5`
- `Divide 144 by 12`

## 📌 Limitations

- Handles only two numerical operands per operation.
- Keyword matching is basic and case-insensitive.
- Limited support for complex expressions or grammatical variations.
