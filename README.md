# App Gestione Patrimonio

Questa semplice applicazione web permette di creare e gestire conti con un nome, dei tag associati e un registro di transazioni. I dati sono salvati nel `localStorage` del browser, quindi non è richiesto alcun backend.

## Come usare

1. Apri `index.html` in un browser moderno.
2. Usa la barra di navigazione per passare alle pagine **Dashboard**, **Statistiche** e **Transazioni**.
3. In **Dashboard** trovi il riepilogo dei conti e le ultime operazioni.
4. In **Statistiche** puoi visualizzare grafici dinamici scegliendo l'intervallo temporale (1 settimana, 1 mese, 6 mesi o 1 anno).
5. Nella pagina **Transazioni** gestisci il registro completo e puoi aggiungere nuovi movimenti.
6. Nell'homepage compila il form indicando il **Nome del Conto** e, facoltativamente, una serie di **tag** separati da virgola, quindi clicca **Aggiungi Conto**.
7. Premi **Inserisci Transazione** per registrare un movimento su un conto. Oltre a conto, importo e tipo (entrata/uscita) viene richiesta anche la **data** dell'operazione, la **categoria** e una descrizione facoltativa.
8. Ogni card mostra il saldo aggiornato e può essere eliminata tramite il pulsante *Elimina*.

L'interfaccia è basata su [Bootstrap 5](https://getbootstrap.com/).
È disponibile una modalità **dark** attivabile tramite l'apposito interruttore nella navbar.

## Categorie disponibili

Le transazioni possono essere classificate scegliendo una di queste categorie:

- 🍔 Cibo
- 🛍️ Shopping
- 🏠 Casa
- 🚍 Trasporti
- 🚗 Veicoli
- 🎮 Intrattenimento
- 💻 Comunicazione PC
- 💳 Spese Finanziarie
- 📈 Investimenti
