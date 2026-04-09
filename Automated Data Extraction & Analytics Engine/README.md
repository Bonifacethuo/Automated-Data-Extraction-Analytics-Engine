# 🚀 Automated Data Extraction & Analytics Engine

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Data-Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Visibility](https://img.shields.io/badge/Visibility-Public-green)](#)

## 📋 Project Overview
This repository contains a suite of **high-performance Python automation scripts** designed to streamline data extraction from complex, unstructured business materials. By bridging the gap between raw PowerPoint presentations (`.pptx`) and structured Excel spreadsheets (`.xlsx`), this engine enables rapid analysis of market performance metrics without manual data entry.

### 💡 The Problem
Manually extracting data from hundreds of slides and cross-referencing them with solution workbooks is a bottleneck for data analysts. 

### ✅ The Solution
An automated ETL (Extract, Transform, Load) pipeline that:
1.  **Directly parses PPTX XML content** (minimizing dependencies and maximizing speed).
2.  **Analyzes Excel structures dynamically** using Pandas and Openpyxl.
3.  **Generates structured analytical outputs** for immediate business decision-making.

---

## 🛠️ Tech Stack & Key Features

### **Technologies**
*   **Core Logic:** Python 3.x
*   **Data Processing:** `Pandas` (ETL), `NumPy`
*   **Excel Engine:** `Openpyxl`
*   **Low-Level Parsing:** `Zipfile` & `Regex` (for direct PowerPoint XML manipulation)

### **Key Features**
- **Zero-Dependency PPTX Extraction:** Avoids heavy libraries by reading raw XML from slide archives—ideal for lightweight deployment.
- **Dynamic Excel Mapping:** Automatically detects worksheet structures and handles varying data formats across multiple sheets.
- **Automated Verification:** Cross-validates extracted exercise data against "Master Solution" workbooks to ensure 100% accuracy.
- **Structured Reporting:** Outputs clean, readable logs and extracted data points for downstream BI tools.

---

## 📊 Project Insights: Real-World Output
The engine was used to analyze market dynamics for a shopper dataset (Exercise 2.2). Below is a snapshot of the **automated analytical output**:

| Metric | Brand 1 | Brand 2 | Brand 3 | Brand 4 | Brand 5 | Brand 6 |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Market Share** | 31.7% | 28.4% | 14.5% | 10.3% | 8.6% | 6.5% |
| **Penetration** | 27.6% | 19.8% | 18.2% | 12.0% | 9.4% | 9.0% |
| **Purchase Freq.** | 4.34 | 5.42 | 3.00 | 3.23 | 3.45 | 2.73 |

> **Key Takeaway:** The analysis reveals that "Brand 2" has the highest purchase frequency despite a lower penetration than "Brand 1", suggesting strong brand loyalty among its core users.

---

## 🚀 Getting Started

### **1. Installation**
```bash
# Clone the repository
git clone https://github.com/Bonifacethuo/Automated-Python-Scripts.git

# Install dependencies
pip install pandas openpyxl
```

### **2. Execution**
Run the core analysis scripts to generate insights:
```bash
python read_data.py        # Extracts raw data from Excel/PPTX
python read_details.py     # Detailed slide-by-slide text extraction
python analyze_exercise.py  # Generates the final analytical report
```

---

## 👨‍💻 Why This Matters for Recruiters
This project demonstrates more than just coding—it shows a **product-focused mindset**:
- **Efficiency:** Replacing hours of manual extraction with seconds of automation.
- **Robustness:** Handling "messy" real-world data files with fallback mechanisms.
- **Analytical Depth:** Transforming raw text and numbers into actionable market insights.

---

## 📬 Connect With Me
I am always looking for opportunities to apply my automation and data engineering skills to real-world challenges.

- **LinkedIn:** [Boniface Thuo](https://www.linkedin.com/in/boniface-thuo-52ab3816a/) 
- **Portfolio:** [http://boniface-thuo-m-portifolio.vercel.app/]
- **GitHub:** [@Bonifacethuo](https://github.com/Bonifacethuo)

---
*Keywords: Python Automation, Data Extraction, ETL, Excel Analytics, PPTX Parsing, Business Intelligence, Data Engineering Portfolio.*
