
# Flask Application for VCC Assignment

This repository contains a Flask web application developed as part of the VCC assignment. It features a simple web interface with multiple routes, each demonstrating different functionalities including serving HTML pages and handling JSON data.

## Features

- Home page with navigation links
- About page with project information
- Data page showing JSON data

## Prerequisites

Before you can run this application, you'll need the following installed on your system:

- Python 3.9 or higher
- Docker
- Git (for version control)

## Installation

Follow these steps to get the environment set up:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/GowthamRam2000/flask-app
   cd flask-app
   ```

2. Build the Docker image:
   ```bash
   docker build -t flask-app .
   ```

## Running the Application

To run the application, use the following Docker command:

```bash
docker run -p 5001:5000 flask-app
```

This command runs the Docker container and exposes it on port 5001 of your localhost, mapping to port 5000 inside the Docker container.

## Accessing the Application

After running the container, access the application by navigating to `http://localhost:5001` in your web browser. You will see the home page with links to other pages.

## Project Structure

- `app.py`: Contains the Flask application setup and routes.
- `templates/`: Contains the HTML templates for the application.
- `static/`: Contains static files like CSS stylesheets.
- `Dockerfile`: Contains instructions for Docker to build the application environment.
- `requirements.txt`: Lists the Python dependencies required by the application.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

For any further queries or issues, please open an issue on the GitHub repository, or contact the repository owner at `g23ai2029@iitj.ac.in`.
