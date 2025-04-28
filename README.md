# IELTS Speaking Test Platform - Backend

## Assignment 14: Logging and Error Handling Implementation

### Overview
This repository contains the backend implementation for an IELTS Speaking Test platform with enhanced logging and error handling middleware as per Assignment 14 requirements.

### Key Features
- **Request Validation Middleware**
- **Structured Logging System**
- **Custom Error Handling**
- **API Endpoint Monitoring**

### Technical Specifications
| Component          | Technology Used |
|--------------------|----------------|
| Framework          | Flask          |
| Database           | SQLAlchemy     |
| Logging            | Python logging |
| Error Handling     | Custom Middleware |
| API Documentation  | Postman        |

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/assignment14.git
   cd assignment14/backend
Set up virtual environment:

bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
Install dependencies:

bash
pip install -r requirements.txt
Configuration
Create a .env file with:

ini
DATABASE_URL=sqlite:///ielts.db
SECRET_KEY=your-secret-key
DEBUG=True
Running the Application
bash
python app.py
API Endpoints
Endpoint	Method	Description
/api/users	POST	Create new user
/api/speaking-tests	POST	Submit speaking test
/api/listening-tests	POST	Submit listening test
Logging System
Logs are stored in:

backend/logs/ielts_YYYYMMDD.log
Sample log entry:

2024-05-20 14:30:45 - root - INFO - Incoming POST /api/users [ip=127.0.0.1]
Testing Evidence
See included screenshots in /screenshots directory showing:

Successful API responses

Error handling cases (400, 404, 500)

Log file outputs

Database state

Assignment Completion Proof
Request Validation Middleware

Structured Logging

Error Handling

Test Cases
