# Employee Management System

A simple and responsive Employee Management Web Application built using **Vue.js**, **Axios**, and **MockAPI**. This project demonstrates full CRUD (Create, Read, Update, Delete) operations with a clean and classic Bootstrap UI.

---

## 🚀 Features

* Add new employee records
* View all employees in a table
* Update employee details
* Delete employee records
* Responsive UI using Bootstrap
* Real-time API interaction using Axios

---

## 🛠️ Tech Stack

* **Frontend:** Vue.js
* **HTTP Client:** Axios
* **Backend (Mock):** MockAPI
* **Styling:** Bootstrap

---

## 📂 Project Structure

```
src/
 ├── components/
 │    ├── EmployeeForm.vue        # Create Employee
 │    ├── EmployeeList.vue        # Read Employees
 │    ├── UpdateEmployee.vue      # Update Employee
 │    └── DeleteEmployee.vue      # Delete Employee
 ├── App.vue                      # Main App Component
 ├── main.js                      # Entry Point
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/Sriranaa/Employee-Management-System.git
cd Employee-Management-System
```

### 2️⃣ Install Dependencies

```
npm install
```

### 3️⃣ Install Required Packages

```
npm install axios bootstrap
```

---

## ▶️ Run the Application

```
npm run serve
```

Open in browser:

```
http://localhost:8080
```

---

## 🌐 API Configuration

This project uses **MockAPI** as backend.

Example endpoint:

```
https://69f5fe38a72f01a951b915f3.mockapi.io/EmployeeData
```

### Employee Fields:

* ID (auto-generated)
* Name
* Designation
* Department
* Salary

---

## 🔄 CRUD Operations

| Operation | Method | Description             |
| --------- | ------ | ----------------------- |
| Create    | POST   | Add new employee        |
| Read      | GET    | Fetch all employees     |
| Update    | PUT    | Modify employee details |
| Delete    | DELETE | Remove employee         |

---

## 🎯 Key Concepts Used

* Vue Components (Reusable structure)
* Two-way Data Binding (`v-model`)
* Directives (`v-for`, `v-if`)
* Lifecycle Hook (`mounted()`)
* Axios for API calls
* Async operations handling

---

## 💡 Future Improvements

* Add search and filter functionality
* Add form validation
* Improve UI with cards or modals
* Add authentication system

---

## 📸 Output

* Functional CRUD application
* Responsive layout
* Real-time updates from API
* Screenshot
  ![Alt text](screenshot.png)
---

## 👨‍💻 Author

**Sri Ranaa Prathap Innamuri**
GitHub: https://github.com/Sriranaa

---

## 📜 License

This project is for educational purposes.

