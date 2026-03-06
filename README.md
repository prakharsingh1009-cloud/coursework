# coursework
# Programming Languages Assignment
# Mathematical Algorithms and Numerical Computation in Python

## Project Overview

This project implements several fundamental mathematical algorithms using Python. The objective is to understand how mathematical concepts such as the **Greatest Common Divisor (GCD)**, **Euler’s number approximation**, and **integer power properties** can be translated into computational algorithms.

The program demonstrates how numerical methods and basic programming logic can be used to solve mathematical problems efficiently. It also explores how accuracy and computational limitations affect numerical calculations.

---

## Objectives

The main objectives of this project are:

* To implement the **Euclidean Algorithm** for calculating the Greatest Common Divisor.
* To approximate **Euler’s number (e)** using both limit and series methods.
* To analyze computational errors in numerical approximations.
* To test mathematical properties of integers, such as determining whether a number is a power of another number.
* To understand the effect of floating-point precision in programming.

---

## Technologies Used

* **Programming Language:** Python
* **Libraries:** math
* **Environment:** Python Interpreter / Jupyter Notebook / VS Code

---

## Project Structure

The project is divided into three major problems.

### Problem 1: Greatest Common Divisor (GCD)

This section implements the **Euclidean Algorithm** to compute the GCD of two integers.

**Key Idea:**
The Euclidean algorithm repeatedly replaces the larger number with the remainder of the division until the remainder becomes zero.

**Steps:**

1. Take two integers as input.
2. Compute the remainder using modulo operation.
3. Replace the numbers until the remainder becomes zero.
4. The final value of the divisor is the GCD.

The program also demonstrates behavior when **negative numbers** are used.

---

### Problem 2: Approximation of Euler’s Number (e)

This section explores multiple ways to approximate Euler’s constant.

#### 1. Limit Definition

Euler’s number can be approximated using the limit:

[
e = (1 + 1/n)^n
]

The program calculates this value for different values of **n**.

#### 2. Floating Point Limitation

For extremely large values of **n**, computers may round (1/n) to zero due to floating-point precision limits. This causes the expression to evaluate incorrectly.

#### 3. Series Expansion

Euler’s number can also be approximated using the series:

[
e = \sum_{k=0}^{\infty} \frac{1}{k!}
]

The program calculates the factorial and adds successive terms of the series.

#### 4. Accuracy Control

A function is implemented that keeps adding terms until the approximation error becomes smaller than a given **epsilon value**.

#### 5. Error Analysis

The program prints the error between the computed approximation and the actual value obtained using the **math.exp()** function.

#### Conclusion

The **series method converges faster and provides better accuracy** compared to the limit formula.

---

### Problem 3: Testing Properties of Integers

This section focuses on checking mathematical properties of integers.

#### 1. Checking Power of 2

A function is implemented to determine whether a number is a power of 2 by repeatedly dividing the number by 2.

#### 2. Checking Power of Any Number

A more general function determines whether a number **n** is a power of another number **b**.

Example:

* 8 is a power of 2
* 27 is a power of 3

The program uses repeated division until the number becomes 1 or fails the condition.

---

## Key Concepts Demonstrated

* Euclidean Algorithm
* Numerical Approximation
* Factorial Computation
* Floating-Point Precision
* Error Analysis
* Integer Property Testing
* Iterative Algorithms in Python

---

## How to Run the Program

1. Install Python (version 3 or above).
2. Download or clone this repository.
3. Open the Python file(2025BSDSAI062_PRAKHARSINGH) in any IDE (VS Code, PyCharm, etc.).
4. Run the program:

```bash
python filename.py
```

5. Enter the required inputs when prompted.

---

## Learning Outcomes

After completing this project, the following concepts were understood:

* Implementation of mathematical algorithms using Python
* Understanding numerical approximation methods
* Analyzing computational errors in floating-point calculations
* Applying loops and conditional logic to mathematical problems
* Improving problem solving skills using algorithmic thinking

---

## Conclusion

This project demonstrates how mathematical concepts can be effectively implemented using programming. It highlights the importance of algorithm design, computational accuracy, and logical reasoning when solving numerical problems.By solving this project i get to know mnay maths tools which can be used in the python coding. 

---

## Author

Prakhar Singh(062)
IIM Sambalpur
