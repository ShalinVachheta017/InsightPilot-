# InsightPilot++

## Project Summary

### What is this project?
This is an early-stage idea for a personal data assistant that helps explore CSV files.

### Why is it interesting?
People often have spreadsheets full of data but do not know where to start.

### How does it work?
The planned app reads a CSV file, examines the columns, and supports questions and charts.

### Real-life example
You upload a sales CSV and ask what changed over time. The assistant is intended to help explore it.

### What did I learn?
This project explores how data tools and language models could work together. The README describes an early phase, not a complete product.

---

## Technical Documentation


🔍 LLM-powered personal data scientist copilot. Upload large CSVs, clean them intelligently, derive features, ask questions in natural language, get charts, and export your dashboards.

## 💡 Features (Phase 1)
- Upload large datasets (1GB+)
- Smart schema parsing + profiling
- Streamlit UI
- DuckDB SQL engine on CSV

## 🛠 Tech Stack
- Python 3.10
- Streamlit
- DuckDB
- Pandas
- Pandas Profiling
- Ollama + Mistral (optional)

## 🚀 How to Run (Local)
```bash
git clone https://github.com/<your-username>/InsightPilot.git
cd InsightPilot
pip install -r requirements.txt
streamlit run app/main.py
