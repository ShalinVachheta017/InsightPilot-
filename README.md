# InsightPilot++

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
