#  Arabic OCR Tool: PDF to Text with LightOnOCR

Welcome! This project is a simple yet powerful tool designed to solve a common headache: **extracting high-quality text from Arabic PDFs.** Whether you have scanned documents, historical texts, or modern PDF reports, this tool leverages the state-of-the-art **LightOnOCR-2-1B** model to convert images and PDF pages into editable, searchable text. 

Built with  using Hugging Face Transformers and Gradio.

##  Features
* **High Accuracy:** Powered by LightOnAI's specialized OCR model for complex layouts and languages.
* **PDF Support:** Automatically splits multi-page PDFs into images for processing.
* **User-Friendly UI:** A clean, browser-based interface—no coding required to use once it's running.
* **Batch Export:** View the text in your browser and download the full result as a `.txt` file instantly.

##  How It Works
The pipeline is straightforward:
1.  **Convert:** It uses `pdf2image` to turn each PDF page into a high-resolution image.
2.  **Process:** The LightOnOCR model analyzes the visual tokens to understand the text.
3.  **Generate:** It "writes" the text out, page by page, preserving the document flow.

##  Setup & Installation

To run this locally or in Google Colab, you'll need a few dependencies.

### 1. System Requirements
You will need `poppler-utils` installed on your system to handle PDF conversions:
* **Linux:** `sudo apt-get install poppler-utils`
* **Mac:** `brew install poppler`


### 2.ui
<img width="1280" height="571" alt="image" src="https://github.com/user-attachments/assets/7750286b-d4d1-468b-be4b-f784538eedf6" />









