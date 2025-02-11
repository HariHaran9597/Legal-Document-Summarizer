<<<<<<< HEAD
# Legal Document Summarizer

An AI-powered legal document summarization system that uses Large Language Models to generate concise summaries of legal documents while retaining key information.

## Features

- Multi-format document support (PDF, DOCX, TXT)
- Intelligent preprocessing of legal texts
- LLM-powered summarization using Google's Gemini Pro model
- Clean and intuitive web interface
- Preservation of key legal terms and clauses
- Configurable summary length

## Installation

1. Clone this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Create a `.env` file and add your Google API key:
```
GOOGLE_API_KEY=your-gemini-api-key-here
```

## Usage

1. Start the web interface:
```bash
streamlit run src/app.py
```

2. Upload your legal document (PDF, DOCX, or TXT format)
3. The system will process the document and generate a concise summary
4. View both the summary and the original text

## Technical Details

The system uses a pipeline architecture:
1. Document Processing: Handles multiple file formats and extracts text
2. Text Preprocessing: Cleans and structures the legal text
3. LLM Integration: Uses Google's Gemini Pro model for intelligent summarization
4. Web Interface: Streamlit-based UI for easy interaction

## Skills Demonstrated

- Natural Language Processing (NLP)
- Large Language Model (LLM) Integration
- API Integration (Google Gemini)
- Document Processing
- Text Analysis
- Web Application Development
- Software Architecture Design
- Error Handling and Input Validation
- Testing and Quality Assurance

## Testing

Run the unit tests:
```bash
python -m unittest tests/test_summarizer.py
=======
# Legal-Document-Summarizer
An AI-powered legal document summarization system that uses Large Language Models to generate concise summaries of legal documents while retaining key information.
>>>>>>> 4f8ff3d49e1c704644c7f9aa0a3e32d6344fc9b0
