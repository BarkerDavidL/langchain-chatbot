# langchain-chatbot
Simple chatbot using langchain. This code loads an article from the web and allows a query on the contents.

Followed the tutorials from here:
* https://python.langchain.com/docs/tutorials/llm_chain/
* https://python.langchain.com/docs/tutorials/rag/

Add your OpenAI and LangSmith API keys to the .env file.

To run in Windows CMD shell:

* python -m venv venv
* venv\Scripts\activate.bat
* pip install -r requirements.txt
* python langchain-chatbot.py

To run in a Codespace (Linux):

* python -m venv venv
* source venv/bin/activate
* pip install -r requirements.txt
* python langchain-chatbot.py
