# BigData Assignment Submission

## Overview
This repository contains the implementation of two main tasks for the BigData assignment:

1. **Airflow DAG Task** – Demonstrates basic Airflow functionality with Bash and Python operators.  
2. **Flights Project Task** – A simple Flask-based project to verify project setup and output.

---

## Part 1: Airflow DAG (Airflow_Depi)

### DAG Description
The `Airflow_Depi` DAG consists of three sequential tasks:

1. **Print Current Date** – Prints the current system date using a `BashOperator`.  
2. **Print Welcome Message** – Displays a personalized message using a `PythonOperator`.  
3. **Generate Random Number** – Generates a random number (1–1000) and saves it to `/tmp/random.txt` using a `PythonOperator`.  

**Task Flow:**  

**Purpose:**  
- Demonstrates DAG and task creation in Airflow.  
- Shows integration of Bash and Python operators.  
- Illustrates task dependencies and sequential execution.

### DAG Screenshot
![DAG Screenshot](screenshots/dag_graph.png)

### Task Logs
- **Print Date:** ![Task 1 Log](screenshots/task1_log.png)  
- **Welcome Message:** ![Task 2 Log](screenshots/task2_log.png)  
- **Random Number:** ![Task 3 Log](screenshots/task3_log.png)  

### Random Number File
The generated number is saved in `/tmp/random.txt`.  
![Random File Screenshot](screenshots/random_txt.png)

---

## Part 2: Flights Project

### Project Description
A simple Flask-based project that confirms the project setup and functionality. Visiting the app displays a message indicating that the project is running correctly.

cd flights_project
python app.py
