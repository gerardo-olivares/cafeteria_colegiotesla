# Cafetería Tesla ☕📊

# Overview

This project was developed to solve a real operational problem inside a private school environment.  
Before the system existed, teachers manually tracked student meals and payments using paper notes and spreadsheets, which caused delays, inconsistencies, and poor visibility of outstanding balances.

The goal of this project was to design and deploy a complete web-based system that centralized:

- Student meal registration
- Payment tracking
- Debt calculation
- Account statements
- Excel reporting
- Administrative management

The system is currently designed for real-world school operations and focuses on simplicity, reliability, and fast administrative workflows.

---

# Problem

The school needed a way to:

- Track which students consumed breakfast/lunch
- Monitor pending balances
- Register payments efficiently
- Generate reports for administration
- Reduce manual work and spreadsheet errors

The existing workflow was fragmented and time-consuming.

---

# Solution

I built a full-stack administrative platform composed of:

- A REST API backend using Python and FastAPI
- A Streamlit-based admin interface
- A PostgreSQL database for persistent storage
- Excel report generation for operational use

The system allows staff members to:

✅ Register student purchases  
✅ Register payments/credits  
✅ View account balances  
✅ Generate account statements  
✅ Export operational reports  

---

# Tech Stack

## Backend
- Python
- FastAPI
- REST APIs

## Frontend / Admin Panel
- Streamlit

## Database
- PostgreSQL
- SQLite (initial prototype)

## Deployment
- Render

## Data & Reporting
- Pandas
- Excel report generation

---

# Features

## Student Management
- Student registration
- Student search
- Multiple student selection

## Sales Management
- Meal/product registration
- Quantity handling
- Automatic balance updates

## Payment System
- Payment registration
- Optional payment concepts/notes
- Debt tracking

## Reporting
- Account statements
- Downloadable Excel reports
- Administrative summaries

---

# System Architecture

```text
Teachers/Admin
       ↓
Streamlit Admin Panel
       ↓
FastAPI REST API
       ↓
PostgreSQL Database
```

---

# Why This Project Matters

This was not built as a tutorial or academic-only project.

It was created to solve an actual operational problem inside a school environment with real users and real administrative workflows.

Through this project I learned:

- Backend API development
- Database design
- Deployment to cloud infrastructure
- Real-world software architecture
- Data handling and reporting
- Business-oriented problem solving
- Translating operational needs into software solutions

The experience also helped me understand the difference between building small coding exercises and developing software intended for continuous real-world use.

---

# Challenges

Some of the technical and operational challenges included:

- Designing a clean workflow for non-technical users
- Migrating from SQLite to PostgreSQL
- Handling report generation
- Managing environment variables and deployment configuration
- Structuring scalable API endpoints
- Ensuring simple administrative usability

---

# Future Improvements

Planned improvements include:

- Authentication system with roles
- Purchase confirmation workflows
- Debtors dashboard
- School cycle reset system
- Bulk Excel uploads
- Analytics dashboard
- AI-assisted administrative insights

---

# What I Would Improve Today

If rebuilding the project today, I would likely:

- Containerize services using Docker
- Add automated testing
- Improve API documentation
- Implement CI/CD pipelines
- Add monitoring/logging
- Separate frontend and backend into independent services

---

# Installation

```bash
git clone https://github.com/yourusername/cafeteria-tesla.git
cd cafeteria-tesla
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run backend:

```bash
uvicorn main:app --reload
```

Run Streamlit frontend:

```bash
streamlit run app.py
```

---

# Environment Variables

Create a `.env` file with:

```env
DATABASE_URL=your_database_url
STREAMLIT_USERNAME=your_username
STREAMLIT_PASSWORD=your_password
API_URL=your_api_url
```

---

# API Documentation

FastAPI automatically generates interactive API documentation:

```bash
/docs
```

---

# Author

**Gerardo Olivares**  
Software Engineering Student  
