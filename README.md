# Personalized Health and Fitness Advisor

## Introduction
This Streamlit application offers tailored health and fitness advice using advanced NLP and AI models. It leverages the OpenAI API and other machine learning techniques to generate personalized fitness plans, dietary recommendations, and health strategies based on user-specific data.

## Features
- **Personalized Fitness Plans**: Generate custom workout routines and dietary plans.
- **Integration with AI Models**: Uses Sentence Transformers and Faiss for NLP tasks and efficient similarity search.
- **Interactive UI**: Engage users with an interactive web interface to input their data and receive instant health advice.

## Getting Started

### Prerequisites
- Python 3.8+
- Pip
- Virtual environment (recommended)

### Installation

1. **Clone the Repository**
   git clone https://github.com/mustafashahzadd/fitnesspro1
   cd fitnesspro1

2. **Set up a Virtual Environment (Optional but recommended)**
   python -m venv venv
   .\venv\Scripts\activate

3. **Install Requirements**
   pip install -r requirements.txt

4. **Configuration**
Create a .env file in the root directory of the project and add the following environment variable:

 AIML_API_KEY='your_openai_api_key_here'
Note: The .env file is not tracked by git as specified in the .gitignore to keep sensitive data such as API keys private.

5. **Running the Application**
To run the app, execute the following command:
    streamlit run streamlit_app.py

6. **Usage**
Upon launching, navigate through the sidebar to select different models for tailored fitness advice. Input your personal health data such as height, weight, age, and specific goals. The app will interact with AI models to generate personalized advice that you can follow.


Please ensure to update tests as appropriate.

7. **License**
    MIT
   




