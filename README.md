# DynamicDataFramework

## Overview

This repository contains the code for the Zeotap Intern Assignment, which includes:
1. **Application 1:** A Rule Engine with Abstract Syntax Tree (AST) to determine user eligibility based on attributes.
2. **Application 2:** A Real-Time Weather Monitoring System with rollups and aggregates using the OpenWeatherMap API.

---

## Application 1: Rule Engine with AST

### Overview
This application implements a 3-tier rule engine to evaluate user eligibility based on rules such as age, department, salary, etc. It allows for dynamic creation, combination, and modification of rules using Abstract Syntax Trees (AST).

### Key Features
- Dynamic rule creation, modification, and evaluation.
- Error handling for invalid rule strings.
- User-defined functions for advanced conditions.
- Validation of attributes against a predefined catalog.

### Design Choices
- **Abstract Syntax Tree (AST):** Chosen to represent the rule logic for flexibility in dynamic rule construction.
- **Python-based API:** For easy integration with other systems.
- **Error Handling:** Comprehensive error handling for invalid rules or missing data.

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/zeotap-intern-assignment.git
   cd zeotap-intern-assignment/application1-rule-engine
