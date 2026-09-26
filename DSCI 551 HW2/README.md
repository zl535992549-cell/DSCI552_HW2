# HW2 — Combined Cycle Power Plant

## Repository structure

```text
.
├── data/
│   └── CCPP/
│       ├── Folds5x2_pp.xlsx
│       └── Readme.txt
├── notebook/
│   └── Last_First_HW2.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Setup

```bash
python -m venv .venv
# Windows PowerShell:
.venv\Scripts\Activate.ps1
# macOS/Linux:
# source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook
```

Open `notebook/Last_First_HW2.ipynb`, replace the name/GitHub/USC ID placeholders, rename the notebook to `Lastname_Firstname_HW2.ipynb`, then use **Kernel > Restart & Run All** (or **Cell > Run All**, depending on Jupyter version).

The notebook intentionally loads the data with the relative path `../data/CCPP/Folds5x2_pp.xlsx`. Do not replace it with an absolute path.
