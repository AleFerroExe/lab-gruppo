# Caso d’Uso: CompilareQuestionario

| **Campo**                                | **Descrizione**                                                                                                                                                          |
|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nome caso d'uso**                      | CompilareQuestionario                                                                                                                                                       |
| **Portata**                              | Gestione palestra                                                                                                                                                         |
| **Livello**                              | Obbiettivo utente                                                                                                                                                         |
| **Attore primario**                      | Cliente                                                                                                                                                                   |
| **Parti interessate e interessi**        | - **Cliente**: Una volta ricevuto il questionario può decidere se compilarlo <br>          |
| **Pre-condizioni**                       | - L’amministratore ha inviato un questionario <br> - Il cliente accede al sistema <br> - Il cliente riceve il questionario                                             |
| **Garanzia di successo**                 | - Il cliente compila ed invia il questionario                                                                                                                              |
| **Scenario principale di successo**      | 1. Il Cliente accede al sistema <br> 2. Il Cliente compila il questionario <br>  3. Il sistema registra le informazioni <br> 4. Il client riceve lo sconto <br> |
| **Estensione**                           | - **3a** Non tutti i campi obbligatori sono stati compilati (compila dati mancanti) <br> - **4a** I dati non sono stati caricati (fallimento)                            |
| **Requisiti speciali**                   | - Il cliente riceve lo sconto del 5% <br> - Il sistema deve essere accessibile in tempo reale da dispositivi mobili e desktop                                            |
| **Elenco delle variabili tecnologiche e dati** | - Interfaccia utente: inserimento dati nel questionario. <br> - Output conferma: Conferma dati inseriti                                                                  |
| **Frequenza di ripetizione**             | - Ogni volta che l’amministratore invia un questionario                                                                                                                    |
