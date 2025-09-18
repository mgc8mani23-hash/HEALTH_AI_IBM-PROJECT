Project

* Team ID : NM2025TMID02150
* Team Leader : MANI BHARATHI A A
* Team member : MUGUNDAN M 
* Team member : NANDHAKUMAR B
* Team member : MAHESH KUMAR S
  
Overview
Healthcare AI Intelligent Assistance is a project developed under the Naan Mudhalvan scheme, a flagship skill development initiative by the Government of Tamil Nadu. 
The project aims to create an AI-powered assistant for the healthcare sector.
It focuses on using artificial intelligence to provide general medical information, predict potential diseases based on symptoms, and suggest treatment plans. The goal is to leverage AI to assist both healthcare professionals and the general public, while always emphasizing the importance of professional medical consultation.

🚀 Features
Symptom-based Disease Prediction: The core feature is an AI model that analyzes user-provided symptoms and predicts a list of possible medical conditions. 🩺
Personalized Treatment Suggestions: The system generates general and personalized treatment plans, including home remedies and medication guidelines, based on the user's condition and other parameters like age, gender, and medical history. 💊
Informational Disclaimer: A critical feature is the prominent display of a disclaimer on all outputs, strongly advising users to consult a qualified healthcare professional. This ensures the responsible use of the AI assistant. ⚠️
Intuitive UI: An easy-to-use web interface built with Gradio allows for simple user interaction and a clear display of the generated information. 💻
🛠️ Tech Stack
Language: Python is the primary programming language for the entire application.
AI/ML Frameworks: The project leverages the Hugging Face Transformers library for its core functionality. It specifically uses the IBM Granite 3.2-2B-Instruct large language model.
Backend: The model inference and logic are handled by the Python script, acting as a backend server.
Frontend: The user interface is built using Gradio, which allows for rapid prototyping and deployment of machine learning models.
Dependencies: Key libraries include torch, transformers, and gradio.
📂 Project Structure
This project is contained within a single directory and a single Python file, simplifying its structure and execution.
healthcare_ai_assistant.py: This is the main and only file. It contains all the necessary code for:
Importing libraries (gradio, torch, transformers).
Loading the pre-trained language model and tokenizer.
Defining the core functions for disease prediction and treatment plan generation.
Creating and launching the Gradio web interface.
README.md: A file that provides a brief overview, setup instructions, and how to run the application.
Demo Video
Watch our project demo here: Click to Watch

⚡ How to Run
Clone the repository:
git clone https://github.com/venkattweb/SmartSDLC-IBM-Project.git# HEALTH_AI_IBM-PROJECT
