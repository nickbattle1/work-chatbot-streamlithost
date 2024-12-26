# Streamlit-Hosted RAG AI Chatbot  

Zorro is a Retrieval-Augmented Generation (RAG) AI chatbot designed for testing and fine-tuning chatbot interactions in a user-friendly Streamlit environment. This version includes both front-end and back-end functionality, making it an excellent tool for evaluating chatbot responses before integrating them into your official website frontend.  

## Key Features  

- **Language Model**: Utilizes Anthropic's Claude Haiku model for natural language processing and generation.  
- **Embedding Model**: Employs OpenAI's embedding model for creating high-dimensional vector representations of data.  
- **Data Parsing and Formatting**:  
    - Supports text-based data files such as JSON, CSV, Excel, Word, and PDF.  
    - Reformats files into a format compatible with the language model.  
- **Data Chunking and Storage**: Processes large datasets by chunking them and embedding the information into a vector database for efficient querying.  
- **Document Upload**: Streamlit app includes a dialogue box to upload your data files directly—no need to edit the code.  
- **Customizable Prompt**: The core prompt is located in the `rag_methods.py` file and can be easily modified to suit your business or application needs **before** deploying the app.  
- **API Key Management**: The app provides a dropdown section for entering your Anthropic and OpenAI API keys directly within the Streamlit interface.  

## Requirements  

- **Anthropic API Key**: Required for accessing the Claude Haiku language model.  
- **OpenAI API Key**: Required for generating embeddings.  

## Usage Instructions  

1. **Install Required Libraries**:  
   Install the necessary dependencies using:  
   ```bash  
   pip install -r requirements.txt  
   ```  

2. **Customize the Prompt**:  
   - Modify the core prompt in the `rag_methods.py` file to match your specific business requirements **before** deploying the app.  

3. **Deploying via Streamlit Website**:  
   - You can link this repository to a new app directly from the Streamlit website. Create an app on Streamlit’s platform, link it to the GitHub repository, and deploy it with ease.  

4. **Launch the Streamlit App**:  
   Alternatively, to run the app locally, use the following command in the terminal:  
   ```bash  
   streamlit run app.py  
   ```  

5. **API Key Input**:  
   - Use the dropdown menu in the app to input your Anthropic and OpenAI API keys.  

6. **Document Upload**:  
   - Upload your data files directly through the Streamlit app's dialogue box for parsing and embedding—no need to modify the code.  

## Why Use Zorro on Streamlit?  

- **Testing Made Simple**: Quickly test chatbot behavior in real-time without deploying on a production frontend.  
- **Seamless Integration**: Easily transition to your website’s frontend once the chatbot is fine-tuned.  
- **User-Friendly Interface**: Streamlit offers an interactive UI for configuration, making it accessible for both developers and non-technical users.  

This Streamlit-hosted version of Zorro simplifies testing and refining your chatbot, ensuring it’s perfectly tailored to your needs before full deployment.
