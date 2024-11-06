# FastAPI Application with Docker and JSON Data Persistence
------------------------------------------------------------
This project is a simple FastAPI application with Docker support. It uses a JSON file to store and persist user data, leveraging Docker Compose for streamlined container management.

## Table of Contents
* Features
* Project Structure
* Installation
* Usage
* Dockerization
* API Endpoints

## Features
* FastAPI framework for building APIs
* Data persistence using a JSON file
* Dockerized setup for easy deployment
* Docker Compose for managing multi-container setups

## Project Structure
![structure](C:\Users\Sanket\Downloads\screenshots)

## Installation
To run this project locally, ensure you have the following installed:

* Python 3.8+
* Docker & Docker Compose

## 1. Clone the repository
> git clone https://github.com/ps9824/your-repo-name.git
> cd your-repo-name

## 2. Install dependencies
If you prefer to run locally without Docker, install dependencies with:
> pip install -r requirements.txt

# Usage

To start the application locally:
> uvicorn app.main:app --reload
The FastAPI application will be accessible at http://127.0.0.1:8000.


## Dockerization

This project includes Docker configurations to simplify setup and deployment.

## 1. Build and run the Docker container
Run the following commands to start the app using Docker Compose:
> docker-compose up --build

## 2. Access the application
Once running, the FastAPI application is accessible at http://localhost:8000.

## 3. Stopping the Docker container
> docker-compose down


## API Endpoints
|Method|Endpoint|Description|      
|----|-----|-------|      
|Get|/|Returns a hello message|     
|Get|/users|Returns list of users stored in JSON file|      
|Post|/users|Accepts and stores user data in JSON file






























