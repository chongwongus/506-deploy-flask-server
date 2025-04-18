# Flask Docker Application

A simple Flask application containerized with Docker.

## Endpoints

- `/your_name`: Returns a greeting message
- `/datetime`: Returns the current date and time

## How to Run

### Using Docker

```bash
# Build the Docker image
docker build -t flask-app .

# Run the container
docker run -p 5000:5000 flask-app
