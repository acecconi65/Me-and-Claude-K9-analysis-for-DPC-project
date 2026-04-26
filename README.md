# Me-and-Claude-K9-analysis-for-DPC-project
DPC riguarda lo sviluppo di un nuovo portale documentale e di collaboration che integra l’attuale sistema Protocollo del cliente.
Per un contesto di partenza sul progetto, sono da considerare i seguenti documenti:
- Soluzione Documentale Protezione Civile - SOW_v6_presentata.docx: Sow del portale da sviluppare
- PI TRE_Manuale di gestione.pdf: il manuale utente dell'attuale sistema Protocollo
- PI TRE WS_REST_01.04.pdf: le API dell'attuale soluzione Protocollo
<br>
Chiedo a Claude di esaminarli per una prima idea del progetto. In C.1 riporto la risposta di Claude.
<br>
Chiedo quindi a Claude di produrre una analisi di integrazione API protocollo ↔ portale: la riporto in 1. E riporto in C.2 le osservazioni di Claude durante la produzione dell'analisi.
<br>
Quindi, vengo al punto spinoso: l'analisi funzionale sulla ricerca avanzata.
Analizzando le fonti documentali a disposizione:
- Matrice Strutturale delle Tipologie Documentali e dei Metadati (Sistema GeDoP).docx
- Protocolli e Formati Documentali del Sistema PiTre GeDoP.docx
- Metadati Tipologie Documentali Sistema GeDoP.xlsx
- Matrice Visibilità_ Profilo Utente vs Natura del Contenuto.xlsx
- Repo PITRe (protocollo usato da Protezione Civile): https://github.com/ProvinciaAutonomaTrento/PITre
- KB LLM PI.Tre (interna SMC): https://notebooklm.google.com/notebook/22109c44-2f97-4822-bfde-40004d39a792?pli=1
<br>
non risulta chiaro:
- quali sono le entità documentali da trattare, sia come oggetti ricercabili, che come elementi da indicizzare: le entità candidate sono il Fascicolo e il Documento (o Scheda documentale)
- quale è il modello dati per le entità da trattare: metadati, domini, ecc - le fonti a disposizioni sono lacunose e/o contrastanti
<br>
e questo rende difficoltoso progettare l'esperienze utente di ricerca e anche dare indicazioni sul disegno di un mockup per la SERP
