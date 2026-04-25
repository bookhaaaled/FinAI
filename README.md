# FinAI — Financial Analytics Platform

> Senior Capstone Project | Saudi Electronic University  
> Supervised by **Dr. Faris Hassan Almansour** | Advised by **Prof. Abc**

---

## Project Overview

**FinAI** is an automated financial analysis tool designed to parse complex financial datasets, generate exploratory data analysis (EDA) reports, and surface actionable insights — all through a clean, user-friendly interface backed by a robust database layer.

The platform reduces manual data profiling time by **90%** through automated EDA pipelines, CSV upload processing, and AI-assisted financial reporting.

---

## Features

- **CSV Upload & Parsing** — Automated ingestion of financial datasets
-  **Automated EDA** — Instant statistical summaries, distributions, and anomaly flags
- **AI-Assisted Analysis** — LangChain-powered natural language financial insights
- **Interactive Visualizations** — Dynamic charts and dashboards via the UI layer
- **Session Management** — Persistent user sessions and analysis history via MySQL

---

##  Project Structure

```
FinAI/
├── src/
│   ├── tools/          # Core analytics & EDA engine (Python, Pandas, LangChain)
│   ├── ui/             # Frontend interface & design components
│   └── database/       # Database models, sessions, and connection logic
├── data/
│   ├── raw/            # Original uploaded datasets (gitignored)
│   └── processed/      # Cleaned/transformed outputs (gitignored)
├── docs/               # Project documentation & reports
├── tests/              # Unit and integration tests
├── scripts/            # Utility and setup scripts
├── requirements.txt    # Python dependencies
├── .env.example        # Environment variable template
└── README.md
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3.11+ |
| Data Processing | Pandas, NumPy |
| AI / LLM | LangChain |
| Database | MySQL |
| Machine Learning | Scikit-Learn |
| Version Control | Git / GitHub |

---

## Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/FinAI.git
cd FinAI
```

### 2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure environment variables
```bash
cp .env.example .env
# Edit .env with your database credentials and API keys
```

### 5. Set up the database
```bash
python scripts/setup_db.py
```

### 6. Run the application
```bash
python src/ui/app.py
```

---

## Team

| Name | Role | Student ID |
|---|---|---|
| Bader Mohammed Salem Alkathiri | Group Leader & Tools Building | - |
| Abdulrahman Hassan Ali Alzubaidi | Tools Building | S210020445 |
| Faris Mohammed Alshaikhi | UI Designing | - |
| Abdulrahman Mohammed A Alhomayany | Tools Building | - |
| Yazeed Abdulrahman Mahmoud Almadhoun | Database & Sessions Management | - |

---

## License

This project is developed as an academic capstone project at **Saudi Electronic University**.  
© 2025 FinAI Team. All rights reserved.
