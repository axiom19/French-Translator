# French Translator
This project is a web-based French translator that uses Large Language Models (LLM) to translate English sentences into French. It incorporates speech-to-text and text-to-speech capabilities for a more interactive user experience.
Motivation: I am an A2 level French student and want to practice speaking French.

## Features

- English to French translation using IBM Watson Machine Learning
- Speech-to-text functionality for voice input
- Text-to-speech capability for audio output of translations
- Web interface built with Flask, HTML, CSS, and JavaScript

## Project Structure

The main components of this project are:

- `server.py`: Flask server that handles routing and API endpoints
- `worker.py`: Contains core functionality for speech-to-text, text-to-speech, and LLM translation
- Frontend files (HTML, CSS, JS) for the user interface

## Setup and Installation

(Add instructions for setting up the project, including any required dependencies and environment variables)

## Usage

(Provide instructions on how to run the application and use its features)

## API Endpoints

- `/speech-to-text`: Converts audio input to text
- `/process-message`: Handles translation requests and returns both text and audio responses

## Technologies Used

- Python
- Flask
- IBM Watson Machine Learning
- IBM Watson Speech-to-Text and Text-to-Speech services
- HTML/CSS/JavaScript

## Demo
![Demo Screenshot](https://github.com/axiom19/French-Translator/blob/main/demo/Demo%20SS.png)
[Watch the Demo Video](https://github.com/axiom19/French-Translator/blob/main/demo/Demo%20Vid.mov)
---

This project was created as a demonstration of integrating LLM technology with speech processing capabilities to create a practical language translation tool.
