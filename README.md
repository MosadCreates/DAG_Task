This DAG demonstrates basic Airflow functionality with three sequential tasks:

Print Current Date – Uses a BashOperator to print the current system date.

Print Welcome Message – Uses a PythonOperator to display a personalized welcome message.

Generate Random Number – Uses a PythonOperator to generate a random integer between 1 and 1000 and save it to /tmp/random.txt.

Task Flow:

Print Current Date → Print Welcome Message → Generate Random Number


Purpose:

Illustrates how to define a DAG and tasks in Airflow.

Shows task dependencies and execution order.

Demonstrates integration of Bash and Python operators.

Usage:

Run the DAG to see each task execute sequentially.

Verify that the random number file is created and contains the generated value.
