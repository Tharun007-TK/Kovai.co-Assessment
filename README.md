# Transportation Ridership Forecasting - Kovai.co Assessment

## 📌 Project Overview

This project implements a **Vector Autoregression (VAR)** model for forecasting transportation ridership across multiple service categories. The solution was developed as part of the **Kovai.co technical assessment** to demonstrate time series forecasting capabilities for multivariate transportation data.

---

## ❓ Problem Statement

Predict **daily ridership for the next 7 days** across five transportation service categories:

- **Local Route** (bus services)  
- **Light Rail**  
- **Peak Service** (rush hour services)  
- **Rapid Route** (express services)  
- **School** (educational transport)  

---

## ⚙️ Solution Approach

### Algorithm Selection: **Vector Autoregression (VAR)**

#### Why VAR?

- Captures **interdependencies** between different transportation modes  
- Generates **simultaneous forecasts** for all service categories  
- Accounts for **cross-variable relationships**  
  (e.g., high bus ridership may correlate with high rail usage)

---

## 🔑 Key Features

### ✅ Robust Data Processing

- Multiple **date format parsing**  
- **Automatic numeric conversion** with error handling  
- **Missing value and outlier detection**  
- **Data validation and cleaning**  

---

### ✅ Intelligent Model Selection

- **AIC/BIC-based lag order selection**  
- **Automatic fallback mechanisms**  
- **Parameter optimization** with constraints  

---

### ✅ Comprehensive Forecasting

- **7-day ahead predictions**  
- **Non-negativity constraints** for realistic forecasts  
- Detailed **model diagnostics** and **performance metrics**  
