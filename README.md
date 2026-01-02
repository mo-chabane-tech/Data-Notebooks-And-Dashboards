# Introduction
This repository contains my data-analysis projects: I collect datasets (mostly from Kaggle), clean and explore them in Jupyter notebooks, and publish the cleaned data as interactive Power BI dashboards.

![Static Badge](https://img.shields.io/badge/v3.8+-blue?logo=python&label=Python&labelColor=green) ![Static Badge](https://img.shields.io/badge/3-red?logo=github&label=Projects) ![Static Badge](https://img.shields.io/badge/apache%202.0-black?label=License)

# Python version
Python 3.8 or higher is required.

# Quick start (2 steps)
1. Clone:
```bash
git clone "https://github.com/mo-chabane-tech/Data-Notebooks-And-Dashboards.git"
git lfs pull
cd Data-Notebooks-And-Dashboards
```

2. Install (recommended: virtual env):
```bash
# Windows
python3.8 -m venv .venv # or 'python -m venv .venv' if python points to 3.8 or higher
.venv\Scripts\activate # use '. .venv/bin/activate' on macOS/Linux

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt
```

# Repo layout
```
/
├─ .gitattributes
├─ .gitignore
├─ README.md
├─ project-1-name/
│  ├─ Notebook.ipynb
│  ├─ data.csv         <- tracked with git lfs
│  ├─ dashboard.pbix   <- tracked with git lfs
│  ├─ dashboard-preview.png    <- tracked with git lfs
│  └─ README.md
└─ project-2-name/
```
