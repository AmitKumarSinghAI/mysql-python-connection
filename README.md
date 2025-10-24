# 🐍 MySQL Connection with Python in Jupyter Notebook

This project demonstrates how to connect a **MySQL database** with **Python** using the `mysql.connector` library inside a **Jupyter Notebook**.  
It includes creating a database, connecting to it, and executing SQL queries — all from Python.

---

## 🚀 Repository Details

**Repository Name:** `mysql-python-connection`  
**Description:** A simple project showing how to connect MySQL database with Python using Jupyter Notebook.

---

## 🚀 Features
- Connect to MySQL Server from Python  
- Create a new database using SQL  
- Connect to a specific database  
- Execute and manage SQL queries  
- Error handling for failed connections  

---

## 🧰 Requirements

Make sure you have the following installed:

- Python 3.x  
- MySQL Server  
- Jupyter Notebook  
- Libraries:
  ```bash
  pip install mysql-connector-python pandas
  ```

---

## 🧑‍💻 How to Run

1. Clone this repository:
   ```bash
   git clone 
   https://github.com/AmitKumarSinghAI/mysql-python-connection/blob/main/mysql_py.ipynb
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook mysql_py.ipynb
   ```
3. Run each cell step-by-step to:
   - Connect to MySQL Server  
   - Create a database  
   - Connect to that database  
   - Run SQL queries  

---

## ⚙️ Code Overview

```python
import mysql.connector
from mysql.connector import Error

# Connect to MySQL Server
connection = mysql.connector.connect(
    host="localhost",
    user="root",
    passwd="your_password"
)

print("Connected to MySQL Server")
```

---

## 🧠 Important Notes
- Do **not** share your real MySQL password in public repositories.  
  Instead, use:
  ```python
  password = input("Enter your MySQL password: ")
  ```
- You can extend this project by adding:
  - Table creation
  - Data insertion and retrieval
  - Pandas integration for analysis

---

## 🏁 Output Example

```
Connected to MySQL Server
Database created....
```
---

## 🧑‍🏫 Author
**Amit Kumar Singh Kurmi**  
📍 Kalinga University, India  
🎯 Aspiring AI / Gen AI Engineer  
📧 [Your Email or GitHub Profile Link]
