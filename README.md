# Project Setup Guide

## Setting up the Virtual Environment

1. **Create a virtual environment:**
    ```sh
    py -m venv .venv
    ```

2. **Activate the virtual environment:**
    ```sh
    source .venv/bin/activate
    ```

## Installing Dependencies

1. **Install Flask:**
    ```sh
    pip install flask
    ```

2. **Install Flask-RESTful:**
    ```sh
    pip install flask_restful
    ```

3. **Install Flask-SQLAlchemy:**
    ```sh
    pip install flask_sqlalchemy
    ```

4. **Freeze the installed dependencies into `requirements.txt`:**
    ```sh
    pip freeze > requirements.txt
    ```

## Creating Important Files

1. **Create a `.gitignore` file:**
    ```sh
    touch .gitignore
    ```

## Managing the Virtual Environment

1. **Deactivate the virtual environment:**
    ```sh
    deactivate
    ```

2. **Install dependencies from `requirements.txt`:**
    ```sh
    pip install -r requirements.txt
    ```

## Running the Application

1. **Run the code on localhost:**
    ```sh
    py api.py
    ```

2. **Create the database file (create_db.py) and run:**
    ```sh
    py create_db.py
    ```

---

Feel free to edit and expand this guide as your project evolves!
