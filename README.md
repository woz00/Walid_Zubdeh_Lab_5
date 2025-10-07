# Walid_Zubdeh_Lab_5

### How to Run:

#### 1. Create Virtual Environment:

Clone the repository and open the project in VSCode.

In the VSCode search bar at the top of the screen, type the following:

  >Python: Create Environment

Choose “Venv”.

Select a Python interpreter.

VSCode will create and automatically select the virtual environment.

#### 2. Install flask and sqlite3

Open a new terminal (the virtual environment should be active).
Type the following commands:

  >pip install flask

  >pip install sqlite3

#### 3. Start the flask application

Type the following commands:

  >cd main

  >flask --app User run

#### 4. Test the Get endpoints

Open in your browser URLs such as http://127.0.0.1:5000/api/users or http://127.0.0.1:5000/api/users/<user_id>
