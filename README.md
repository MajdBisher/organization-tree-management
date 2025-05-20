# 🏢 Organization Tree Management System (Advanced Python Assignment)

This project is a Python-based command-line application that manages an organizational hierarchy for a high-tech company. It simulates a company structure where each employee has a unique ID, a role, and a potential manager, and supports hierarchical relationships and department-based reporting.

---

## 📌 Features

- Add new employees (with or without managers)
- Automatically assign a unique ID to each employee
- Enforce a single CEO (no manager)
- Delete employees only if they have no subordinates
- Reassign managers dynamically
- Print a full organization tree (hierarchical view)
- Print department-level summaries
- Validate inputs and handle errors gracefully

---

## 🧱 Object-Oriented Structure

### `Employee` class
- Represents a single employee
- Stores name, department, age, type, and subordinates
- Methods to add/remove subordinates and represent employee as string

### `Organization` class
- Manages all employees and company structure
- Stores the CEO and all employee records
- Contains logic for adding/removing/reassigning employees and displaying reports

---

## 📂 Project Structure

```
organization_project/
│
├── employee.py        # Defines the Employee class
├── organization.py    # Defines the Organization class and core logic
├── hw3_main.py        # Main CLI interface for the user (not shown here)
```

---

## 🚀 How to Run

1. Make sure all `.py` files are in the same directory.
2. Run the main interface:
```bash
python hw3_main.py
```
3. Use commands like:
- `welcome`
- `add_employee`
- `delete_employee`
- `print_employee`
- `assign_manager`
- `print_org`
- `print_dep`
- `quit`

---

## 👨‍💻 Author

**Majd Bisher**  
📧 MajdBisher85@gmail.com

---

## 🎓 Educational Purpose

This project was created as part of an advanced Python programming course to demonstrate mastery of:
- Object-Oriented Design
- Tree structures and recursion
- Input validation and CLI interactions
- Modular and maintainable code design

---

## 📝 License

This project is for educational use only.
