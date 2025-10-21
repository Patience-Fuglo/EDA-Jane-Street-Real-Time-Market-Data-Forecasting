# 🧠 Jane Street Real-Time Market Data Forecasting

Exploratory Data Analysis project for the **Jane Street Real-Time Market Data Forecasting** Kaggle competition.  
This notebook investigates patterns, feature distributions, and relationships in the provided market dataset to inform future predictive modeling.

---

## 📋 Project Overview

The goal of this analysis is to:
- Explore the **structure and quality** of the real-time trading dataset  
- Identify **key statistical patterns** and **data anomalies**  
- Visualize trends in key market variables (features, responses, and time)  
- Prepare clean, ready-to-model data for further quantitative research or ML pipelines  

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|----------|
| **Python 3.10+** | Core programming language |
| **Jupyter Notebook** | Interactive exploration |
| **Pandas / NumPy** | Data manipulation |
| **Matplotlib / Seaborn** | Data visualization |
| **LightGBM** | Baseline model testing |
| **VS Code** | Development environment |

---

## ⚙️ Quickstart

```bash
# 1. Clone this repo
git clone https://github.com/Patience-Fuglo/EDA-Jane-Street-Real-Time-Market-Data-Forecasting.git
cd EDA-Jane-Street-Real-Time-Market-Data-Forecasting

# 2. (Optional) Create virtual environment
python3 -m venv .venv
source .venv/bin/activate  # On Mac/Linux
# or .venv\Scripts\activate  # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook JaneStreetEDA.ipynb

