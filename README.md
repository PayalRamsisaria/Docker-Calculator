# Docker Calculator

A simple Python-based Calculator application containerized using Docker.

## Project Overview

This project demonstrates:

* Python programming fundamentals
* Docker containerization
* Docker image creation
* Running applications inside containers
* Git and GitHub version control

This is a beginner-friendly DevOps project that shows how a Python application can be packaged and executed consistently across environments using Docker.

## Project Structure

```text
docker-calculator/
│
├── calculator.py
├── Dockerfile
└── README.md
```

## Technologies Used

* Python 3.11
* Docker
* Git
* GitHub

## Calculator Features

* Addition (+)
* Subtraction (-)
* Multiplication (*)
* Division (/)
* Division-by-zero handling
* Interactive command-line interface

## Python Code Execution

Run locally:

```bash
python calculator.py
```

Example:

```text
Simple Calculator
Enter First Number: 10
Enter Operator (+,-,*,/): *
Enter Second Number: 5

Result = 50
```

## Docker Setup

### Build Docker Image

```bash
docker build -t mycalculator .
```

### Run Docker Container

```bash
docker run -it mycalculator
```

## Dockerfile

```dockerfile
FROM python:3.11-slim

WORKDIR /app

COPY calculator.py .

CMD ["python", "calculator.py"]
```

## Git Commands Used

```bash
git init
git add .
git commit -m "Docker Calculator Project"
git push -u origin master
```

## Learning Outcomes

Through this project, I learned:

* Creating Python applications
* Writing Dockerfiles
* Building Docker images
* Running containers
* Managing source code with Git
* Publishing projects on GitHub

## Future Enhancements

* Flask Web Calculator
* Docker Compose integration
* CI/CD pipeline using GitHub Actions
* Deployment on AWS EC2
* Kubernetes deployment

## Author

Payal Ramsisaria

GitHub: https://github.com/PayalRamsisaria
