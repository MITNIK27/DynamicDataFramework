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
   git clone https://github.com/MITNIK27/DynamicDataFramework.git
   cd DynamicDataFramework/App1.ipynb

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the application:
   ```bash
   python rule_engine.py

## Application 2: Real-Time Weather Monitoring System
### Overview
The Real-Time Weather Monitoring System retrieves real-time weather data from the OpenWeatherMap API. The data is processed to generate daily rollups and aggregates (average, max, min temperature, etc.), and alerts are triggered based on configurable thresholds.

### Key Features
- Real-Time Weather Data Retrieval
- Dynamic Rollups and Aggregates 
- Threshold Alerts 
- Forecast Summary 
- Error Handling

### Design Choices
- OpenWeatherMap API: Selected for reliable access to real-time and forecast weather data for multiple cities.
- Python for Data Processing: Chosen for its ease of use in handling API responses and processing real-time data efficiently.
- Alerts & Aggregates: Built-in functionality to handle thresholds and provide daily summaries based on real-time data.

### How to Run
 1. Clone the repository:
    ```bash
    git clone https://github.com/MITNIK27/DynamicDataFramework.git
    cd DyanamicDataFramework/App2.ipynb
 2. Install dependencies:
    ```bash
    pip install -r requirements.txt
 3. Set up your OpenWeatherMap API key:
    API_KEY = '005a68adc5b1790d133aa2aeab176807'
 4. Run the applicationn:
    ```bash
    python weather_monitoring.py

### Dependencies
- Python 3.x
- Libraries:
  ```bash
  requests
 for API calls.
```bash
matplotlib
```
for data visualization (optional for plotting graphs).
### Testing
- Test cases are embedded within the scripts for retrieving weather data and verifying daily summaries.
- Test for various thresholds and weather conditions by adjusting the parameters in the script.
### Example Run:
- Retrieve weather data for a city.
- Trigger alerts if thresholds are breached (e.g., temperature > 35°C).
- Visualize temperature trends using matplotlib (optional).
