# AdvanceTaskMarsPart3
This repository contains Postman collections and test scripts for API automation, covering CRUD operations, response validation, schema checks, and error handling. It ensures reliable API behavior through automated tests and can be executed via Postman or Newman.

# API Automation with Postman

This repository contains Postman collections and automated test scripts for validating REST APIs.  
The tests cover **CRUD operations, response validations, schema checks, performance (response time), and error handling** to ensure API reliability.  

## 🚀 Features
- Automated tests for multiple API endpoints  
- JSON schema validation  
- Status code and header verification  
- Error handling tests (401, 415, 500, etc.)  
- Supports execution via **Postman** and **Newman (CLI)**  

## 📦 Usage
1. Clone this repository  
2. Import the collection (`.json` file) into **Postman**  
3. Run tests directly in Postman or via **Newman**:  
   ```bash
   newman run collection.json -e environment.json --reporters cli,html
