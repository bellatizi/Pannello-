# App Pannello Arrampicata

Web app leggera (HTML/JS) per mappare, salvare e condividere vie su un pannello di arrampicata. Nessun database server richiesto (usa il `localStorage` del browser).

## File del progetto

*   **`index.html` (App Creatore):** Applicazione completa per tracciare nuove vie, salvarle ed esportarle. Da usare privatamente.
*   **`blocchi.html` (App Lettore):** Versione in sola lettura. Contiene le vie pre-caricate nel codice. Ideale da associare al QR Code in palestra.
*   **`fotopannello.png`**: Immagine di sfondo del muro.

## Come usare `index.html`

L'interfaccia permette di cliccare le prese sulla foto per evidenziarle. 

**Guida ai tasti:**
*   **Salva nel Menu:** Salva la via disegnata (con nome e grado) nella memoria del tuo browser (locale).
*   **Genera Link Via Corrente:** Crea un link web (URL) per condividere al volo *solo* la via che stai visualizzando in quel momento.
*   **Elimina Selezionata:** Rimuove la via dal tuo menu a tendina.
*   **Esporta Vie:** Scarica un file `.json` (un backup leggerissimo) contenente tutte le tue vie salvate.
*   **Importa Vie:** Carica un file `.json` (tuo o di un amico) per aggiungere nuove vie al tuo menu a tendina.
