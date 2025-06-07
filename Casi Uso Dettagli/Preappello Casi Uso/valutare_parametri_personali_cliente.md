# Caso d’Uso: ValutareParametriPersonaliCliente

| **Campo**                                | **Descrizione**                                                                                                                                                          |
|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nome Del Caso d’Uso**                  | ValutareParametriPersonaliCliente                                                                                                                                           |
| **Portata**                              | Gestione Palestra                                                                                                                                                         |
| **Livello**                              | Obbiettivo utente                                                                                                                                                         |
| **Attore Primario**                      | Trainer                                                                                                                                                                   |
| **Parti Interessate e Interessi**        | - **Trainer**: accede ai dati caricati dal Cliente e scrive commento complessivo e lista di attività suggerite |
| **Pre-condizioni**                       | - Il Cliente deve essere iscritto alla palestra <br> - Il Cliente deve aver compilato i parametri personali mensili relativi al proprio stato di salute e attività fisica svolta (peso, indice di massa corporea, frequenza cardiaca a riposo ed eventuali descrizioni di approfondimento) |
| **Garanzia di successo**                 | - La valutazione viene caricata nel sistema <br> - Il cliente riceve la valutazione                                                                                       |
| **Scenario principale di successo** | 1. Il Trainer Richiede i ParametriPersonali Del Cliente <br> 2. Il Trainer inserisce la valutazione sul parametro personale di interesse <br> 3. Il Sistema inserisce i parametri personali nel database e invia la conferma di inserimento  |
| **Estensioni**                           | - **3a** Il Sistema Fallisce nell'inserimento dei dati
| **Requisiti speciali**                   | - Aggiornamento database ogni volta che Trainer carica i dati                                                                                               |
| **Elenco variabili tecnologiche e dati** | - Il Trainer ha un’interfaccia per ricevere, commentare i dati e caricarli                                                                                                |
| **Frequenza di ripetizione**             | - Ogni volta che ci sono dei parametri personali disponibili da valutare                                                                        |
