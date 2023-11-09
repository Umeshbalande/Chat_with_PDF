
# Chat with PDFs : using Langchain and streamlit
ANY TextBOOK ( for E.g: CBSE class 6 science Textbook)

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgments](#acknowledgments)

## Introduction

This project allows users to interact with a chatbot that can answer questions based on the content of uploaded PDF documents. It uses Streamlit for the web interface, PyPDF2 for PDF text extraction, and various machine learning models for natural language understanding and retrieval.

## Features

- Upload multiple PDFs
- Real-time chat interface
- Text-based search and retrieval from PDFs
- Powered by advanced NLP models

## Prerequisites

- Python 3.x
- Streamlit
- PyPDF2
- FAISS
- OpenAI or HuggingFace models

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/your-username/Chat-with-PDFs.git
    ```

2. Navigate to the project directory:
    ```
    cd Chat-with-PDFs
    ```

3. Install the required packages:
    ```
    pip install -r requirements.txt
    ```
  ## Output i.e. Interface in streamlit  
![Interface](https://github.com/Umeshbalande/Chat_with_PDF/assets/3708552/5435cca9-73d9-4683-8c05-ae7fbe4b4240)

## Usage

1. Run the Streamlit app:
    ```
    streamlit run app.py
    ```

2. Open the app in your web browser and upload your PDFs.
3. Ask questions in the chat interface.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to OpenAI and HuggingFace for their incredible NLP models.
- Thanks to Streamlit for their easy-to-use web framework.

---

Feel free to customize this README to better suit your project's specific needs.
