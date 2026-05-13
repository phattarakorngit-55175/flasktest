# Flask Web Application

A professional web application built with Python and the Flask framework.

## 🚀 Features
- **User Authentication:** Sign up and Log in functionality.
- **Modular Design:** Uses Flask Blueprints for clean code organization.
- **Database Integration:** Ready for SQLAlchemy models.
- **Clean Structure:** Follows industry-standard Flask project layout.

## 🛠️ Tech Stack
- **Backend:** Python, Flask
- **Database:** SQLAlchemy
- **Authentication:** Flask-Login
- **Environment:** Python venv (Virtual Environment)

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd Code_Projects
   ```

2. **Create and activate virtual environment:**
   ```powershell
   # Windows
   python -m venv venv
   .\venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🏃 How to Run
Once the environment is set up and dependencies are installed, run the app using:
```powershell
python main.py
```
The application will be available at `http://127.0.0.1:5000`

## 📂 Project Structure
- `website/`: Main application package.
  - `auth.py`: Routes for authentication.
  - `views.py`: Main application routes.
  - `models.py`: Database models.
  - `templates/`: HTML files.
  - `static/`: CSS and JavaScript files.
- `main.py`: Entry point of the application.
- `requirements.txt`: List of project dependencies.
