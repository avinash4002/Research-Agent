# Research Agent

## Overview
Research Agent is a project aimed at automating and enhancing the research process using advanced algorithms and AI technologies.

## Features
- Automated data collection
- Intelligent data analysis
- Customizable research parameters
- User-friendly interface

## Installation
To install the Research Agent, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/avinash4002/Research-Agent
    ```
2. Navigate to the project directory:
    ```bash
    cd Research_agent
    ```
3. Create a venv:
    ```bash
    python -m venv .venv
    source .venv/bin/activate
    ```    
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Start the server:
    ```bash
    python manage.py runserver
    ```
6. Build the docker image:
    ```bash
    docker-compose build --no-cache
    ```
7. Run the docker container:
    ```bash
    docker-compose up -d
    ```
