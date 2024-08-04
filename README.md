# Chatbot - Ask Me Anything 😬

This is a Streamlit-based chatbot application that allows users to interact with OpenAI's GPT-3.5 and GPT-4 models. The application supports conversation history, token usage tracking, and cost calculation for each conversation.

## Features

- Chat with OpenAI's GPT-3.5 or GPT-4 models.
- Track the total cost of each conversation.
- Clear conversation history.
- Dynamic model selection via sidebar.

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   cd <repository_directory>

2. Create and activate a virtual environment:
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`

3. Install the required packages

    pip install -r requirements.txt

4. Set up your OpenAI API key:
    export OPENAI_API_KEY='your-api-key'

5. Run the Streamlit application:
    streamlit run app.py

6. Running through Docker:

    If you have docker installed locally, just run below command:
        Add OPEN AI Key in cocker compose file
        docker build
        docker-compose

Access the application:

Open your web browser and navigate to http://localhost:8501 to interact with the chatbot.

