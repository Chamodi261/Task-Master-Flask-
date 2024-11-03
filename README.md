# 📋 Task Master - Flask Application

Task Master is a simple task management application built with Flask. It allows users to create, update, and delete tasks, helping to keep track of to-dos easily.

## 🌟 Features
- 📝 **Add New Tasks**: Quickly add tasks to the list.
- ✏️ **Update Existing Tasks**: Modify tasks as needed.
- ❌ **Delete Tasks**: Remove completed or unnecessary tasks.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Flask
- Flask-SQLAlchemy

### ⚙️ Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Chamodi261/Task-Master-Flask-.git
    cd Task-Master-Flask-
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - **For Windows**:
        ```bash
        venv\Scripts\activate
        ```
    - **For macOS/Linux**:
        ```bash
        source venv/bin/activate
        ```

4. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application**:
    ```bash
    flask run
    ```

6. **Access the app** at `http://127.0.0.1:5000/`.

## 🗃️ Database
The app uses SQLite for storing tasks. The database file is automatically created as `test.db` in the root directory.

## 📁 File Structure
- **app.py**: Main application file
- **templates/**: HTML templates for the app
- **static/**: Static files (CSS, JavaScript)

## 💡 Usage
- Go to the homepage to view tasks.
- Use the form to add new tasks.
- Use "Update" to modify tasks and "Delete" to remove tasks.

---

🌐 **[Chamodi261 on GitHub](https://github.com/Chamodi261/Task-Master-Flask-)**
