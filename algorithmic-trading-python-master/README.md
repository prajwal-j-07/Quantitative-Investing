# Quantitative-Investing

![License](https://img.shields.io/badge/license-MIT-green) ![Python Version](https://img.shields.io/badge/python-3.8%2B-blue) ![Build Status](https://img.shields.io/github/actions/workflow/status/<your-username>/Quantitative-Investing/ci.yml)

A hands-on repository of quantitative trading strategies using Python. Covers equal-weight indexing, momentum, and value approaches on the S&P 500.

---

## 🚀 Project Overview
This course-style repo guides you through:
1. **Equal-Weight S&P 500 Index Fund**
2. **Quantitative Momentum Strategy**
3. **Quantitative Value Strategy**

Each section covers theory, data acquisition, weight calculations, output generation, and extension ideas.

---

## 📋 Course Outline

### Section 1: Fundamentals
- What is Algorithmic Trading?
- Real-World vs. Course Scope

### Section 2: Setup & API Basics
- Installing Python & Tools
- Cloning & Dependencies
- Jupyter Notebook Basics
- API Request Fundamentals

### Section 3: Equal-Weight S&P 500 Index
- Theory & Concepts
- Importing Constituents
- Data Pull (Yahoo Finance, Alpha Vantage)
- Calculating Weights
- Generating Output Files
- Extension Ideas

### Section 4: Momentum Strategy
- Theory & Concepts
- Data Pull & Preprocessing
- Momentum Score Calculation
- Portfolio Construction
- Generating Output Files
- Extension Ideas

### Section 5: Value Strategy
- Theory & Concepts
- Data Pull & Fundamental Metrics
- Value Score Calculation
- Portfolio Construction
- Generating Output Files
- Extension Ideas

---

## ⚙️ Prerequisites
- Python 3.8+  
- Git  
- Docker (optional)  
- API keys (e.g., Alpha Vantage, IEX Cloud) as environment variables:
  ```bash
  export ALPHAVANTAGE_API_KEY="your_key_here"
  export IEXCLOUD_API_TOKEN="your_token_here"
