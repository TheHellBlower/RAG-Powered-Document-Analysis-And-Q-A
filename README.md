# PDF Document Analyzer (Q&A Chatbot & Summarizer)

This project is a Streamlit web application that allows you to upload a PDF document and interact with it in two ways:

1. **Chatbot (Q&A):** Ask specific questions about the document's content using Retrieval-Augmented Generation (RAG).

2. **Summarizer:** Generate a detailed, bullet-pointed summary of the entire document.

This application was developed by combining the two projects from an original Jupyter Notebook, converting the logic into a deployable app. It uses LangChain and leverages the free, open-source **Llama 3** model from Hugging Face for all language tasks, requiring no paid API keys.

## 🛠️ How to Run This App Locally

### 1. Prerequisites

* Python 3.8 - 3.11

* A free Hugging Face API Token (get one [here](https://huggingface.co/settings/tokens))

### 2. Get the Project Files

Clone this repository or download the files (`app.py`, `requirements.txt`, and your notebook) into a new folder on your computer.

### 3. Install Dependencies

It is highly recommended to use a Python virtual environment to avoid conflicts.

### 4. Run the Streamlit App

With your virtual environment still active, run the following command in your terminal:

### 5. Use the App

Your browser will automatically open to `http://localhost:8501`.

1. Paste your Hugging Face API Token (the one starting with `hf_...`) into the sidebar.

2. Upload your PDF file using the file uploader.

3. The app will process the file (you'll see spinners).

4. Once processed, you can use the **"Chatbot (Q&A)"** and **"Summarization"** tabs to interact with your document.

## 📁 Repository Files

* `app.py`: The main Python script for the Streamlit application.

* `requirements.txt`: A list of all Python libraries required to run the app.

* `README.md`: This file, explaining the project and how to run it.

* `[Your_Notebook_Name].ipynb`: The original Jupyter Notebook showing the step-by-step development and logic.
