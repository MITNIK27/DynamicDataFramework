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

---

#### **3. Dependencies and Setup Instructions**
In the **README.md**, make sure you:
- List all dependencies (e.g., Python 3.x, libraries like `requests`, `re`, etc.).
- Provide clear setup instructions, including how to install dependencies using `requirements.txt` or how to use Docker (if applicable).
  - Example `requirements.txt`:
    ```txt
    requests==2.25.1
    matplotlib==3.4.2
    ```
- Provide instructions for configuring the **OpenWeatherMap API key** for the weather monitoring system.

#### **4. (Optional) Docker or Podman Setup**
- **Docker Setup (Optional but Recommended):**
  - Create a `Dockerfile` to containerize the application. Example `Dockerfile`:

    ```dockerfile
    FROM python:3.8-slim

    WORKDIR /app

    COPY . /app

    RUN pip install --no-cache-dir -r requirements.txt

    CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--allow-root"]
    ```

- **Docker Build and Run Instructions:**
  - Include commands in the README on how to build and run the Docker container.

---

### **4. Final Check and Submission**
- **Review the Codebase:** Ensure that the code runs without errors, and test cases pass.
- **Push to GitHub:** Push all your changes to the GitHub repository, ensuring the README is up to date.
- **Share the GitHub URL**: Submit the URL to your GitHub repository where the reviewer can access the code and follow the setup instructions.

---

Let me know if you need help with any of these steps or specific clarifications on the Docker setup, README, or GitHub process!
