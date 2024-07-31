## Conversate with PDF using ChatGPT, Langchain, Embedding

This project creates a conversational interface for PDFs. It uses ChatGPT to understand user questions and Langchain to bridge the gap between ChatGPT and the PDF data. Embeddings convert PDF text into a format ChatGPT can understand, while ChromaDB stores these embeddings efficiently. This allows users to ask questions about PDFs in natural language and get answers directly from the document.


### How to run it on your own machine

1. Create the secrets.toml file:

Create the .streamlit folder in the root directory of your project.
File name: The file must be named exactly secrets.toml (with the leading dot).
Contents: The file uses the TOML format.  Here's an example:

GOOGLE_API_KEY="your_actual_api_key_here"
Replace "your_actual_api_key_here" with your real API key. You can add other secrets in a similar way.

2. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

3. Run the app

   ```
   $ streamlit run app.py
   ```

