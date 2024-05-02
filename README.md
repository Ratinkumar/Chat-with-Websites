# Chat-with-Websites
<p>This project is basically to build a chatbot capable of interacting with websites,extracting information, and
communicating in user-friendly manner.It leverages the power of LangChain and integrates it with a Streamlit GUI
for an enhanced user experience.</p>

● The chatbot uses the latest version of LangChain to interact with and extract information from various websites.

● Compatibility with models like GPT-4,Mistral,Llama2 and ollama.In this code I have used GPT-4.

● A clean and intuitive user interface built with Streamlit.

● Entirely coded in Python.

# Brief explanation of how RAG works

A RAG bot is short for Retrieval-Augmented Generation. This means that we are going to "augment" the knowledge of our LLM with new information that we are going to pass in our prompt. We first vectorize all the text that we want to use as "augmented knowledge" and then look through the vectorized text to find the most similar text to our prompt. We then pass this text to our LLM as a prefix.

<img src="Docs/HTML-rag-diagram.jpg">

# Reqrirements

langchain==0.1.4

langchain_community==0.0.16

langchain_core==0.1.17

langchain_openai==0.0.5

python-dotenv==1.0.1

streamlit==1.30.0

chromadb==0.3.29

beautifulsoup4==4.12.2

# Create your own .env file with the following variables:

OPENAI_API_KEY=[your-openai-api-key]
