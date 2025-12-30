# scherzo

Progetto minimale per eseguire la pagina "Sito Assolutamente Affidabile" localmente.

Requisiti
- Node.js (versione moderna) o aprire direttamente `index.html` in un browser.

Esecuzione (consigliata, server locale):

```bash
cd /Users/patrickbressan/Desktop/Progetti/scherzo
npm start
# poi aprire http://localhost:3000
```

Se preferisci usare Python (nessun server Node):

```bash
# Python 3
cd /Users/patrickbressan/Desktop/Progetti/scherzo
python3 -m http.server 3000
# poi aprire http://localhost:3000
```

File principali:
- `index.html` — la pagina principale (contenuto fornito)
- `server.js` — semplice server statico Node
- `package.json` — script `npm start`
