# 🌞 Solar Data Discovery
Kickstart Your AI Mastery with Cross-Country Solar Farm Analysis
This project analyzes solar farm data from Benin, Sierra Leone, and Togo to identify high-potential regions for solar installation. 
It includes data cleaning, exploratory analysis, cross-country comparison, and an interactive Streamlit dashboard.
```
├── app/
│   └── main.py             # Streamlit dashboard
├── data/
│   ├── benin-malanvile.csv
│   ├── sierraleone-bumbuna.csv
│   └── togo-dapaong_qc.csv
├── notebooks/
│   └── <country>_eda.ipynb # Exploratory Data Analysis notebooks
├── scripts/
│   └── README.md
├── reports/
│   ├── Interim_Report.pdf
│   └── Final_Report.pdf
├── requirements.txt
└── README.md
```
## Environment Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/solar-challenge-week1.git
cd solar-challenge-week1
```

python -m venv venv
# or using conda
conda create -n solar python=3.12

```
pip install -r requirements.txt
```

---

### **5. Running the Streamlit Dashboard**
```markdown
## Launch the Interactive Dashboard

Run the following command:
```bash
streamlit run app/main.py
```

---

### **6. Additional Notes / Insights**
```markdown
- All data files are located in the `data/` folder.
- Cleaned datasets are used in the notebooks for analysis and visualization.
- Screenshots of the dashboard are available in `reports/dashboard_screenshot.png`.
- The dashboard allows for interactive exploration to support data-driven decisions.
```


