Local GPT App
This project is a local GPT app that uses Langchain and the OpenAI API for the backend and Streamlit for the frontend.

 Features

 - Generate text, translate languages, write different kinds of creative content, and answer your questions in an informative way.
 - Use a variety of prompts and settings to customize the output of the GPT model.
 - Use memory to save and load your work to continue where you left off.

Getting Started

1. Clone the repository to your local machine.

2. Install the required libraries

3. Create a file called `apikey.py` and add your OpenAI API key to it.

OPENAI_API_KEY=YOUR_API_KEY


4. Run the app:

streamlit run app.py

Usage
The app is divided into two main sections: the prompt section and the output section.

In the prompt section, you can enter a prompt for the GPT model. You can also specify a variety of settings, such as the maximum length of the output, the temperature, and the randomness.
In the output section, you will see the generated text. You can also save the output to a file or load a previously saved file.
Credits
This project uses the following open source libraries:

Langchain
OpenAI API
Streamlit

