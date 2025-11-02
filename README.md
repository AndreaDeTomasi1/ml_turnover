# ML_Turnover

## Descrizione del progetto
**ML_Turnover** è un progetto di machine learning finalizzato alla **predizione del turnover aziendale** (ovvero se un dipendente lascerà l’azienda o meno).  
Il progetto nasce come esercizio in ambiente SAS Miner, successivamente è stato eseguito anche in **Python**, con l’obiettivo di confrontare modelli, analizzare variabili e standardizzare il workflow di machine learning.

---

## Contenuti della repository

- **Dataset**
  - `Employee.csv` : dataset originale preso da [Kaggle](https://www.kaggle.com/) contenente informazioni sui dipendenti.

- **Notebook**
  - `ml_turnover.ipynb` : notebook Python con tutto il codice per:
    - Pulizia e trasformazioni dei dati
    - Studio delle variabili
    - Confronto di modelli (Naive Bayes, Decision Tree, Random Forest)
    - Calcolo metriche di performance, ROC curve e soglia ottimale
    - Salvataggio del modello migliore: Random Forest 

- **Modello salvato**
  - `rf_reduced_package.pkl` : modello Random Forest addestrato sul dataset ridotto, salvato con Pickle insieme alla soglia ottimale e alla versione di scikit-learn.

- **Presentazione**
  - `ML_turnover.pptx` : slide di presentazione del progetto e dei risultati ottenuti.

- **Versione SAS**
  - `diagramma_sas_miner_ml_turnover.xml` : diagramma del progetto originale realizzato con SAS Miner.

---

## Obiettivi del progetto

1. Esercitarsi nella **realizzazione di un progetto di ML in SAS Miner e Python**.
2. Analizzare il **dataset dei dipendenti** per comprendere quali variabili influenzano il turnover.
3. Confrontare diversi modelli di classificazione
4. Calcolare metriche di performance, curve ROC, MSE, e determinare la soglia ottimale per il modello vincitore.
5. Salvare e rendere riutilizzabile il modello addestrato in Python tramite Pickle.

---

ml_turnover/  
│  
├─ Employee.csv  
├─ ml_turnover.ipynb  
├─ rf_reduced_package.pkl  
├─ ML_turnover.pptx  
└─ diagramma_sas_miner_ml_turnover.xml  
## Struttura dei file

