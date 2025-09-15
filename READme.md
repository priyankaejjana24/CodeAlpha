# Data Redundancy Removal System

## 📂 Project Overview
This project is part of the **Cloud Computing Internship at CodeAlpha**. The goal of this task is to create a simple and efficient system to remove redundant (duplicate) entries from datasets. The solution is implemented using Python, and it can be extended to integrate with cloud storage services such as AWS S3.


## 🎯 Main Goal
- Develop a system to clean datasets by removing duplicate entries.
- Improve data quality for analytics, machine learning, and reporting.
- Prepare for cloud-native applications by working with data stored locally and in cloud storage.


## ✅ Features
- Load data from a JSON file (`input.json`).
- Identify and remove duplicate records.
- Save cleaned data to `output.json`.
- Designed for scalability and easy integration with cloud platforms.
- Interactive usage through **Jupyter Notebook** and Python scripts.


## 📂 Input File

The input file `input.json` contains sample data with names like **Nana, Lovely, Bangaram, Jimmy**, and includes some duplicate entries.

Example content of `input.json`:

```json
[
    {"name": "Nana", "email": "nana@example.com"},
    {"name": "Lovely", "email": "lovely@example.com"},
    {"name": "Bangaram", "email": "bangaram@example.com"},
    {"name": "Nana", "email": "nana@example.com"},
    {"name": "Jimmy", "email": "jimmy@example.com"},
    {"name": "Bangaram", "email": "bangaram@example.com"}
]
