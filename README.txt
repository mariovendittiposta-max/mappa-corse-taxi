TAXI LOMBARDIA - PROTOTIPO PWA

Contenuto:
- index.html: applicazione web
- manifest.json: impostazioni installazione PWA
- sw.js: service worker
- icon.svg: icona

FUNZIONI:
- ricerca località con OpenStreetMap Nominatim
- percorso stradale, km e tempo stimato con OSRM
- mappa Leaflet/OpenStreetMap
- inverti partenza/destinazione
- località rapide
- preferiti salvati sul dispositivo
- elenco destinazioni per raggio (distanza in linea d'aria)

IMPORTANTE:\nPer installare su iPhone come app, i file devono essere pubblicati su un sito HTTPS.
Il prototipo usa servizi pubblici OpenStreetMap/Nominatim e OSRM, quindi necessita Internet.
I servizi pubblici hanno limiti di utilizzo e non sono garantiti per uso commerciale o intenso.
Non aprire index.html direttamente come file locale per testare tutte le funzioni: pubblicarlo prima su HTTPS.

PUBBLICAZIONE SEMPLICE (GitHub Pages):
1. Crea un account GitHub, se non ne hai uno.
2. Crea un repository nuovo chiamato taxi-lombardia.
3. Carica index.html, manifest.json, sw.js e icon.svg nella root del repository.
4. Repository Settings > Pages > Deploy from branch > main > /(root) > Save.
5. Attendi che GitHub Pages mostri il link HTTPS.
6. Apri il link da Safari su iPhone > Condividi > Aggiungi alla schermata Home.

Nota: per una versione stabile destinata a uso professionale, conviene usare un provider di routing/geocoding con API key e limiti/condizioni adeguati.
