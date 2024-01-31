## **MercaLibri Unitn**
Benvenuti nell'organizzazione del progetto *MercaLibri Unitn*, sviluppato nel contesto del corso di Ingegneria del Software presso l'Università degli Studi di Trento (a.a. 2022/2023). Il progetto consiste nel realizzare il sito web *MercaLibri Unitn* per la compravendita di libri tra gli studenti dell’Università di Trento.

In questa organizzazione sono presenti i documenti di progetto e tutti i file coinvolti nella realizzazione del progetto.

*MercaLibri Unitn* è disponibile al seguente URL: <https://merca-libri-unitn-31e0f9ac1d17.herokuapp.com/>.  
Si noti che il sistema sarà disponibile fino alla scadenza del deployment.

### **Membri del Team**
- Enrico Cescato
- Matteo Sottocornola

### **Tecnologie utilizzate**
- **Node.js**: usato per lo sviluppo del backend;

- **CSS**: usato per definire stile e presentazione delle pagine web;

- **HTML**: usato per strutturare le pagine web;

- **Vue.js**: usato per lo sviluppo del frontend;

- **Jest**: usato per testare la WebApp;

- **Markdown**: usato per la stesura dei documenti di progetto;

- **Swagger**: tool usato per la documentazione delle API;

- **MongoDB**: database usato per la gestione dei dati nel backend;

- **Visual Studio Code**: code editor usato per lo sviluppo del progetto;

- **Postman**: development environment usato per testare e verificare la correttezza delle API;

- **Heroku**: deployment platform usata per distribuire la WebApp.

### ***Nota tecnica***
Per ragioni tecniche, è stato deciso di implementare la procedura di autenticazione direttamente all'interno del sistema MercaLibri Unitn, anziché aderire alla procedura originariamente prevista tramite la pagina Unitn Login.
Si noti che gli utenti sono stati preregistrati nel database del sistema con gli indirizzi e-mail Unitn.

Gli utenti salvati nel database hanno tutti l'indirizzo e-mail della forma *nome.cognome@studenti.unitn.it* (tutto in minuscolo) e password *1234*. Alcuni utenti salvati sono i seguenti:

- Marco Gialli;
- Anna Neri;
- Mario Rossi.

### **API documentation**
La documentazione delle API tramite *Swagger* è disponibile al seguente URL: <https://merca-libri-unitn-31e0f9ac1d17.herokuapp.com/api-docs>. Per poter utilizzare le API, è necessario specificare lo schema *https*.
