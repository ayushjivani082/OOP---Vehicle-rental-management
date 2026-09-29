# OOP---Vehicle-rental-management

# 🚗 Vehicle Rental Management System


---

## 📌 Project Overview

The **Vehicle Rental Management System** is a Python-based console application developed using **Object-Oriented Programming (OOP)** concepts.

The project allows users to manage different types of vehicles, including **Cars and Bikes**, and perform basic rental operations such as adding vehicles, renting vehicles, returning vehicles, and displaying vehicle details.

---

## 🎯 Project Objectives

- Understand the fundamentals of Python OOP.
- Create and use classes and objects.
- Implement inheritance using parent and child classes.
- Use encapsulation for sensitive vehicle information.
- Demonstrate method overriding.
- Manage vehicle rental and return operations.
- Create a simple menu-driven Python application.

---

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Concept:** Object-Oriented Programming (OOP)
- **Application Type:** Console-Based Application

---

## 📚 OOP Concepts Covered

### 1. Class and Object

The project uses classes such as:

- `Vehicle`
- `Car`
- `Bike`

Objects are created from these classes to store individual vehicle information.

### 2. Encapsulation

Private attributes are used for information such as:

- Rental price
- Availability status
- Renter ID

Getter and setter methods are used to access and modify these values.

### 3. Inheritance

`Car` and `Bike` inherit common properties and methods from the `Vehicle` class.

```python
class Car(Vehicle):
```

```python
class Bike(Vehicle):
```

This helps reduce code duplication and improves code organization. 

### 4. Polymorphism

Both `Car` and `Bike` have their own `display()` method, allowing each vehicle type to display its specific information.



### 5. Constructor

The `__init__()` method is used to initialize vehicle information such as vehicle ID, brand, model, and rental price.

---

## ⚙️ Main Features

### 🚘 Add a Car

Users can add a car by entering:

- Brand
- Model
- Vehicle ID
- Rental price per day
- Number of seats
- Fuel type

### 🏍️ Add a Bike

Users can add a bike by entering:

- Brand
- Model
- Vehicle ID
- Rental price per day
- Bike type

### 🔑 Rent a Vehicle

The user can enter a Vehicle ID and Renter ID to rent an available vehicle.

### 🔄 Return a Vehicle

A rented vehicle can be returned and its availability status is changed back to **Available**.

### 📋 Show Vehicle Details

The application displays the details of all vehicles stored in the system.

### ❌ Exit

The user can exit the application through the menu.

---

## 🧾 Menu

```text
--- Python OOP Project: Vehicle Rental Management System ---

1. Add a Car
2. Add a Bike
3. Rent a Vehicle
4. Return a Vehicle
5. Show Vehicle Details
6. Exit
```

The menu-driven system is implemented using a continuous `while` loop.

---

## ▶️ How to Run

### Step 1: Install Python

Make sure Python is installed on your computer.

### Step 2: Download or Clone the Repository

Download this project or clone the GitHub repository.

### Step 3: Open the Project

Open the project folder in **VS Code**, **IDLE**, or another Python editor.

### Step 4: Run the Python File

Run:

```bash
python oop.project.py
```

### Step 5: Use the Menu

Select an option from the menu and follow the instructions displayed on the screen.

---

## 📂 Project Structure

```text
Vehicle-Rental-Management-System/
│
├── oop.project.py
└── README.md
```

---

## 🔗 Project Links

### GitHub Repository

**Paste your GitHub repository link here:**

`YOUR_GITHUB_REPOSITORY_LINK`

### 🎥 Project Explanation Video

**Paste your video link here:**

`YOUR_VIDEO_LINK`

---

## 💡 Learning Outcome

Through this project, I learned how to apply Python OOP concepts in a practical console-based application.

The project helped me understand:

- Classes and Objects
- Constructors
- Encapsulation
- Inheritance
- Polymorphism
- Method Overriding
- Getter and Setter Methods
- `isinstance()`
- Lists and Loops
- Menu-driven programming

---

## 👨‍💻 Author

**Ayush Jivani**

Python OOP Project  
Vehicle Rental Management System

---

## ⭐ Conclusion

The **Vehicle Rental Management System** is a simple Python OOP project designed to demonstrate how Object-Oriented Programming concepts can be used to build a practical application for managing vehicles and rental operations.
