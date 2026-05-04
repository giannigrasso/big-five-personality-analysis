# DataScience_Project1
Questo progetto è stato realizzato nell'ambito del corso di **Data Science** e consiste in un'analisi di un dataset reale.

## Dataset
Il dataset contiene le risposte a un test di personalità online basato sui **Big Five Factor Markers**.

---

## Struttura del Dataset

### Le 5 dimensioni della personalità (Big Five / OCEAN)

Ogni dimensione è misurata da **10 domande**, valutate da 1 (*In disaccordo*) a 5 (*D'accordo*).

| Codice | Dimensione            | Descrizione                                                  |
|--------|-----------------------|--------------------------------------------------------------|
| `EXT`  | **Estroversione**     | Socievolezza, energia, tendenza a cercare stimoli esterni    |
| `EST`  | **Stabilità Emotiva** | Calma, resistenza allo stress, controllo emotivo             |
| `AGR`  | **Amabilità**         | Cooperazione, empatia, orientamento verso gli altri          |
| `CSN`  | **Coscienziosità**    | Organizzazione, affidabilità, autodisciplina                 |
| `OPN`  | **Apertura Mentale**  | Curiosità intellettuale, immaginazione, creatività           |

### Tempi di risposta

Per ogni domanda esiste una variabile `<CODICE>_E` (es. `EXT1_E`) che registra il **tempo in millisecondi** impiegato per rispondere, calcolato come differenza tra il click sulla risposta e il click precedente.

### Metadati

| Colonna                  | Descrizione                                                          |
|--------------------------|----------------------------------------------------------------------|
| `dateload`               | Timestamp di inizio del questionario                                 |
| `screenw` / `screenh`    | Risoluzione schermo dell'utente (pixel)                              |
| `introelapse`            | Secondi trascorsi sulla pagina introduttiva                          |
| `testelapse`             | Secondi trascorsi sulla pagina con le domande                        |
| `endelapse`              | Secondi trascorsi sulla pagina finale (conferma consenso)            |
| `IPC`                    | Numero di risposte dallo stesso IP                                   |
| `country`                | Paese dell'utente (rilevato tecnicamente, non dichiarato)            |
| `lat_appx_lots_of_err`   | Latitudine approssimativa                                             |
| `long_appx_lots_of_err`  | Longitudine approssimativa                                             |

---

## Struttura della Repository

```
├── README.md               # Questo file
├── description.txt         # Descrizione del dataset 
├── data/
│   └── data.csv            # Dataset originale (non incluso nel repository)
└── notebook/
    └── analysis.ipynb      # Notebook Jupyter con l'analisi del dataset
```
---