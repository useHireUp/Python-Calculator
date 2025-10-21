
# Python Beginner Assessment — Console Calculator (Full README)

Welcome to the **Python Beginner Coding Assessment**!  
In this project, you’ll build a **simple calculator** that runs in the **console** — no graphics or frameworks needed.

---

## Objective
Create a program that performs **addition, subtraction, multiplication, and division** based on user input.

---

## What You’ll Learn
By completing this assessment, you’ll practice:
- Getting user input with `input()`
- Performing arithmetic operations
- Using **functions** to organize your code
- Applying **if/elif/else** conditionals
- Handling **invalid input** and **errors**
- Optionally repeating actions with **loops**

---

## Requirements

Your program must:

1. **Display a menu** with four operation choices:
   ```
   Select operation:
   1. Add
   2. Subtract
   3. Multiply
   4. Divide
   ```
2. **Ask the user** to select an operation (1–4).  
3. **Ask for two numbers** as input.  
4. **Perform the selected operation** and print the result.  
5. Handle the following cases:
   - **Division by zero** → show an error message  
   - **Invalid menu choice** → prompt again  
   - **Non-numeric input** → display an error message  
6. (Optional) Ask if the user wants to perform another calculation before exiting.

---

## Getting Started

### 1. Clone This Repository
```bash
git clone https://github.com/your-org/python-calculator-assessment.git
cd python-calculator-assessment
```

Or download the ZIP file and open it in your preferred editor (VS Code, IDLE, etc.).

---

### 2. Create Your File
Create a file named:
```
calculator.py
```

You’ll write all your code in this file.

---



## Running the Program

1. Save your file as `calculator.py`.
2. Open your terminal and navigate to the project directory.
3. Run the program:
   ```bash
   python calculator.py
   ```
   or on some systems:
   ```bash
   python3 calculator.py
   ```

---

## Example Output

```
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice (1/2/3/4): 3
Enter first number: 4
Enter second number: 7
Result: 28
Do you want to perform another calculation? (yes/no): no
Goodbye!
```

---


##  Bonus Challenges
- Add **power (xⁿ)** or **modulus (%)** operations  
- Format results to **two decimal places**  
- Store calculation **history** in a list  
- Let users **chain calculations** without restarting  

---

##  Submission

When you’re done:
```bash
git add calculator.py
git commit -m "Complete calculator assessment"
git push origin main
```

---

## Resources
- [Python Official Tutorial](https://docs.python.org/3/tutorial/)
- [GitHub Getting Started](https://docs.github.com/en/get-started)

> *This exercise is part of the HireUp Beginner Python Series — designed to help you build confidence with real coding tasks.*
