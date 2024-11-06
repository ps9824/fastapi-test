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
'
project_root/
│
├── app/
│   ├── main.py           # Entry point for FastAPI application
│   ├── schema.py         # Defines data schemas and models
│   ├── services.py       # Handles business logic and data operations
│   └── data.json         # JSON file for data persistence
│
├── Dockerfile            # Docker setup for the FastAPI application
├── docker-compose.yml    # Docker Compose configuration
└── README.md             # Project documentation
'
