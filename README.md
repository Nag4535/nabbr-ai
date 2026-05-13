# NABBR AI ⚡
### Enterprise Analytics Platform by Nalla

> From raw data to boardroom-ready insights — in seconds.

---

## 🚀 Features

- 🔐 **User Authentication** — Supabase auth (login, register, secure sessions)
- 📁 **Multi-Workspace** — Organise analyses into separate workspaces
- 🧹 **Auto-Clean Pipeline** — Deduplication, imputation, outlier removal, date parsing
- 🤖 **7 AI Agents** (LLaMA 3.3 via Groq):
  - 🔍 Quality Inspector
  - 📊 Statistical Analyst
  - 🧠 ML Expert
  - 🎨 Visualization Designer
  - 📄 Report Writer
  - 💼 Business Advisor
  - 🎯 Strategy Director
- 📊 **Interactive Dashboard** — Distributions, correlations, categories, time series, custom charts
- 🧠 **ML Pipeline** — Auto-trains 3 models (RF, GB, LR), feature importance, predictions
- 📄 **Report Generator** — PDF + Excel reports, cleaned data download
- 📜 **Session History** — All analyses saved to Supabase

---

## 🛠️ Setup & Deploy

### 1. Clone & Install
```bash
git clone <your-repo>
cd nabbr_ai
pip install -r requirements.txt
```

### 2. Set Environment Variable
Add your Groq API key:
```bash
export GROQ_API_KEY=gsk_your_key_here
```

### 3. Run Locally
```bash
streamlit run app.py
```

### 4. Deploy to Streamlit Cloud
1. Push to GitHub
2. Go to share.streamlit.io
3. Connect your repo → select `app.py`
4. Add secret: `GROQ_API_KEY = "gsk_..."`
5. Deploy! ✅

---

## 🔧 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Streamlit |
| AI Agents | LLaMA 3.3 via Groq API |
| Auth + DB | Supabase |
| ML | scikit-learn, XGBoost |
| Forecasting | Prophet |
| Reports | FPDF2 (PDF) + openpyxl (Excel) |
| Charts | Plotly |
| Language | Python 3.11 |

---

## 📁 File Structure
```
nabbr_ai/
├── app.py              # Main application
├── requirements.txt    # Dependencies
├── .streamlit/
│   └── config.toml    # Theme & server config
└── README.md
```

---

**NABBR AI by Nalla** · Built with ⚡ by Nagarajulu Reddy Nalla
