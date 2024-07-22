# AI_Math_Gesture
# AI-Powered Hand Gesture Recognition and Drawing Application

This project is an interactive application that uses hand gestures to draw on a canvas and interprets the drawings using Google Generative AI.

## Introduction
This application leverages computer vision and artificial intelligence to create a unique drawing experience. By recognizing hand gestures through a webcam, users can draw on a canvas, clear the canvas, and send the drawing to an AI for interpretation.

## Features
- Real-time hand gesture recognition
- Drawing on a canvas using hand gestures
- Clearing the canvas with a specific gesture
- AI-based interpretation of the drawing
- User-friendly interface with Streamlit

## Installation
To run this project locally, follow these steps:


Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:


pip install -r requirements.txt
Download and save the required image (th.jpeg) in the project directory.


Run the application:
streamlit run app.py


Usage
Start the application by running the Streamlit app.
Check the "Run" checkbox to start the webcam feed.
Use the following hand gestures to interact with the application:
Draw: Raise your index finger to draw on the canvas.
Clear: Raise your thumb to clear the canvas.
Send to AI: Raise all five fingers to send the drawing to the AI for interpretation.


View the AI-generated response in the "Answer" section.

Technologies Used
OpenCV: For capturing and processing webcam feed.
cvzone: For hand gesture recognition.
Google Generative AI: For interpreting the drawings.
Streamlit: For creating the user interface.
Python: As the programming language.
PIL: For image processing.   
