# InsightPilot++

## Project Summary

Imagine opening a large spreadsheet and not knowing where to begin. This early-stage project explores an assistant that could help you understand the data by asking simple questions. The challenge is making large files easier to search and explore without needing to write a lot of code.

The planned tool reads CSV files, examines their columns, and supports charts and questions about the data. For example, you might upload sales records and ask what changed over time. I am exploring how data tools and AI could work together to make analysis easier. The repository describes an early project, not a completed product.

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
