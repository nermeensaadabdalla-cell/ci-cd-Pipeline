# Flask CI/CD Pipeline Project 🚀

This project demonstrates a simple CI/CD pipeline using **Jenkins**, **GitHub**, and **Python Flask**. The pipeline automatically automates the process of checking out code, building a virtual environment, running tests, and deploying the application.

## 🛠 Tech Stack
* **Language:** Python (Flask Framework)
* **CI/CD Tool:** Jenkins
* **Version Control:** GitHub
* **Testing:** Pytest
* **Environment:** Ubuntu (Linux)

## 📸 Screenshots

### 1. Jenkins Pipeline Success
This screenshot shows that all pipeline stages (Checkout, Build, Test, and Deploy) were completed successfully.

![Jenkins Pipeline](Screenshot%202026-05-15%20195730.png)

### 2. Application UI
This screenshot shows the Flask application running live on port 5000 after a successful deployment.

![App UI](Screenshot%202026-05-15%20182811.png)

## 📄 Project Structure
* `app.py`: The main Flask application.
* `test_app.py`: Basic unit test for the app.
* `Jenkinsfile`: Defines the automation pipeline stages.
* `requirements.txt`: Project dependencies.
