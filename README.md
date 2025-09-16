# General Detector Helper (PWA)

Questa è la versione PWA dell'app **General Detector Helper**.

## Come pubblicarla su GitHub Pages

1. Crea un nuovo repository pubblico su GitHub (es. `general-detector-helper`).
2. Carica direttamente nella root del repo i seguenti file:
   - index.html
   - sw.js
   - manifest.webmanifest
   - icon-gd-192.png
   - icon-gd-512.png
   - LICENSE
   - README.md
3. Vai in Settings → Pages → seleziona branch `main` e cartella `/root` → Save.
4. Attendi 2-3 minuti, poi apri l'URL:
   ```
   https://TuoNomeUtente.github.io/general-detector-helper/
   ```
5. Sul telefono apri l'URL e fai “Aggiungi a schermata Home”.

L'app funzionerà **offline** e userà la libreria privata `general-detector-lib`.
