# Java Date Management System

##  Project Overview
This project is a simple Java program that allows users to:
- Enter multiple dates dynamically.
- Validate and store dates.
- Determine the day of the week for a given date.
- Calculate the difference in days between two dates.
- Sort dates in ascending order (by year, then month, then day).

The program ensures proper date validation, considering leap years and invalid date entries.

---

##  Compilation and Execution
### 1️ Compile the program
Ensure you have Java installed, then open the terminal and run:
```sh
javac Main.java
```
### 2️ Run the program
Execute the compiled program with:
```sh
java Main
```
### 3️ Enter Input
You will be prompted to enter the number of dates, followed by individual date entries.

Example:
```
Enter the number of dates to process: 3

Enter date 1:
Day: 15
Month: 8
Year: 2022

Enter date 2:
Day: 1
Month: 1
Year: 2023

Enter date 3:
Day: 29
Month: 2
Year: 2024
```

---

##  Additional Notes & Challenges
- **Leap Year Handling**: The program correctly identifies leap years and allows February 29 in such cases.
- **Sorting**: Dates are sorted using `Collections.sort()` based on the `Comparable<Date>` interface.
- **Exception Handling**: Invalid inputs (like February 30) are caught and handled gracefully.
- **Improvements**: Future versions could include time support, different date formats, and more advanced date operations.

---

📌 **Developed in Java, ensuring accuracy and efficiency in date operations!** 🚀

