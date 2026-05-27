# Data Science – Assignment 2 

---

## File Structure

```
ds-assignment-2/
├── Analysis(1).ipynb                      # Main Jupyter Notebook
├── pakistan-media-dataset-synthetic.csv   # Original Dataset
├── cleaned_media_dataset.csv             # Cleaned Dataset
└── README.md
```

---

## 📋 Assignment Overview

A forensic data analysis investigation for the Media Accountability Network (MAN) into systematic bias, editorial influence, and data manipulation in Pakistan's media ecosystem using a synthetic dataset of news outlets.

Key areas of investigation:
- Data cleaning and preprocessing (inconsistent categories, unit mismatches, outliers)
- Exploratory data analysis (descriptive statistics, distributions)
- Comparative analysis of pro-government vs independent media (TRP, revenue, sentiment)
- Journalist beat analysis and topic coverage patterns
- Advertising revenue vs political affiliation correlation
- Watchdog report with findings and ethical reflections

---

## 🔧 Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib` / `seaborn` – Visualization

---

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/KainatZahraa/pakistan-media-bias-analysis.git
   cd pakistan-media-bias-analysis
```

2. Install dependencies:
```bash
   pip install pandas numpy matplotlib seaborn
```

3. Launch Jupyter Notebook:
```bash
   jupyter notebook "Analysis(1).ipynb"
```

> Make sure `pakistan-media-dataset-synthetic.csv` is in the same directory as the notebook.
