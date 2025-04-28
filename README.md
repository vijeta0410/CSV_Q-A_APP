Problem statement:

You are tasked with building a lightweight AI agent that can intelligently answer basic questions from a simple CSV file containing customer purchase data or any client data.
The agent should be able to:
Parse the CSV file.
Understand simple user queries in natural language.
Perform appropriate data lookups and respond with correct answers

Approach:
Get CSV data as input and using Grok anwering the queries asked by the user.
Implemented a Streamlit UI application to upload the CSV data 
Used deepseek-r1-distill-llama-70b model

Libraries used:
pandas 
pandasai
matplotlib
seaborn
streamlit
langchain-groq

TO run the code:
pip install -r requirements.txt
cd app
streamlit run app.py


