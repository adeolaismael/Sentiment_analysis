# Real-Time Sentiment Analysis Project

## Overview
This repository contains the code for a real-time sentiment analysis system. The project is divided into two main components: 

- `SENTIMENT-ANALYSIS`: This component uses Apache Spark to perform sentiment analysis on incoming data streams.
- `streaming`: This part is responsible for handling real-time data streams, ingesting data from Reddit.

## Components

### Spark Sentiment Analysis
- `Dockerfile`: Defines the Docker image for running the Spark jobs.
- `requirementsspark.txt`: Lists the Python dependencies necessary for the Spark component.
- `str.py`: The main Python script that uses Spark to analyze sentiments.

### Streaming
- `Dockerfile`: Docker image for the streaming component.
- `redd.py`: Python script that may handle streaming data from Reddit.
- `requirements.txt`: Python dependencies for the streaming component.
- `docker-compose.yml`: Docker Compose file to orchestrate the multi-container setup.

## Getting Started

### Prerequisites
- Docker
- Docker Compose
- Python 3.x

### Installation
1. Clone the repository to your local machine.
2. Navigate to the respective component directories to build the Docker images using the provided Dockerfiles.

### Usage
- Detailed usage instructions for deploying and running the system.
- Steps to start the streaming and sentiment analysis.
- Example command to build and run the containers using Docker and Docker Compose : 
- `docker compose up` : for running containers
- `docker build -t image_name` : for building docker image


