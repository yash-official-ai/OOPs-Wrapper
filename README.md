# 👨‍💼 Employee Management System (Python OOP Project)

## 📌 Project Overview

The **Employee Management System** is a Python-based Object-Oriented Programming (OOP) project designed to demonstrate the core concepts of OOP, including:

- ✅ Classes and Objects
- ✅ Inheritance
- ✅ Encapsulation
- ✅ Constructors and Destructors
- ✅ Method Overriding
- ✅ Menu-Driven Programming
- ✅ Runtime Object Creation

The system allows users to create and manage different types of personnel such as **Persons**, **Employees**, and **Managers** through an interactive console-based menu.

---

## 🎯 Features

### 👤 Create a Person
Users can create a basic person by entering:
- Name
- Age

### 🧑‍💼 Create an Employee
Users can create an employee with:
- Name
- Age
- Employee ID
- Salary

### 👨‍💼 Create a Manager
Managers inherit all Employee properties and include:
- Name
- Age
- Employee ID
- Salary
- Department

### 📋 Display Details
View stored information for:
- Person
- Employee
- Manager

### 🔍 Inheritance Verification
The program demonstrates OOP inheritance by checking whether:

```python
Manager is subclass of Employee
```

Output:

```python
True
```

### 🚪 Exit System
Safely exits the program and frees resources.

---

# 🏗️ OOP Class Structure

```text
Person
   │
   └── Employee
            │
            └── Manager
```

### Person Class
Attributes:
- Name
- Age

Methods:
- Display Details

### Employee Class (Inherits Person)
Additional Attributes:
- Employee ID
- Salary

Methods:
- Display Employee Details

### Manager Class (Inherits Employee)
Additional Attributes:
- Department

Methods:
- Display Manager Details

---

# 💻 Sample Execution

### Create Person

```text
Enter Name: donald
Enter Age: 45

Person created with name: donald and age: 45
```

### Create Employee

```text
Enter your name: Akshat
Enter Age: 30
Enter Employee ID: G876
Enter Salary: 5600

Employee created with name: Akshat, age: 30,
ID: G876 and salary: $5600.0
```

### Create Manager

```text
Enter your name: yash
Enter age: 32
Enter Employee ID: M978
Enter Salary: 10000
Enter Department: sales

Manager created with name: yash, age: 32,
ID: M978, salary: $10000.0,
and department: sales
```

### Display Employee Details

```text
Employee Details:
Name: Akshat
Age: 30
Employee ID: G876
Salary: $5600.0
```

### Exit Program

```text
Exiting the system. All resources have been freed.
Goodbye!!
```

### Inheritance Check

```text
Checking Inheritance:
Is Manager subclass of Employee? True
```

---

# 🛠️ Technologies Used

- Python 3.x
- Object-Oriented Programming (OOP)
- Jupyter Notebook Compatible
- Console-Based Interface

---

# 📚 OOP Concepts Demonstrated

| Concept | Implementation |
|----------|---------------|
| Classes & Objects | Person, Employee, Manager |
| Inheritance | Manager → Employee → Person |
| Constructors | `__init__()` |
| Destructors | `__del__()` |
| Method Reuse | Parent class methods |
| Polymorphism | Display methods |
| Encapsulation | Class attributes |


---

## 👨‍💻 Author

**Yash**

Python Object-Oriented Programming Project

> "Programming is not about what you know; it's about what you can build."
