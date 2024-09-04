# Hostname Web App

This is a simple Python Flask application that displays the hostname of the Docker container on a web page.

## Prerequisites

- Docker
- Python 3.9 or later

## Getting Started

### Clone the Repository

```shell
git clone https://github.com/davisdre/hostname-webapp.git
cd hostname-webapp
```

### Build the Docker Image
Build the Docker image using the following command:
```shell
docker build -t hostname-webapp .
```

### Build the Docker Container
Run the Docker container with the following command:
```shell
docker run -d -p 80:80 hostname-webapp
```

### Access the Web Page
Open your web browser and navigate to `http://localhost` (or the IP address of your Docker host). You should see the hostname of the container displayed on the web page.

## Files
- `app.py`: The main Flask application file.
- `Dockerfile`: The Dockerfile used to build the Docker image.

## License
This project is licensed under the MIT License - see the LICENSE file for details.