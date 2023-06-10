# Azure-Voice-to-Text Documentation

## Introduction
Azure-Voice-to-Text is a project developed during a hackathon, utilizing Azure Cognitive Services. The project incorporates text-to-speech and text classification functionalities.

## Poharogapp
Poharogapp is a web application designed for medical consultations in hospitals, facilitating both in-person and virtual visits. This application enables recording and transcribing consultations into text format using Azure's text-to-speech service. The transcribed text is then passed through our API, which leverages an AI model trained with Azure's text classification capabilities.

## Technology Stack
The application is built using Flask, a Python web framework, which provides a lightweight and flexible foundation for web development.

## Key Features
1. Medical Consultation Recording: Poharogapp allows users to record medical consultations, capturing the audio content for future reference.
2. Transcription: Azure's text-to-speech service is utilized to convert the recorded audio into text, providing a textual representation of the consultation.
3. Text Classification: The transcribed text is processed using our API, which leverages an AI model trained with Azure's text classification capabilities. This enables categorization and analysis of the consultation content.

## Getting Started
To run the Azure-Voice-to-Text project locally, follow these steps:
1. Clone the repository from [GitHub link].
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Configure the Azure Cognitive Services credentials in the application to enable text-to-speech and text classification functionalities.
4. Launch the Flask application by executing `python app.py` in the project directory.
5. Access the Poharogapp web interface through your browser to begin using the application.

## Conclusion
Azure-Voice-to-Text, with its integration of Azure's text-to-speech and text classification services, provides a powerful solution for medical consultations. Poharogapp's ability to record, transcribe, and analyze consultations enhances the efficiency and effectiveness of healthcare professionals.
