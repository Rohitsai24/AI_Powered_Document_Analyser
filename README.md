AI Powered Document Analyzer
This repository contains a Streamlit application that utilizes AI models to extract and analyze text from PDF documents. The application allows users to upload PDF files, process them to extract text, and then query the content using natural language questions. 
The answers are generated based on the content extracted from the PDFs.The application is integrated using the ocr(Optical character recognition) which is used in detecting the text on the images of the pages in the pdfs.

Features
1.PDF Text Extraction: Extract text from PDF files, including text embedded in images using OCR (Optical Character Recognition).
2.Text Chunking: Split the extracted text into manageable chunks for processing.
3.Vector Store Creation: Generate vector embeddings for text chunks and store them using FAISS (Facebook AI Similarity Search).
4.Conversational AI: Answer user queries based on the context extracted from the uploaded PDFs using Google's Generative AI models.
5.Streamlit Interface: A user-friendly web interface to upload PDFs and ask questions.

Requirements
1.Python 3.8+
2.Streamlit
3.PyPDF2
4.Langchain
5.pytesseract
6.FAISS
7.dotenv

Setup
Prerequisites
Tesseract OCR: Install Tesseract OCR on your system. Follow the instructions on the official Tesseract GitHub for installation.
Google API Key: Obtain a Google API Key to use Google's Generative AI models. Set this key in your environment variables.
Intially we have to setup the google api key in the .env file so that it will be able to generate the content.Otherwise it will give key missing error.
