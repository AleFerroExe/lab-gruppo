# Caso d’Uso: InserisciParametriPersonali

| **Campo**                                | **Descrizione**                                                                                                                                                          |
|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nome Del Caso d’Uso**                  | InserisciParametriPersonali                                                                                                                                              |
| **Portata**                              | Gestione Palestra                                                                                                                                                         |
| **Livello**                              | Obbiettivo utente                                                                                                                                                         |
| **Attore Primario**                      | Cliente                                                                                                                                                                   |
| **Parti Interessate e Interessi**        | - **Cliente**: Inserisce i suoi dati personali nel sistema  <br> - **Trainer**: Riceve i dati inseriti dal Cliente                                                       |
| **Pre-condizioni**                       | - Il Cliente deve avere un'iscrizione attiva in palestra                                                                                                                  |
| **Garanzia di successo**                 | - Il Cliente riceverà un commento e una lista di possibili attività da fare in palestra in seguito ai suoi dati personali inseriti                                       |
| **Scenario principale di successo**      | 1. Il Cliente accede al Sistema <br> 2. Il Cliente carica i dati <br> 3. Il Trainer eseguirà ValutaParametriPersonaliCliente <br> 4. Il Cliente riceve l’esito dai suoi dati |
| **Estensioni**                           | - **1a** Il Cliente non carica dati (fallimento) <br> - **4a** Il Cliente non riceve nulla (Il Cliente resta in attesa del commento)                                     |
| **Requisiti speciali**                   | - Aggiornamento database ogni volta che Trainer o Cliente caricano dati                                                                                                   |
| **Elenco variabili tecnologiche e dati** | - Interfaccia grafica per il cliente per poter caricare i dati e ricevere le valutazioni                                                                                 |
| **Frequenza di ripetizione**             | - Mensile con possibilità di interruzione in qualsiasi momento                                                                                                            |
