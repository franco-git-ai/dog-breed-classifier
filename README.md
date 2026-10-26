# Panoramica:
    Il progetto usa un classificatore di immagini pre-addestrato per identificare se un’immagine contiene un cane e confrontare la classificazione con le etichette reali.

# Contesto:
    Classificazione immagini di animali 

# Obiettivo:
    Valutare le prestazioni di modelli diversi 

# Focus:
    Organizzare il flusso con script Python e analisi dei risultati

# Obiettivo del progetto: 
    Usare modelli di image classification pre-addestrati per verificare le etichette delle immagini di animali domestici e confrontarne l’accuratezza.

    input → immagini + label reali
    processo → classificazione con modelli diversi
    output → statistiche e confronto delle prestazioni

# Files:
    classifier.py
    get_input_args.py
    check_images.py
    calculates_results_stats.py
    print_results.py
    dognames.txt
    run_models_batch.sh
    ...

# Come procedere:
    Il progetto si esegue da terminale lanciando lo script principale check_images.py con gli argomenti richiesti, e che il file run_models_batch.sh serve per testare più modelli in sequenza.

    check_images.py → punto di ingresso 
    | get_input_args.py / classifier.py / print_results.py → moduli chiamati dallo script principale 
    | run_models_batch.sh → automatizza più esecuzioni

# Cosa ho imparato:
    - classificazione con modelli pre-addestrati 
    - gestione argomenti da riga di comando 
    - analisi e confronto dei risultati


## 📝 Nota sulla struttura del codice e indicazioni TODO
I commenti e le istruzioni `TODO` presenti nei file sorgente sono stati intenzionalmente mantenuti a scopo educativo e metodologico. Testimoniano la struttura originale dell'esercitazione proposta nel corso Udacity e mostrano il percorso step-by-step seguito per l'implementazione del codice finale e il completamento del progetto.


---
## 👤 Autore
Sviluppato da **Francesco Venale**  
*Progetto realizzato nell'ambito del percorso di specializzazione in Artificial Intelligence / Deep Learning.*

*Corso Udacity Nanodegree Future AWS AI Programmer.*