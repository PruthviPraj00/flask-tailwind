# CRUD Application with Flask, SQLAlchemy, and Tailwind CSS

This project is a simple CRUD (Create, Read, Update, Delete) application using Flask for the backend, SQLAlchemy for database interactions, and Tailwind CSS for styling.

## Getting Started

### 1. Set Up the Environment

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment:

- **Mac/Linux**:
  ```bash
  source .venv/bin/activate
  ```

- **Windows**:
  ```bash
  .venv\Scripts\activate
  ```

### 2. Install Dependencies

Install Python and npm packages:

```bash
pip install -r requirements.txt
npm install
```

### 3. Build CSS

Run the following command to compile Tailwind CSS:

```bash
npm run watch:css
```

### 4. Run the Application

Start the Flask application with:

```bash
python -m flask run
```

Visit `http://127.0.0.1:5000/` in your browser to see the app in action.


## Notes

- Make sure to have both Python and Node.js installed on your machine.
- Modify the Flask routes and SQLAlchemy models as needed for your application.
