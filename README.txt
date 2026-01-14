Calcolo Orari — PWA (App su iPhone)

1) Requisito fondamentale:
   - Deve essere pubblicata su un server HTTPS (non funziona come “file locale” su iPhone).
     Esempi: GitHub Pages, Netlify, Vercel, un tuo sito con HTTPS.

2) Pubblicazione:
   - Carica TUTTI i file di questa cartella mantenendo la struttura:
     - index.html
     - manifest.webmanifest
     - sw.js
     - /icons/...

3) Installazione su iPhone (aggiunta su Home):
   - Apri l’URL della pagina con Safari (non Chrome).
   - Tocca Condividi (icona quadrato con freccia).
   - Seleziona “Aggiungi a Home”.
   - Conferma il nome e premi “Aggiungi”.
   - L’icona apparirà sul desktop e si aprirà a schermo intero (standalone).

Note:
- Le icone in /icons sono placeholder. Puoi sostituirle con le tue (PNG):
  icon-192.png (192x192), icon-512.png (512x512), apple-touch-icon.png (180x180)
