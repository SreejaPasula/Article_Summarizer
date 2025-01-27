# Article Summarization Tool

This is a **Streamlit application** designed to summarize articles, newspapers, research papers, and other text-based content. The app includes **user authentication (Signup/Login)** and processes articles via URL input. It extracts the text and generates concise summaries, making it an efficient tool for summarizing lengthy articles and documents.

## Features

- **User Authentication**: 
  - Signup and login functionality for secure access.
- **Content Summarization**:
  - Summarizes articles, newspapers, research papers, and plain text.
  - Automatically extracts content from URLs.
- **Text Extraction**:
  - Processes and extracts text from online articles (via URLs).
  - Supports research paper text extraction (PDF links included).
- **Interactive UI**:
  - Clean, responsive interface built using Streamlit.

## Prerequisites

- Python 3.7 or above
- Required Python Libraries:
  - `streamlit` (for the app framework)
  - `newspaper3k` (for article processing)
  - `requests` (for making HTTP requests)
  - `nltk` (for Natural Language Processing tasks)
  - `PyMuPDF` (for PDF text extraction)

You can install the required libraries using pip:

```bash
pip install streamlit newspaper3k requests nltk PyMuPDF
```

Alternatively, install all dependencies from the `requirements.txt` file.

## How to Run the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/article-summarization-tool.git
   cd article-summarization-tool
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run streamlit_app.py
   ```

4. Open the provided local URL in your browser to use the app.

---
