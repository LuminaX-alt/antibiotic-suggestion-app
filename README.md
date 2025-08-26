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
<img width="2823" height="1644" alt="image" src="https://github.com/user-attachments/assets/381fe962-97c1-4af1-99ae-db384f0a6614" />

<img width="1440" height="900" alt="Screenshot 2025-08-26 at 8 34 00 PM" src="https://github.com/user-attachments/assets/b98ec16a-c6a4-477b-8675-2fb229a433e6" />

<img width="2153" height="1438" alt="image" src="https://github.com/user-attachments/assets/88ef08a0-030b-492b-8834-a48cafb6e69c" />

<img width="2148" height="1434" alt="image" src="https://github.com/user-attachments/assets/faae3136-e48f-4ec5-b6dc-da3510edf76d" />

<img width="2205" height="395" alt="image" src="https://github.com/user-attachments/assets/a4ed876e-3c35-446b-aebc-b126d4c26f36" />

<img width="1526" height="696" alt="image" src="https://github.com/user-attachments/assets/a505c091-e834-4cbe-821e-c2cecbc840b4" />

<img width="2866" height="1439" alt="image" src="https://github.com/user-attachments/assets/f05e3d96-3db9-4602-9631-accc56213f78" />

<img width="2868" height="1438" alt="image" src="https://github.com/user-attachments/assets/0a294c08-e11e-4d3c-973f-6c0acf684c43" />



## Development Guidelines

- Follow medical software development best practices
- Implement comprehensive testing for medical logic
- Maintain detailed audit logs for all recommendations
- Regular validation against current medical guidelines
- Secure handling of patient data (HIPAA compliance)

## License

This project is licensed under a restricted medical software license - see LICENSE file for details.
