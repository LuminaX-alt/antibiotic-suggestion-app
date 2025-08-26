# Antibiotic Treatment Recommendation System

An AI-powered system that analyzes patient lab reports, prescriptions, and clinical data to provide evidence-based antibiotic treatment recommendations following WHO guidelines.

## ⚠️ Important Medical Disclaimer

**THIS SYSTEM IS FOR EDUCATIONAL AND RESEARCH PURPOSES ONLY**

This software is designed to assist healthcare professionals and should NOT be used as a substitute for professional medical judgment. All recommendations must be reviewed and validated by qualified healthcare providers before implementation.

## Features

- **Document Processing**: Upload and analyze lab reports, prescriptions, and clinical notes
- **WHO Compliance**: Built-in WHO antibiotic guidelines and resistance patterns
- **Dosage Recommendations**: Evidence-based dosing with patient-specific adjustments
- **Safety Checks**: Drug interactions, contraindications, and allergy warnings
- **Audit Trail**: Comprehensive logging for medical decision tracking

## System Components

1. **Document Processing Pipeline**: OCR and NLP for medical document analysis
2. **Knowledge Base**: Comprehensive antibiotic database with WHO guidelines
3. **LLM Integration**: Specialized medical AI for treatment analysis
4. **Safety Engine**: Multi-layer validation and safety checks
5. **Web Interface**: User-friendly interface for healthcare professionals

## Technology Stack

- **Backend**: Python with FastAPI
- **Database**: PostgreSQL with medical data schemas
- **LLM**: OpenAI GPT-4 with medical fine-tuning
- **Document Processing**: Tesseract OCR, spaCy NLP
- **Frontend**: React with medical UI components
- **Security**: HIPAA-compliant data handling

## Quick Start

1. Clone the repository
2. Set up virtual environment: `python -m venv venv && source venv/bin/activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Configure environment variables in `.env`
5. Initialize database: `python scripts/init_db.py`
6. Run the application: `uvicorn app.main:app --reload`

## Project Structure

```
antibiotic-llm-system/
├── app/                    # Main application code
│   ├── api/               # API endpoints
│   ├── core/              # Core business logic
│   ├── models/            # Database models
│   ├── services/          # Business services
│   └── utils/             # Utility functions
├── data/                  # Medical databases and guidelines
├── docs/                  # Documentation
├── frontend/              # React frontend
├── scripts/               # Setup and maintenance scripts
├── tests/                 # Test suites
└── requirements.txt       # Python dependencies
```

## Development Guidelines

- Follow medical software development best practices
- Implement comprehensive testing for medical logic
- Maintain detailed audit logs for all recommendations
- Regular validation against current medical guidelines
- Secure handling of patient data (HIPAA compliance)

## License

This project is licensed under a restricted medical software license - see LICENSE file for details.
