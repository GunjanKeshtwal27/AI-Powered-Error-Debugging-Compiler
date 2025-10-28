#  Simple Code Error Debugger

A simple web application built with Flask that allows users to paste in a code snippet, which is then analyzed for common errors on the backend.

##  Features

* **Web Interface:** A clean HTML/CSS/JS frontend to paste and submit code.
* **Backend Analysis:** Uses a Python backend (Flask) to receive the code.
* **Error Reporting:** Runs a custom error-checking logic (from `errors.py`) on the code.
* **JSON Response:** Returns a list of found errors to the frontend.

##  Technologies Used

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS, JavaScript
* **Dependencies:** As listed in `requirements.txt`


##  How to Run This Project

Follow these steps to get the project running on your local machine.

### 1. Clone the Repository

(If you are downloading this from GitHub)
```bash
git clone [https://github.com/GunjanKeshtwal27/AI-Powered-Error-Debugging-Compiler.git](https://github.com/GunjanKeshtwal27/AI-Powered-Error-Debugging-Compiler.git)
cd AI-Powered-Error-Debugging-Compiler

###  Create a Virtual Environment (Recommended)
###  This creates an isolated environment for your projects dependencies.
On Windows:
python -m venv venv
.\venv\Scripts\activate

###  To Run the project-
 python -m pip install -r requirements.txt
 python app.py






