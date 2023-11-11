# Powdery Mildew Leaf Classification

## Overview

This project aims to classify leaf images based on their susceptibility using a deep learning model. The frontend is built using React.js, and the backend utilizes FastAPI. The core of the classification is powered by the EfficientNet B3 model.

## Features

- **Leaf Image Classification:** The deep learning model classifies leaf images into categories based on their susceptibility.

- **React.js Frontend:** A user-friendly web interface built with React.js allows users to interact with the classification system easily.

- **FastAPI Backend:** The backend, powered by FastAPI, handles requests, communicates with the deep learning model, and provides seamless integration with the frontend.

- **EfficientNet B3 Model:** The deep learning model, EfficientNet B3, is employed for accurate and efficient leaf image classification.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/leaf-classification.git
    cd leaf-classification
    ```

2. Install dependencies:

    ```bash
    # Frontend (React.js)
    cd frontend
    npm install

    # Backend (FastAPI)
    cd ../backend
    pip install -r requirements.txt
    ```

3. Run the application:

    ```bash
    # Frontend
    cd frontend
    npm start

    # Backend
    cd ../backend
    uvicorn main:app --reload
    ```

4. Visit `http://localhost:3000` in your browser to access the Leaf Classification application.

## Usage

1. Upload Leaf Image: Use the web interface to upload a leaf image for classification.

2. View Results: The classification results will be displayed, indicating the susceptibility category of the uploaded leaf.

