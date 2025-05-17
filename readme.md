# Create chatbot with Groq api

In this repo, I created chatbot using groq api helps to interact with open source llms. I used llama3 as open source llm.

# Stack

1. Python = 3.12
2. streamlit = 1.41.1
3. open source llm model = llama-3.3-70b-versatile

# How to use

1. First of all, needs to have conda (Anaconda) -package as an env management tool.
2. Once conda is installed create new virtual env using command conda create -n {env_name} python={python_version} e.g. conda create -n venv python=3.12
3. Activate conda env using command conda activate {env}
4. Create .env file as per sample env .For this you will need to create groq api.
5. Install packges using command pip install -r src/requirements.txt
6. Run application using command streamlit run app.py

# Demo
https://basic-llama3-chatbot.streamlit.app/
