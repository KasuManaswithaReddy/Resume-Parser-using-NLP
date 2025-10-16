Resume Parser using NLP

An intelligent resume parsing system that leverages Natural Language Processing (NLP) to automatically extract and structure key information from resumes. This tool streamlines the recruitment process by converting unstructured resume data into organized, actionable insights.

## 🌟 Features

•⁠  ⁠*Automated Information Extraction*: Extracts essential details including:
  - Contact Information (Name, Email, Phone Number)
  - Educational Background
  - Work Experience
  - Technical Skills
  - Certifications
  - Projects

•⁠  ⁠*Multiple Format Support*: Handles various resume formats (PDF, DOCX, TXT)
•⁠  ⁠*NLP-Powered Analysis*: Uses advanced NLP libraries for accurate text processing
•⁠  ⁠*Structured Output*: Converts extracted data into JSON format for easy integration
•⁠  ⁠*Skills Matching*: Identifies and categorizes technical and soft skills
•⁠  ⁠*Pattern Recognition*: Uses regex and NLP techniques for reliable data extraction

## 🛠️ Technologies Used

•⁠  ⁠*Python 3.x*
•⁠  ⁠*NLP Libraries*:
  - spaCy - For advanced natural language processing
  - NLTK - For text processing and tokenization
•⁠  ⁠*PDF Processing*:
  - PyPDF2 / pdfplumber - For PDF text extraction
•⁠  ⁠*Document Processing*:
  - python-docx - For DOCX file handling
•⁠  ⁠*Regular Expressions* - For pattern matching
•⁠  ⁠*Pandas* - For data manipulation

Performance

•⁠  ⁠*Accuracy*: ~85-90% for well-formatted resumes
•⁠  ⁠*Processing Time*: ~2-5 seconds per resume
•⁠  ⁠*Supported Formats*: PDF, DOCX, TXT

 
## 🚀 Installation

1.⁠ ⁠Clone the repository:
⁠ bash
git clone https://github.com/KasuManaswithaReddy/Resume-Parser-using-NLP.git
cd Resume-Parser-using-NLP
 ⁠

2.⁠ ⁠Install required dependencies:
⁠ bash
pip install -r requirements.txt
 ⁠

3.⁠ ⁠Download spaCy language model:
⁠ bash
python -m spacy download en_core_web_sm
 ⁠
## 🏗️ Project Structure


Resume-Parser-using-NLP/
│
├── data/                    # Sample resumes and datasets
├── models/                  # Trained models (if any)
├── src/                     # Source code
│   ├── parser.py           # Main parser logic
│   ├── extractors.py       # Information extraction modules
│   └── utils.py            # Utility functions
├── notebooks/              # Jupyter notebooks for testing
├── requirements.txt        # Project dependencies
├── README.md              # Project documentation
└── LICENSE                # License file

## 📧 Contact

For questions or suggestions, please open an issue in the repository.
