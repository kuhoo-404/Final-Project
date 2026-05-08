# Emotion Detection Web Application
This is the Final Project for the IBM Python Project for AI & Application Development course.
## 📝 Description
This project is a Flask-based web application that detects and analyzes emotions in text using the IBM Watson Embedded AI Libraries. It evaluates a given statement and returns an emotion profile consisting of scores for **anger, disgust, fear, joy, and sadness**, as well as identifying the **dominant emotion**.

This application was developed as the final project for the IBM "Python Project for AI & Application Development" course.

## ✨ Features
* **Watson NLP Integration:** Leverages the `emotion_aggregated-workflow_lang_en_stock` model to provide accurate emotional analysis.
* **Web Interface:** Includes a responsive UI built with HTML/JavaScript and served via a Flask backend.
* **Error Handling:** Robust validation to handle blank submissions and API 400 status codes gracefully.
* **Modular Packaging:** Code is structured into a reusable Python package (`EmotionDetection`).
* **Unit Tested:** Includes `unittest` test cases to verify the accuracy of the detection logic.
* **Static Code Analysis:** Server code has been optimized to achieve a perfect 10/10 score using Pylint.

## 🚀 Usage Instructions

### Prerequisites
Make sure you have Python 3 installed, along with the following libraries:
* `Flask`
* `requests`

### Running the Application
1. Clone this repository to your local machine.
   ```bash
   git clone [https://github.com/your-username/github-final-project.git](https://github.com/your-username/github-final-project.git)
