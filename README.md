# 🛡️AI Shredder & Redaction Tool

## Overview
The **AI Shredder & Redaction Tool** is an AI-powered application designed to automatically detect, redact, and anonymize sensitive information from documents and images. It provides a secure and efficient solution for privacy compliance, sensitive data protection, and document management.

This tool is particularly useful for organizations handling confidential data such as legal documents, financial records, medical reports, and scanned images.  

---

## Features
- **Automatic Redaction**: Detects sensitive text and images to redact using AI-based models.
- **Supports Multiple Formats**: Works on PDFs, images (JPEG, PNG), and scanned documents.
- **Customizable Rules**: Users can define which types of information to redact (e.g., names, addresses, IDs).
- **Batch Processing**: Redact multiple documents/images at once.
- **Preview Before Redaction**: Allows users to review detected sensitive areas before final processing.

---

## Technology Stack
- **Python 3.11+**
- **Libraries Used**:
  - `PyTorch`: For AI model development.
  - `transformers`: NLP model handling for sensitive text detection.
  - `PIL (Pillow)`: Image processing.
  - `opencv-python`: Image and PDF processing.
  - `json`: Storing and exporting metadata.
  - `dataclasses`: Handling structured data for detected information.
- **Machine Learning Models**:
  - Pretrained OCR models for text extraction.
  - Custom-trained models for detecting sensitive data patterns.

---

## Installation

**1. Clone the repository:**<br>
  bash ```
    git clone https://github.com/prachishende007/AI_Shredder_and_Redaction_Tool.git
    cd ai-shredder-redactor
     ```

**2. Create a virtual environment:**<br>
python -m venv venv


**3.Activate the virtual environment:**<br>
- Windows:
    <br>venv\Scripts\activate
- Linux/MacOS:
   <br>pip install -r requirements.txt
  
**4.Install dependencies:**<br>
pip install -r requirements.txt

---

## Project Structure
  AI_Shredder_and_Redaction_Tool/<br>
  │<br>
  ├── input/              <br>
  ├── output/             <br>
  ├── models/             <br>
  ├── scripts/            <br>
  ├── main.py             <br>
  ├── requirements.txt    <br>
  ├── README.md           <br>
  └── config.json         <br>

---

## Results

- Successfully redacts sensitive information like names, phone numbers, emails, and SSNs.
- Maintains original document structure and readability.
- Batch processing reduces manual effort significantly.
- Preview mode ensures accurate redaction before saving final files.

---

## Future Improvements

- Integration with web and desktop GUI applications.
- Support for more languages in text detection.
- AI-based image obfuscation techniques for better security.
- Cloud-based deployment for large-scale document management.

---

## Contact

**Project Lead: Prachi Shende**<br>
Email: prachishende182@gmail.com<br>
GitHub: https://github.com/prachishende007

---
