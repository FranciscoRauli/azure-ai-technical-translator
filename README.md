# Azure AI Technical Document Translator

AI-powered solution for translating technical documents and articles using Microsoft Azure AI Services.

This project was developed to automate multilingual translation of technical content, improving accessibility and knowledge sharing across different languages using Azure AI capabilities.

---

## Overview

Technical documentation is often available only in English, creating barriers for non-English speakers in technology environments.

This solution uses Azure AI Translator Services combined with Python to process and translate technical content efficiently and at scale.

---

## Features

- Technical document translation
- Azure AI Translator integration
- Automated text processing
- Multilingual support
- Scalable cloud-based architecture
- REST API integration

---

## Tech Stack

- Python
- Microsoft Azure AI Services
- Azure Translator
- REST APIs
- JSON
- NLP (Natural Language Processing)

---

## Architecture

```text
User Input
     ↓
Python Application
     ↓
Azure AI Translator Service
     ↓
Processed Translation Output
```

---

## Business Use Case

This solution can support companies and teams that need to:

- Translate technical documentation
- Localize knowledge bases
- Improve access to technical learning materials
- Automate multilingual communication workflows
- Scale document translation processes

---

## Project Structure

```text
├── src/
├── docs/
├── assets/
├── requirements.txt
├── README.md
└── main.py
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/FranciscoRauli/azure-ai-technical-translator.git
```

Access the project folder:

```bash
cd azure-ai-technical-translator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Azure Configuration

Create an Azure AI Translator resource and configure your credentials:

```python
TRANSLATOR_KEY=your_key
TRANSLATOR_ENDPOINT=your_endpoint
```

---

## Running the Project

```bash
python main.py
```

---

## Future Improvements

- PDF and DOCX support
- Web interface with Streamlit or FastAPI
- Azure cloud deployment
- Batch document processing
- Translation history
- AI-powered text summarization

---

## Screenshots

_Add project screenshots here._

Example:
- Input document
- Translation output
- Azure integration workflow

---

## Author

Francisco Raule

Data & Analytics Engineer specialized in Microsoft Data Stack solutions.

- Microsoft Fabric
- Azure
- Power BI
- SQL
- Python

LinkedIn:
https://linkedin.com/in/franciscoraule

GitHub:
https://github.com/FranciscoRauli

---

## License

This project is licensed under the MIT License.
