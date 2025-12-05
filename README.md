# Automated-Garage-Door-Opening-Using-AI
This project is meant to automatically open a garage door for our Smart Robot, using AI to detect the Smart Robot. This robot will drive to the garage door which then triggers the garage door to open automatically. 

Required Items: Smart Robotn (OAR V4.0), Tape, Small garage door to fit the smart robot (1 foot wide), wood, motor, Arduino, Huggingface, Teachable Machines, 


# My Contribution: Camera-Based Car Detection Using Teachable Machine
 
For this project, I was responsible for developing the AI system that allowed the garage door setup to recognize when a car was present. My work focused on training and integrating an image classification model using Google Teachable Machine, and connecting it to the Arduino-controlled motor via our project’s code.

# What I Did

Collected and prepared training data by taking multiple images of the car from different angles and lighting conditions.

Trained an image classification model using Teachable Machine, creating two classes:

Car Detected
No Car Detected

Exported the trained model as a TensorFlow.js model for use in our web-based camera interface.

Implemented camera input so the system could read real-time video from a webcam.

Integrated the machine-learning model into our project’s code so that the camera feed was continuously analyzed.

Helped my team test and optimized the model, adjusting confidence thresholds to reduce false positives and improve detection reliability.
