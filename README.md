# ChatGPT Clone with Django

This project is a ChatGPT clone using Django, where users can interact with a chatbot powered by the OpenAI GPT-3.5 Turbo model.

## Prerequisites

Before running the project, make sure you have the following installed:

- Python (>=3.6)
- Django
- OpenAI Python Library

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/LakshithaR/ChatGPT_Clone_with_Django.git
    ```

2. Navigate to the project directory:

    ```bash
    cd chatgpt-django-clone
    ```

3. Install the dependencies:

    ```bash
    pip install python
    pip install django
    pip install openai
    ```

4. Configure OpenAI API Key:

    Get your OpenAI API key from [OpenAI](https://beta.openai.com/signup/) and set it in the Django project settings.

5. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Visit `http://127.0.0.1:8000/` in your web browser to interact with the ChatGPT clone.

## Usage

1. Access the chatbot interface through the web browser.

2. Type a message in the input box and press Enter.

3. The chatbot will generate a response using the OpenAI GPT-3.5 Turbo model.

4. Interact with the chatbot by sending more messages.

## Customization

You can customize the chatbot behavior by modifying the `ask_openai` function in the `views.py` file.

