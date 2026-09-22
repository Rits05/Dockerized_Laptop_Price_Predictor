# Laptop Price Predictor

A machine learning-based web application that predicts the price of a laptop based on its specifications. The project uses a regression model and is deployed as a Flask web application with Docker containerization.

## Project Overview

The Laptop Price Predictor is a machine learning project that estimates laptop prices based on specifications such as company, laptop type, RAM, weight, CPU, GPU, operating system, screen size, and other features.

The trained machine learning pipeline is integrated with a Flask web application, allowing users to enter laptop specifications and receive a predicted price.

The application is also Dockerized and the Docker image is available on Docker Hub.

## Features

* Predict laptop prices using machine learning
* Flask-based web application
* Regression-based prediction model
* User-friendly input interface
* Pre-trained model stored using Pickle
* Dockerized application
* Docker Hub image available
* Easy local and containerized deployment

## Technologies Used

* Python
* Flask
* Pandas
* NumPy
* Scikit-learn
* HTML/CSS
* Jupyter Notebook
* Pickle
* Docker
* Docker Hub

## Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Rits05/Dockerized_Laptop_Price_Predictor.git
```

### 2. Move into the Project Directory

```bash
cd Dockerized_Laptop_Price_Predictor
```

### 3. Create Virtual Environment

```bash
python -m venv myenv
```

### 4. Activate Virtual Environment

For Windows:

```bash
myenv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
python app.py
```

Open the application in your browser:

```text
http://127.0.0.1:5000
```

## Run Using Docker

### 1. Build Docker Image

```bash
docker build -t laptop-price-predictor .
```

### 2. Run Docker Container

```bash
docker run -p 5000:5000 laptop-price-predictor
```

Open:

```text
http://127.0.0.1:5000
```

## Docker Hub

Docker Hub image:

```text
riti05/laptop
```

### Pull Docker Image

```bash
docker pull riti05/laptop
```

### Run Pulled Image

```bash
docker run -p 5000:5000 riti05/laptop
```

Then open:

```text
http://127.0.0.1:5000
```

## Docker Workflow

### Build

```bash
docker build -t laptop-price-predictor .
```

### Tag

```bash
docker tag laptop-price-predictor riti05/laptop:latest
```

### Push

```bash
docker push riti05/laptop:latest
```

### Pull

```bash
docker pull riti05/laptop:latest
```

### Run

```bash
docker run -p 5000:5000 riti05/laptop:latest
```
