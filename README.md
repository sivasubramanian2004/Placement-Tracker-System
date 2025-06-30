# 🎓 Placement Tracker System

A desktop-based Placement Tracker System developed using **Python (Tkinter)** and **MySQL** to manage student placement records. It supports **CRUD operations**, **search**, **filters**, and **CSV export** functionality with a clean user interface.

![Dashboard Screenshot](Screenshot%20(55).png)

## 🚀 Features

- ✅ Add, Edit, and Delete placement records
- 🔍 Search by Roll Number or Company
- 🎯 Filter records by Year and Salary Package
- 📤 Export data to CSV
- 🖥️ User-friendly GUI with Tkinter
- 🛢️ MySQL database connectivity

## 🧰 Technologies Used

- Python 3.x
- Tkinter (for GUI)
- MySQL (for backend database)
- Pandas (for CSV operations)
- mysql-connector-python

## 📂 Files in this Repository

- `final_placement_tracker.ipynb` – Jupyter Notebook containing the full source code
- `Screenshot (55).png` – Screenshot of the working application
- `README.md` – Project documentation

## 💽 MySQL Database Setup

1. Create the database and table in MySQL:

```sql
CREATE DATABASE placement_db;

USE placement_db;

CREATE TABLE placements (
    roll_no VARCHAR(20) PRIMARY KEY,
    name VARCHAR(50),
    phone VARCHAR(15),
    department VARCHAR(50),
    company VARCHAR(50),
    package FLOAT,
    year INT
);
