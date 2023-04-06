## Introduction

This is a simple Python flask app with a modal chat window for the users to interact with GPT models within an empty web page. The goal of this project was to use GPT-4 available from Bing and generate a webpage with dragable modal chat window that would represent an interface for the user to interact with the OpenAI GPT model.

### Frontend

The frontend is written using Bootstrap as well as custom JavaScript to send user's query in the background and receive the response back from the OpenAI GPT model.

### Backend

The backend is written in Python flask with `/chat` and `/` routes to process user's queries.

## Installation

1. Run `sudo git clone https://github.com/arquisito/modal-draggable-chat-gpt` in the home directory to clone this repository.
2. Install pip, ___, and ____ if you don't already have them installed (skip if you do):
For pip: `sudo apt install python3-pip` NOTE: If you encounter an error saying there is no installation candidate, run `sudo apt-get update`, then try again.
For docker: 


In the directory for this repository, run `pip install -r requirements.txt` to install all necessary dependencies.
3. Replace the openai_api with your OpenAI API key inside of `app.py` file.
4. Run `flask --app app run --host 0.0.0.0 --debug` from the main directory of this project.
