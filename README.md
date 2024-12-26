# Zorro: Streamlit-Hosted RAG AI Chatbot  

Zorro is a Retrieval-Augmented Generation (RAG) AI chatbot designed for testing and fine-tuning chatbot interactions in a user-friendly Streamlit environment. This version includes both front-end and back-end functionality, making it an excellent tool for evaluating chatbot responses before integrating them into your official website frontend.  

## Key Features  

- **Language Model**: Utilizes Anthropic's Claude Haiku model for natural language processing and generation.  
- **Embedding Model**: Employs OpenAI's embedding model for creating high-dimensional vector representations of data.  
- **Data Parsing and Formatting**:  
  - Supports text-based data files such as JSON, CSV, Excel, Word, and PDF.  
  - Reformats files into a format compatible with the language model.  
- **Data Chunking and Storage**: Processes large datasets by chunking them and embedding the information into a vector database for efficient querying.  
- **Customizable Prompt**: The core prompt can be adapted to specific business needs, ensuring relevance across various applications.  
- **API Key Management**: Provides a dropdown section for entering Anthropic and OpenAI API keys directly within the Streamlit interface.  

## Requirements  

- **Anthropic API Key**: Required for accessing the Claude Haiku language model.  
- **OpenAI API Key**: Required for generating embeddings.  

## Usage Instructions  

1. Install the required dependencies using `pip install -r requirements.txt`.  
2. Launch the Streamlit app either using the Streamlit website or by running in terminal:  
   ```bash  
   streamlit run app.py  
   ```  
3. Use the dropdown menu in the app to input your Anthropic and OpenAI API keys.  
4. Add your data files to the `docs` folder in the project directory for parsing and embedding.  
5. Customize the prompt in the Streamlit app or code as needed to align with your business requirements.  

## Why Use Zorro on Streamlit?  

- **Testing Made Simple**: A quick and efficient way to test chatbot behavior in real-time without needing to deploy on a production frontend.  
- **Seamless Integration**: Easily transition to your website’s frontend once the chatbot is fine-tuned.  
- **User-Friendly Interface**: Streamlit provides an interactive UI for configuration, making it accessible for both developers and non-technical users.  

This Streamlit-hosted version of Zorro simplifies the process of testing and refining your chatbot, ensuring it's perfectly tailored to your needs before full deployment.  
