# Flask App - Dockerized

Basic Flask web application containerized with Docker and automated CI/CD via Jenkins.

## How to Build and Run

### Build Docker Image
```bash
docker build -t flask-app .
```

### Run Container
```bash
docker run -d -p 5000:5000 --name flask-container flask-app
```

### Access the App
Open http://localhost:5000 in your browser.

## Tech Stack

- **Python** – Application language
- **Flask** – Web framework
- **Docker** – Containerization
- **Jenkins** – CI/CD pipeline

## Author

**Mallikarjuna Kanal**

GitHub: https://github.com/MKanal2003
