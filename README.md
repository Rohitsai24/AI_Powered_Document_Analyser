# AI Powered Document Analyser

Welcome to the AI Powered Document Analyser repository! This Streamlit application leverages cutting-edge AI models to extract and analyze text from PDF documents. With this tool, users can upload PDF files, process them to extract text, and query the content using natural language questions. The answers are generated based on the content extracted from the PDFs, utilizing Optical Character Recognition (OCR) for text detection in images embedded within the PDFs.

## ✨ Features

1. **PDF Text Extraction**: Extract text from PDF files, including text embedded in images using OCR.
2. **Text Chunking**: Split the extracted text into manageable chunks for processing.
3. **Vector Store Creation**: Generate vector embeddings for text chunks and store them using FAISS (Facebook AI Similarity Search).
4. **Conversational AI**: Answer user queries based on the context extracted from the uploaded PDFs using Google's Generative AI models.
5. **Streamlit Interface**: A user-friendly web interface to upload PDFs and ask questions.

## 🛠 Requirements

- Python 3.8+
- Streamlit
- PyPDF2
- Langchain
- pytesseract
- FAISS
- dotenv

## ⚙️ Setup

### Prerequisites

1. **Tesseract OCR**: Install Tesseract OCR on your system. Follow the instructions on the [official Tesseract GitHub](https://github.com/tesseract-ocr/tesseract) for installation.
2. **Google API Key**: Obtain a Google API Key to use Google's Generative AI models. Set this key in your environment variables.

### Installation Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repo/ai-powered-document-analyser.git
    cd ai-powered-document-analyser
    ```

2. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up the environment variables**:
    Create a `.env` file in the root directory of the project and add your Google API Key:
    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

4. **Run the Streamlit application**:
    ```bash
    streamlit run app.py
    ```

## 🚀 Usage

1. Open the Streamlit application in your browser.
2. Upload a PDF file through the interface.
3. Ask questions related to the content of the PDF.
4. Receive answers generated based on the extracted text from the PDF.

## 🤝 Contributions

We welcome contributions! Please fork the repository and submit a pull request for any enhancements, bug fixes, or new features.

