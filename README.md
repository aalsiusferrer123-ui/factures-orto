# Facturació — Ortopèdia (app d'escriptori)

L'aplicació (`app/index.html`) empaquetada amb Electron com a app instal·lable.

## Enllaços de descàrrega (sempre la darrera versió)

- **Windows:** https://github.com/aalsiusferrer123-ui/factures-orto/releases/latest/download/Facturacio-Ortopedia-Setup.exe
- **Mac:** https://github.com/aalsiusferrer123-ui/factures-orto/releases/latest/download/Facturacio-Ortopedia-Mac.dmg

> Aquests enllaços només funcionen per a tothom si el repositori és **públic**.

### Primera obertura
L'instal·lador no està signat digitalment:
- **Windows:** si surt "Windows ha protegit l'equip", clica *Més informació → Executa igualment*.
- **Mac:** clic dret sobre l'app → *Obrir* → *Obrir* (només la primera vegada).

## Actualitzar l'app
Substitueix `app/index.html` per la nova versió i fes push a `main`: GitHub Actions
genera els instal·ladors i publica una nova *Release* automàticament.

## Desenvolupament
```
npm install
npm start          # obre l'app
npm run dist:win   # genera l'instal·lador de Windows a dist/
```

Les dades (pacients, factures…) es guarden localment a cada ordinador.
