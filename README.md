# Cucina – PWA (versione 1.5)

La PWA conserva il ricettario della versione 1.4: Dolce/Salato, ingredienti modificabili, **Adatta quantità** (aggiorna l’elenco superiore senza alterare la ricetta originale), **Ripristina originale**, note per ricetta e backup JSON.

## Pubblicazione con GitHub Pages
1. Crea un repository GitHub nuovo, ad esempio `cucina`.
2. Carica **tutti i file presenti in questa cartella** nella radice del repository (non caricare solo lo ZIP).
3. Vai in **Settings → Pages → Build and deployment**, scegli **Deploy from a branch**, seleziona `main` e `/ (root)`, poi salva.
4. Apri l'indirizzo pubblicato da Pages, di solito `https://TUO-USERNAME.github.io/cucina/` (sostituisci lo username e il nome del repository).
5. Su Android, aprilo in Chrome e scegli **Installa app** / **Aggiungi a schermata Home** dal menu.

La PWA richiede HTTPS per installazione e offline; non basta aprire `index.html` come file locale. Dopo la prima visita online l'app funziona offline.

**Dati:** le ricette modificate sono salvate nel browser del dispositivo, non sincronizzate tra PC e telefono. Prima di cambiare dispositivo, eliminare dati del browser o cambiare indirizzo web, esporta un **Backup**; poi usa **Importa** sull’altro dispositivo. Il backup non viene caricato su GitHub automaticamente.

**Valori nutrizionali:** nessun valore non verificato è stato inventato. Ricette incomplete sono segnalate nell'app.
