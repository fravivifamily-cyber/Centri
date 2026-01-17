# Modulo Centri UniPA (web)

Applicazione web (HTML/JS) per la compilazione degli Allegati relativi ai Centri UniPA, con:
- gestione pratica multi-allegato
- salvataggio locale (IndexedDB) inclusi PDF/JPEG
- generazione PDF Allegato e Fascicolo (copertina + indice + numerazione)
- esportazione/importazione pratica (ZIP)

## Pubblicazione (GitHub Pages)
1. Crea un repository su GitHub (es. `modulo-centri-unipa`)
2. Carica il contenuto di questa cartella nel repository (root)
3. Vai su **Settings → Pages**
4. Source: **Deploy from a branch**
5. Branch: `main` — Folder: `/ (root)`
6. Apri l’URL indicato da GitHub Pages (es. `https://<utente>.github.io/<repo>/`)

## Guida rapida
- `guida/Guida_rapida_Modulo_Centri_UniPA.pdf`

## Note importanti
- I dati sono salvati nel browser dell’utente (IndexedDB/localStorage).
- Se l’utente cancella i dati del sito o usa un browser diverso, i dati non saranno disponibili.
- Per trasferire una pratica tra persone/PC: usare “Esporta pratica” e poi “Importa pratica”.

## Supporto / Feedback
Per segnalazioni:
- indicare browser e versione (es. Safari 17.x, Chrome 1xx)
- descrivere i passaggi per riprodurre il problema
- allegare, se utile, lo ZIP prodotto da “Esporta pratica”
