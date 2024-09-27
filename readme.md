# PDF Question Answering with Speech Conversion

## Overview
This project implements a RAG (Retrieval-Augmented Generation) system that allows users to upload a PDF file, extract text from it, and ask questions about the content. The answers can be converted to speech using the Sarvam API. The project utilizes the Langchain framework, PyMuPDF for PDF processing, and Streamlit for the user interface.

## Features
- **PDF Text Extraction**: Extract text from PDF files using PyMuPDF.
- **Question Answering**: Ask questions about the extracted content using an LLM (GPT-3.5).
- **Speech Conversion**: Convert the generated answers to speech using the Sarvam API.
- **User Interface**: Interactive web interface built with Streamlit for a seamless user experience.

## Technologies Used
- **Python**: Programming language for implementation.
- **Streamlit**: Framework for building the web application.
- **PyMuPDF**: Library for extracting text from PDF files.
- **Langchain**: For building the RAG system and integrating the LLM.
- **Sarvam API**: For converting text responses to speech.
- **OpenAI**: For accessing the GPT-3.5 model.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
