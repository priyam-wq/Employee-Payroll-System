Here's a clear and concise description you can use for your GitHub repository to showcase this payroll system project:

---

## 🧾 Payroll System in Java

This project is a simple **Payroll Management System** implemented in Java using **Object-Oriented Programming (OOP)** principles. It demonstrates the use of **abstraction**, **inheritance**, and **polymorphism** to manage different types of employees and calculate their salaries.

### 🚀 Features

- **Abstract `Employee` class** with common attributes (`name`, `id`) and an abstract method `calculateSalary()`.
- **FullTimeEmployee** subclass that calculates salary based on a fixed monthly amount.
- **PartTimeEmployee** subclass that calculates salary based on hours worked and hourly rate.
- **PayrollSystem** class to manage employee records:
  - Add employees
  - Remove employees by ID
  - Display all employee details with calculated salaries
- **Interactive CLI** to input employee data and view payroll summary.

### 📦 Technologies Used

- Java (OOP concepts)
- `ArrayList` for dynamic employee storage
- `Scanner` for user input

### 📌 How to Run

1. Clone the repository.
2. Compile and run `Main.java`.
3. Enter the number of employees and their details as prompted.
4. View the payroll summary printed to the console.

### 🛠️ Future Enhancements

- Add support for part-time employee input via CLI.
- Implement file-based storage for employee records.
- Add GUI using JavaFX or Swing.
