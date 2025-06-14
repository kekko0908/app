# App Gestione Patrimonio

Questa semplice applicazione web permette di creare e gestire conti con un nome, dei tag associati e un registro di transazioni. I dati sono salvati nel `localStorage` del browser, quindi non è richiesto alcun backend.

## Come usare

1. Apri `index.html` in un browser moderno.
2. Compila il form indicando il **Nome del Conto** e, facoltativamente, una serie di **tag** separati da virgola.
3. Clicca su **Aggiungi Conto** per visualizzare il nuovo conto nella lista.
4. Premi **Inserisci Transazione** per registrare un movimento su un conto. Verrà richiesto il conto di destinazione, l'importo, il tipo (entrata/uscita) e una descrizione facoltativa.
5. Ogni card mostra il saldo aggiornato e può essere eliminata tramite il pulsante *Elimina*.

L'interfaccia è basata su [Bootstrap 5](https://getbootstrap.com/).
