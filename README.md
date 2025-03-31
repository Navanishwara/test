# Loan Origination Workflow - Proof of Concept (POC)

## Objective
The goal of this POC is to develop a basic workflow for loan origination. It allows employees to securely manage customer loans within a multilingual application.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Technical Stack](#technical-stack)
4. [Setup Instructions](#setup-instructions)
5. [Step-by-Step Workflow](#step-by-step-workflow)
6. [Technical Considerations](#technical-considerations)
7. [Future Enhancements](#future-enhancements)

---

## Project Overview
This POC provides:
- A streamlined workflow for efficient loan processing.
- Secure user authentication and data management.
- Multilingual support for improved user experience.
- API-driven architecture for scalability and adaptability.

---

## Key Features
1. **User Authentication**
   - Secure login using a 4-digit PIN.
   - Multilingual support (English, Spanish, French).
   - Personalized welcome message post-login.
2. **Customer Search and Management**
   - Search customers by name and date of birth.
   - Add new customers if not found.
   - Validate and store customer details securely.
3. **Employment Details Collection**
   - Capture company name, net income, and last salary date.
   - Store employment details for loan assessment.
4. **Loan Application and Calculation**
   - Suggest loan amounts based on income.
   - Employees can adjust loan amounts within allowed limits.
   - Store loan details securely in the database.
5. **Loan History and Tracking**
   - View customer’s loan history and transaction details.
   - Track loan statuses and payment activity.
6. **API Integration and Caching**
   - Seamless UI-API communication for data operations.
   - Front-end caching to optimize performance.

---

## Technical Stack
- **Backend Development**: C# (Visual Studio 2022)
- **Frontend Development**: AngularJS, HTML, CSS, Bootstrap (VS Code)
- **Database**: PostgreSQL (secure storage and management)

---

## Setup Instructions
### Prerequisites
1. Install [Visual Studio 2022](https://visualstudio.microsoft.com/) for backend development.
2. Install [VS Code](https://code.visualstudio.com/) for front-end development.
3. Set up [PostgreSQL](https://www.postgresql.org/) for database management.
4. Ensure Node.js and Angular CLI are installed for AngularJS.

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd LoanOriginationWorkflow
