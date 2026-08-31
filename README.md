# Big Five Personality Analysis

Analisi esplorativa di un dataset reale di test di personalità online, basato sui **Big Five Factor Markers** (IPIP), realizzata per il corso di Data Science.

## Dataset

Il dataset contiene ~1 milione di risposte a un test di personalità online (2016–2018), raccolto dall'[Open-Source Psychometrics Project](https://openpsychometrics.org/).

- **Fonte**: [Big Five Personality Test — Kaggle](https://www.kaggle.com/datasets/tunguz/big-five-personality-test)
- **Descrizione completa delle colonne**: [`data/description.txt`](data/description.txt)

Il file non è incluso nel repository: scaricalo dal link sopra e salvalo in `data/data-final.csv`.

## Struttura
```
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── description.txt      # descrizione dettagliata delle colonne del dataset
│   └── data-final.csv       # dataset (da scaricare, non incluso)
└── notebooks/
    └── big_five_analysis.ipynb
```

## Setup
```bash
pip install -r requirements.txt
jupyter notebook notebooks/big_five_analysis.ipynb
```

## Authors
- Gianni Grasso
- Gianni Toapanta