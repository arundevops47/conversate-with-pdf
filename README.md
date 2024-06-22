## Conversate with PDF using ChatGPT, Langchain, Embedding

This project creates a conversational interface for PDFs. It uses ChatGPT to understand user questions and Langchain to bridge the gap between ChatGPT and the PDF data. Embeddings convert PDF text into a format ChatGPT can understand, while ChromaDB stores these embeddings efficiently. This allows users to ask questions about PDFs in natural language and get answers directly from the document.


### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run app.py
   ```
