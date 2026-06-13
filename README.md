# Dockerized Python Application

## Description

This project is a simple Dockerized Python application that uses the `python:3.12-slim` base image.

The application prints:

* The Python version running inside the container
* The current date and time

## Project Structure

```text
docker-demo/
│
├── app.py
├── Dockerfile
├── requirements.txt
└── README.md
```

## Build the Docker Image

```bash
docker build -t python-version-app .
```

## Run the Docker Container

```bash
docker run --rm python-version-app
```

## Sample Output

```text
Python Version: 3.12.x
Current Date and Time: 2026-06-13 15:00:00
```

## Screenshot

After running the container, take a screenshot of the terminal output and save it as:

```text
screenshots/output.png
```

Then add:

```markdown
![Output Screenshot](screenshots/output.png)
```
