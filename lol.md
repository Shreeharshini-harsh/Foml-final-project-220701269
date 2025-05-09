# MediBot - AI Chatbot for Drug, Disease Information, and Diagnosis Support

MediBot is an AI-powered chatbot that provides real-time drug and disease information, diagnosis support, disease prevention education, and patient triage based on symptoms. It's designed to assist healthcare professionals, patients, and researchers by delivering accurate and comprehensive medical data.

## Features

- **Diagnosis Support**: Offers potential diagnoses based on user-provided symptoms.
- **Disease Prevention Education**: Provides prevention tips for various diseases.
- **Patient Triage**: Assists in determining the severity of symptoms and suggests appropriate actions.

## Technologies Used

- **Streamlit**: For building the web app interface.
- **OpenAI API**: For generating natural language responses.
- **Python**: The language powering the app.

## Prerequisites

- Python 3.x
- OpenAI API key
- DrugBank API key (optional)

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/medibot.git
    cd medibot
    ```

2. **Create a virtual environment** (optional but recommended):

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:

    Run the following command to install dependencies from the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up API keys**:

    You need an OpenAI API key to use the chatbot. Set the API key as an environment variable:
    
    ```bash
    export OPENAI_API_KEY='your-openai-api-key'
    ```

    For Windows:

    ```bash
    set OPENAI_API_KEY='your-openai-api-key'
    ```

    Optionally, set the DrugBank API key:

    ```bash
    export DRUGBANK_API_KEY='your-drugbank-api-key'
    ```

## Running the Application

Once you have installed the dependencies and set up your API keys, run the application using Streamlit:

```bash
streamlit run app.py
