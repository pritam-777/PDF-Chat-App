# PDF-Chat-App

# Langchain Ask PDF 

**SCRENCAST CODEBASE ViDEO**:

**APP DEMO**:





https://github.com/pritam-777/PDF-Chat-App/assets/52121048/f90ebd55-d789-4e97-8dd7-dcbbeae8db70


**APPLICATION URL**:https://pdf-chat-app-8wqfnrlw3raclwwuzkcv2w.streamlit.app/


This is a Python application that allows you to load a PDF and ask questions about it using natural language. The application uses a LLM to generate a response about your PDF. The LLM will not answer questions unrelated to the document.

## How it works

The application reads the PDF and splits the text into smaller chunks that can be then fed into a LLM. It uses OpenAI embeddings to create vector representations of the chunks. The application then finds the chunks that are semantically similar to the question that the user asked and feeds those chunks to the LLM to generate a response.

The application uses Streamlit to create the GUI and Langchain to deal with the LLM.


## Installation

To install the repository, please clone this repository and install the requirements:

```
pip install -r requirements.txt
```

You will also need to add your OpenAI API key to the `.env` file.

## Usage

To use the application, run the `app.py` file with the streamlit CLI (after having installed streamlit): 

```
streamlit run app.py
```







#App URL : 
