# Text Summarisation App

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/your/awesome/project/blob/master/LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![Docker](https://img.shields.io/badge/Docker-20.10-blue.svg)](https://www.docker.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.68-blue.svg)](https://fastapi.tiangolo.com/)
[![AWS](https://img.shields.io/badge/AWS-Cloud%20Platform-orange.svg)](https://aws.amazon.com/)
[![VSCode](https://img.shields.io/badge/VSCode-Editor-lightgrey.svg)](https://code.visualstudio.com/)

Welcome to the Text Summarisation App project! This repository contains the source code for an app that generates summaries for text documents. The app is developed using Python and leverages the AutoModelForSeq2SeqLM from the Transformers Library for training and tokenisation. It is dockerized using Docker for seamless deployment in a production environment and is hosted on the AWS platform.

## Features

- Generate summaries for text documents
- FastAPI-based web interface for interacting with the app
- Docker containerization for easy deployment
- CI/CD pipeline using GitHub Actions for automated testing and deployment

## Technologies Used

- ![Python](https://img.shields.io/badge/Python-3.9-blue.svg): The main programming language used in this project.
- ![Docker](https://img.shields.io/badge/Docker-20.10-blue.svg): Containerization platform used to package the app and its dependencies.
- ![FastAPI](https://img.shields.io/badge/FastAPI-0.68-blue.svg): A modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.
- ![AWS](https://img.shields.io/badge/AWS-Cloud%20Platform-orange.svg): The cloud platform where the app is hosted.
- ![VSCode](https://img.shields.io/badge/VSCode-Editor-lightgrey.svg): The Integrated Development Environment (IDE) used for coding.

## Getting Started

Follow the instructions below to get a local copy of the project up and running on your machine.

### Prerequisites

- Python 3.9: Install Python from the official website: [Python Downloads](https://www.python.org/downloads/release/python-390/)
- Docker 20.10: Install Docker from the official website: [Docker](https://www.docker.com/)
- AWS Account: Sign up for an AWS account if you don't have one: [AWS](https://aws.amazon.com/)
- VSCode: Install Visual Studio Code from the official website: [VSCode](https://code.visualstudio.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your/awesome/project.git
   ```

2. Change to the project directory:

   ```bash
   cd project-directory
   ```

3. Set up a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run the FastAPI development server:

   ```bash
   uvicorn main:app --reload
   ```

   This will start the server, and you can access the app at `http://localhost:8000` in your browser.

2. Interact with the app by providing text documents and generating summaries.

### Deployment

To deploy the app using Docker and host it on AWS, follow these steps:

1. Build the Docker image:

   ```bash
   docker build -t text-summarisation-app .
   ```

2. Push the Docker image to a container registry, such as Docker Hub or Amazon ECR.

3. Create an AWS EC2 instance or any other suitable AWS service to host the Docker container.

4. Pull the Docker image on the EC2 instance.

5. Run the Docker container on the EC2 instance.

For more detailed instructions on deploying Docker containers on AWS, please refer to the official AWS documentation.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT](https://github.com/your/awesome/project/blob/master/LICENSE) License.
