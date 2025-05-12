
| **Nome del Caso d'Uso**              | Acquistare un pacchetto ingressi                                 |
|--------------------------------------|----------------------------------------------------|
| **Portata**                          | Il sistema di gestione della palestra permette ai clienti di acquistare un pacchetto ingressi. |
| **Livello**                          | Obiettivo utente                                   |
| **Attore Primario**                  | Cliente                                            |
| **Parti Interessate e Interessi**    | - **Cliente**: desidera acquistare un pacchetto ingressi.<br> - **Sistema**: gestisce l'acquisto dei pacchetti. |
| **Pre-condizioni**                   | - Il cliente deve essere **iscritto** alla palestra e avere una **tessera** valida.<br> - Il cliente deve essere abilitato a fare acquisti. |
| **Garanzia di Successo**             | - Il cliente ha acquistato con successo un pacchetto ingressi.<br> - Il sistema ha registrato l'acquisto nel proprio database. |
| **Scenario Principale di Successo**  | 1. Il cliente accede al sistema tramite la tessera.<br> 2. Il cliente seleziona il pacchetto ingressi che desidera acquistare.<br> 3. Il sistema mostra i pacchetti disponibili e il relativo prezzo.<br> 4. Il cliente conferma l'acquisto del pacchetto scelto.<br> 5. Il sistema registra l'acquisto e conferma al cliente che il pacchetto ingressi è stato acquistato con successo. |
| **Estensioni**                       | - **Pagamento fallito**: Se il pagamento non va a buon fine, il sistema notifica l'errore al cliente e richiede un nuovo tentativo.<br> - **Pacchetto esaurito**: Se il pacchetto non è più disponibile, il sistema offre altri pacchetti. |
| **Requisiti speciali**               | - Il sistema deve verificare che il cliente abbia fondi sufficienti per l'acquisto del pacchetto.<br> - Il sistema deve essere accessibile in tempo reale da dispositivi mobili e desktop. |
| **Elenco delle variabili tecnologiche e dei dati** | - **Formato di ingresso**: Il cliente inserisce il suo identificativo tessera e seleziona il pacchetto.<br> - **Formato di uscita**: Conferma dell'acquisto con dettagli del pacchetto scelto e il prezzo pagato. |
| **Frequenza di ripetizione**         | Il cliente può acquistare pacchetti ingressi su base occasionale, a seconda delle necessità. |
| **Varie**                            | - Il sistema deve garantire che tutte le transazioni siano gestite correttamente anche in caso di errori di pagamento. |
