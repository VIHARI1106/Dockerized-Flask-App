# Dockerized Flask App

This is a simple Flask web application containerized using Docker.

## 🚀 How to Run the Application Locally Using Docker

### 🛠 Prerequisites
- Docker installed and running on your system

### 📦 Step-by-Step Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/VIHARI1106/Dockerized-Flask-App.git
   cd Dockerized-Flask-App
Build the Docker Image

bash
Copy code
docker build -t flask-docker-demo .
Run the Docker Container

bash
Copy code
docker run -p 5000:5000 flask-docker-demo
View the App
Open your browser and go to:

arduino
Copy code
http://localhost:5000
📝 Project Structure
Copy code
Dockerized-Flask-App/
│
├── Dockerfile
├── app.py
├── requirements.txt
└── README.md
📄 Description
app.py: Flask application file

Dockerfile: Docker instructions to build the image

requirements.txt: Python dependencies

README.md: Setup guide

🧪 Test Output
You should see something like this in the terminal:

csharp
Copy code
* Running on http://127.0.0.1:5000
✅ Example Output in Browser
When accessed, it should display:

csharp
Copy code
Hello from Dockerized Flask App!
🧰 Technologies Used
Python

Flask

Docker

Made with ❤️ for COSC HackWeek
