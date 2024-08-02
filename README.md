# Inquistive-Streamlit-app

Inquisitive Input Screen

![user_input](https://github.com/user-attachments/assets/db1a6f75-18e7-424e-9515-c4a3066208fa)

Inquisitive Response Screen

![output](https://github.com/user-attachments/assets/950ad648-185e-4a2e-b383-baa2e8495377)

Overview

Inquisitive is a Streamlit application designed to facilitate question generation using Google Generative AI and language detection. It serves as a valuable tool for educators, content creators, and anyone seeking to enrich text content with relevant questions.

Features

Language Detection: Automatically identifies the language of input text.
Text Translation: Translates non-English text into English for processing.
Question Generation: Utilizes Google Generative AI to create questions based on the input text.
Multi-Language Support: Ensures generated questions can be translated back to the original language.
Installation

To run this project locally, follow these steps:

Prerequisites

Make sure you have the following installed:

Python 3.8 or higher
Git
Clone the Repository

git clone https://github.com/NaveenDeveloperR/inquisitive-streamlit-app.git
cd inquisitive-streamlit-app
Set Up the Virtual Environment

It's recommended to use a virtual environment to manage dependencies. Run the following commands:

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies

Install the required Python packages using pip:

pip install -r requirements.txt
Usage

To launch the Inquisitive Streamlit app, execute the following command:

streamlit run app.py
Configuration

Before running the app, ensure you have your Google Generative AI API key ready. Configure the API key in your app.py file:

palm.configure(api_key="YOUR_API_KEY_HERE")
File Structure

Here's the basic structure of the project directory:

inquisitive-streamlit-app/
├── app.py
├── requirements.txt
├── README.md
└── images/
    ├── user_input.png
    └── output.png
Contributing

We welcome contributions to enhance the Inquisitive app. To contribute, follow these steps:

Fork the repository on GitHub.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request on GitHub.
License

This project is licensed under the MIT License.
