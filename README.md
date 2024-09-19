# LangChain - Chat with Search

This project demonstrates how to create a chatbot using LangChain that can search the web, as well as query research papers from Arxiv and information from Wikipedia. The chatbot is deployed using Streamlit for an interactive user interface. The chatbot is capable of responding to user queries by searching the web using DuckDuckGo, querying Arxiv for scientific papers, and using Wikipedia to provide concise information.

**Project Link:** https://chatwithsearch.streamlit.app/

## Features
- **Real-time Chatbot:** The chatbot responds to queries interactively using LangChain's capabilities.
- **Multiple Tools Integration:**
  - **DuckDuckGo Search:** The bot uses DuckDuckGo for web searches.
  - **Arxiv Research Papers:** It can query research papers on Arxiv.
  - **Wikipedia Queries:** Information retrieval from Wikipedia.
- **Streamlit Frontend:** The chatbot is deployed using Streamlit, providing a simple yet powerful user interface for interaction.
- **Customizable LLM Model:** The bot is powered by Llama3-8b-8192 from Groq's API.

### How It Works

- **LangChain Integration:** LangChain is used to manage the LLM (Language Learning Model) and integrate with the external APIs for search and research paper retrieval.
- **Agent Initialization:** The chatbot is powered by LangChain agents that leverage multiple tools like DuckDuckGo search, ArxivAPI, and WikipediaAPI to answer queries.
- **Streamlit:** The project uses Streamlit to display the thoughts and actions of the chatbot and allows for a dynamic interface.

## Code Structure
- **app.py:** The main file that runs the chatbot using Streamlit.
- **LangChain Tools:** The Arxiv, Wikipedia, and DuckDuckGo integrations are handled using the LangChain library.
- **Streamlit Callback Handler:** The StreamlitCallbackHandler is used to display the chatbot's thoughts and actions in real time.


## Snaps of the project
![Screenshot (4655)](https://github.com/user-attachments/assets/6cfa6297-2b7c-43f4-801b-12a6f8ad6bc8)

![Screenshot (4656)](https://github.com/user-attachments/assets/a2786584-bf6c-487a-b19c-13105b2aa58a)

