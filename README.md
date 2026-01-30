# perplexica-data-pipeline
Groq-Powered Industrial Data Extractor This project is a high-speed data extraction tool
# 🏗️ Egypt Industrial Project Extractor

An automated Python script that utilizes the **Groq API** and **Llama 3.1** to extract structured data regarding the largest upcoming industrial projects in Egypt.

## 🚀 Overview
This tool is designed to test the capabilities of structured JSON output from high-speed LLMs. The output is formatted specifically to be compatible with search-heavy AI tools like **Perplexica**, allowing for seamless data verification and research.

## 🛠️ Features
- **Model:** Llama-3.1-8b-instant (via Groq).
- **Format:** Strict JSON enforcement using `response_format={"type": "json_object"}`.
- **Data Points:** Captures Project Name, Size (sqm), Contractor, Owner, Status, and Completion Date.
- **Speed:** Optimized for low-latency data extraction.

## 📋 Prerequisites
- Python 3.8+
- A Groq API Key (Get one at [console.groq.com](https://console.groq.com))

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME
