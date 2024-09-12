# Automated Candidate Evaluation System

## Description

This project aims to design and develop an automated candidate evaluation system using prompt engineering techniques and chatbot training. The system leverages prompting patterns such as personas and few-shot examples to provide accurate and tailored evaluations based on recruiters' needs '12 fields evaluated'.

## Features

- **Automated Evaluation**: Analyzes candidate responses to provide precise and objective assessments.
- **Prompt Engineering**: Utilizes personas and few-shot examples to enhance the quality of assistant interactions .
- **Custom Features**: Development of specific functionalities tailored to the system's requirements.
 
This uses the [Flask](https://flask.palletsprojects.com/en/2.0.x/) web framework. It is inspired from [quickstart tutorial](https://beta.openai.com/docs/quickstart).

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/)

2. Clone this repository

3. Navigate into the project directory

4. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

5. Install the requirements

   ```bash
   $ pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file

   ```bash
   $ cp .env.example .env
   ```

7. Add your [API key](https://beta.openai.com/account/api-keys and GOOGLE API Key (for STT and TTS) to the newly created `.env` file

8. Run the app
   terminal cmd
   /venv/Scripts/activate.bat
   flask run --host=0.0.0.0 --port=5001
   




##pour exec dans le terminale 
run-
& /venv/Scripts/Activate.ps1
run-
flask run --host=0.0.0.0 --port=5001
