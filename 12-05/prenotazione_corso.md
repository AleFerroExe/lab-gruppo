
| **Nome del Caso d'Uso**              | Prenotare un corso                                 |
|--------------------------------------|----------------------------------------------------|
| **Portata**                          | Il sistema di gestione della palestra permette ai clienti di prenotare un corso. |
| **Livello**                          | Obiettivo utente                                   |
| **Attore Primario**                  | Cliente                                            |
| **Parti Interessate e Interessi**    | - **Cliente**: desidera prenotare un corso.<br> - **Sistema**: gestisce la disponibilità dei corsi e la prenotazione. |
| **Pre-condizioni**                   | - Il cliente deve essere **iscritto** alla palestra e avere una **tessera** valida.<br> - I corsi devono essere disponibili nella fascia oraria scelta. |
| **Garanzia di Successo**             | - Il cliente ha prenotato con successo un corso specificato.<br> - Il sistema ha registrato la prenotazione nel proprio database. |
| **Scenario Principale di Successo**  | 1. Il cliente accede al sistema tramite la tessera.<br> 2. Il cliente seleziona il corso che desidera prenotare.<br> 3. Il sistema mostra l'elenco dei corsi disponibili, con l'orario e la disponibilità.<br> 4. Il cliente conferma la sua prenotazione per il corso scelto.<br> 5. Il sistema registra la prenotazione e conferma al cliente che è stato prenotato il corso. |
| **Estensioni**                       | - **Corso completo**: Se il corso è pieno, il sistema offre l'opzione di mettersi in lista d'attesa.<br> - **Modifica della prenotazione**: Il cliente può modificare la prenotazione fino a mezz'ora prima dell'inizio del corso.<br> - **Cancellazione della prenotazione**: Il cliente può cancellare la prenotazione fino a mezz'ora prima dell'inizio del corso. |
| **Requisiti speciali**               | - Il sistema deve verificare la disponibilità del corso prima di confermare la prenotazione.<br> - Il sistema deve essere accessibile in tempo reale da dispositivi mobili e desktop. |
| **Elenco delle variabili tecnologiche e dei dati** | - **Formato di ingresso**: Il cliente inserisce il suo identificativo tessera e sceglie un corso disponibile.<br> - **Formato di uscita**: Conferma della prenotazione con orario e data. |
| **Frequenza di ripetizione**         | Il cliente può prenotarsi a corsi su base regolare, a seconda della disponibilità. |
| **Varie**                            | - Il sistema deve garantire che tutte le prenotazioni siano gestite correttamente anche in caso di errori di connessione. |
