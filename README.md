# Document Scans (Public Documentation)

This repository serves as the public documentation for my **Document Scans** project — a Python-based automation tool developed during my On-the-Job Training (OJT).  
The system was designed to **streamline data encoding** by converting scanned graduation records into structured CSV datasets.

---

## Overview

Manually typing hundreds of graduate records was time-consuming and error-prone.  
To solve this, I created a **scripted pipeline** that processes scanned images of graduation lists and extracts key information such as:

- Full Name  
- Course / Program  
- Year and Section (if applicable)

The data is then compiled into a **clean, structured CSV** ready for database import or analysis.

---

## ⚙️ How It Works

1. **Preprocessing:** Images are cleaned and converted for better OCR accuracy.  
2. **OCR Extraction:** The system reads text from scanned documents using OCR (Optical Character Recognition).  
3. **Data Parsing:** Relevant fields (names, courses) are extracted using pattern recognition and string filtering.  
4. **Output:** Generates a CSV file with structured, accurate records.

---

## Tech Stack

- **Language:** Python
- - **Output Format:** CSV
