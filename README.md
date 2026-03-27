# Ringraziamenti: Sviluppo Software tramite Prompt Engineering

Progetto per il corso di **Data Science** *Corso di Laurea Magistrale in Ingegneria Informatica e dell'Automazione* **Università Politecnica delle Marche (UNIVPM)**

---

## 🤖 Visione del Progetto
Questo software non è stato scritto nel modo tradizionale. È il risultato di un esperimento di **sviluppo interamente guidato dall'Intelligenza Artificiale Generativa**. L'intero applicativo è stato creato attraverso un processo iterativo di "dialogo tecnico" con **Claude (modello Sonnet 4.6)**.

L'obiettivo principale non è solo la creazione di un sistema di "ringraziamenti" funzionale, ma la documentazione e l'analisi del **Prompt Engineering** come metodologia di sviluppo software moderna, sicura e scalabile.

## 📂 Struttura della Repository
La repository è organizzata per mostrare l'evoluzione del software attraverso **33 step iterativi**:

* **`Immagini/`**: Contiene 33 sottocartelle (una per ogni prompt). All'interno di ciascuna sono presenti gli screenshot dell'eseguibile e dei risultati ottenuti in quella specifica fase di sviluppo.
* **`Risultati prompt/`**: Contiene 33 file che documentano l'intero processo logico: il prompt inviato a Claude e un commento critico sull'output.
* **`Eseguibili/`**: Contiene i 33 script Python (`.py`) generati. Ogni file rappresenta uno stadio di avanzamento del software, dal prototipo iniziale alla versione finale completa.
* **Documentazione Finale**:
    * `Proposta_Progetto.pdf`: Documento con la definizione iniziale degli obiettivi.
    * `Relazione_Finale.pdf`: L'analisi tecnica completa, i test di sicurezza e le conclusioni sul workflow basato su AI.

## ⚠️ Note sull'Esecuzione e Sicurezza
Gli script presenti nella cartella `Eseguibili/` sono codice Python valido e lanciabile. Tuttavia, **il sistema non effettuerà la connessione al database** per i seguenti motivi di sicurezza:
1. Il file di configurazione Service Account di Firebase (`.json`) è stato rimosso per proteggere le credenziali del cloud.
2. La **Web API Key** necessaria per l'autenticazione non è inclusa nel codice pubblico.

**Per testare localmente:** È necessario creare un proprio progetto su Firebase, scaricare le credenziali e configurare il file come indicato nella documentazione dei prompt.

## 🛠️ Stack Tecnologico
* **Database & Auth:** Google Firebase (Firestore & Authentication)
* **Interfaccia Grafica:** CustomTkinter / Tkinter
* **AI Collaborator:** Claude (Anthropic) - Model: Sonnet 4.6
