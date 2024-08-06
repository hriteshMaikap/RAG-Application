# RAG-Application

A Streamlit application for interacting with PDF documents using Retrieval-Augmented Generation (RAG). This app allows users to upload PDF documents and ask questions about their content, leveraging advanced language models to provide accurate and concise answers.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)

## Introduction

The RAG-Application is designed to simplify the process of interacting with PDF documents by allowing users to ask questions and receive relevant answers. This is achieved using a combination of PDF processing, document embedding, and a question-answering system powered by language models.

## Features

- Upload and process PDF documents
- Ask questions about the content of the uploaded PDFs
- Retrieve accurate and concise answers using advanced language models
- User-friendly interface built with Streamlit

## Installation

### Prerequisites

- Python 3.10
- Git
- Conda

### Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/YOUR_USERNAME/RAG-Application.git
   cd RAG-Application
2. **Create and activate a Conda environment:**
    ```sh
    conda create -p env python=3.10
    conda activate ./env
3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt

## Usage
1. **Run the application:**
    ```sh
    ./run.sh

## Project Structure
    ```sh
    RAG-Application/
    ├── app.py                   
    ├── rag.py                  
    ├── requirements.txt        
    ├── run.sh                  
    ├── README.md                
    └── .env.example             

## Acknowledgements
* Langchain for providing the foundational tools
* Streamlit for the easy-to-use web application framework
* The open-source community for continuous support and contributions


