# Final Project: Emotion Detector

## AI-Based Emotion Detection System


## Project Description
This project is a web-based application developed using **Python** and **Flask**. It leverages the **Watson NLP** library to analyze text provided by the user and identifies the underlying emotions. The application processes five key emotions: **anger, disgust, fear, joy, and sadness**, and determines which one is the **dominant emotion**.

## Features
*   **Real-time Analysis**: Processes text input via a web interface and returns results immediately.
*   **Error Handling**: Built-in capability to handle blank inputs and provide user-friendly error messages ("Invalid text! Please try again!").
*   **Unit Tested**: Includes a comprehensive test suite to ensure consistent and accurate output.
*   **Static Code Analysis**: Compliant with PEP 8 standards, achieving a 10/10 score using PyLint.

## Application Architecture
*   **Backend**: Flask-based server (`server.py`) and a custom package (`EmotionDetection`).
*   **Frontend**: HTML and JavaScript provided as part of the project repository.
*   **API**: Integrates with IBM Watson NLP Emotion Prediction service.

## Installation and Setup
1.  Ensure Python 3.x is installed.
2.  Install required dependencies:
    ```bash
    pip install requests flask pylint
