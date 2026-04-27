# Me-and-Claude-K9-analysis-for-DPC-project
DPC riguarda lo sviluppo di un nuovo portale documentale e di collaboration che integra l’attuale sistema Protocollo del cliente.
Per un contesto di partenza sul progetto, sono da considerare i seguenti documenti:
- Soluzione Documentale [cliente] - SOW_v6_presentata.docx: Sow del portale da sviluppare
- PI TRE_Manuale di gestione.pdf: il manuale utente dell'attuale sistema Protocollo
- PI TRE WS_REST_01.04.pdf: le API dell'attuale soluzione Protocollo
<br>
Chiedo a Claude di esaminarli per una prima idea del progetto. In C.1 riporto la risposta di Claude.
<br>
Chiedo quindi a Claude di produrre una analisi di integrazione API protocollo ↔ portale: la riporto in 1. E riporto in C.2 le osservazioni di Claude durante la produzione dell'analisi.
<br><br>
Quindi, vengo al punto spinoso: l'analisi funzionale sulla ricerca avanzata.
<br><br>
Analizzando le fonti documentali a disposizione:<br>
- Matrice Strutturale delle Tipologie Documentali e dei Metadati (Sistema GeDoP).docx<br>
- Protocolli e Formati Documentali del Sistema PiTre GeDoP.docx<br>
- Metadati Tipologie Documentali Sistema GeDoP.xlsx<br>
- Matrice Visibilità_ Profilo Utente vs Natura del Contenuto.xlsx<br>
- Repo PITRe (protocollo usato da [cliente])<br>
- KB LLM PI.Tre (interna)<br>
<br>
non risulta chiaro:<br>
- quali sono le entità documentali da trattare, sia come oggetti ricercabili, che come elementi da indicizzare: le entità candidate sono il Fascicolo e il Documento (o Scheda documentale)<br>
- quale è il modello dati per le entità da trattare: metadati, domini, ecc - le fonti a disposizioni sono lacunose e/o contrastanti<br>
<br>
e questo rende difficoltoso progettare l'esperienza utente di ricerca e anche dare indicazioni sul disegno di un mockup per la SERP, che viene impostato come segue:<br>
<img width="1458" height="1056" alt="DPC-K9-SERP" src="https://github.com/user-attachments/assets/837dd048-e1e0-469b-a065-75d73090786d" />
<br><br>
Pertanto condivido a Claude:<br>
- Matrice Strutturale delle Tipologie Documentali e dei Metadati (Sistema GeDoP).docx<br>
- Metadati Tipologie Documentali Sistema GeDoP.xlsx<br>
- DPC Analisi funzionale OpenK9 2026-04-20 bozza.docx: la mia analisi funzionale che integra anche mie interazioni con la fonte "KB LLM PI.Tre"<br>
e chiedo:
<br><br>
*Ora devi focalizzare sulla funzione di ricerca avanzata da sviluppare nel nuovo portale grazie a OpenK9 (https://github.com/smclab/openk9). Mi occorre infatti una analisi funzionale e un disegno wireframe per proporre una SERP che implementi l'esperienza di ricerca ottimale per l'utente. Considera le ulteriori informazioni che mi sono state indicate, con particolare riguardo alle entità e al modello dati degli oggetti del sistema protocollo che devono essere resi ricercabili, previa opportuna indicizzazione, da parte di OpenK9. In allegato ci sono alcuni documenti di riferimento. Per la SERP, indicami quindi: cosa può ricercare l'utente, cosa può digitare sulla barra di ricerca, quali possibili filtri di ricerca ha senso implementare, se ci sono filtri implementabili con elenchi dropdown di valori, come può essere strutturata l'area con i risultati della ricerca.*
<br><br>
Claude risponde con l'analisi (PDF) - che riporto in 2 - e con un wireframe - che riporto in 3. 
<br>
In C.3 riporto anche tutte le osservazioni durante il task.
<br><br>
Domanda molto importante:
<br><br>
*Vedo che hai individuato tre tipi di oggetti ricercabili: fascicoli, schede e documenti. Quale è la differenza tra una scheda e un documento?*
<br><br>
Riporto la risposta in C.4.
<br><br>
Infine chiedo di ricreare un wireframe dark-mode più accattivante che riporto in 4 e (vista parziale) qui sotto.
<br>
<img width="2502" height="1304" alt="SERP-mockup-high" src="https://github.com/user-attachments/assets/4c51a7f5-f62e-4dee-bf66-146927f5ddbf" />








     


