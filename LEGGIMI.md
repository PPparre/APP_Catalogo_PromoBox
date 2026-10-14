# Catalogo espositori: installazione come app

Questa cartella è un'app web installabile (PWA). Per installarla sul telefono deve stare online su un indirizzo HTTPS.

## 1. Pubblicare su GitHub Pages
1. Crea un repository su GitHub (anche privato se il tuo piano lo consente per Pages) e carica **tutti** i file di questa cartella, mantenendo la cartella `icons`.
2. Vai in *Settings → Pages*, scegli *Deploy from a branch*, ramo `main`, cartella `/ (root)`, poi *Save*.
3. Dopo un minuto circa l'app è raggiungibile all'indirizzo `https://TUOUTENTE.github.io/NOMEREPOSITORY/`.

## 2. Installare sul telefono
- **iPhone (Safari)**: apri l'indirizzo, tocca *Condividi* → *Aggiungi alla schermata Home*.
- **Android (Chrome)**: apri l'indirizzo, tocca il menu ⋮ → *Installa app* (o *Aggiungi a schermata Home*).

L'icona "Expo" compare nella schermata Home e l'app si apre a schermo intero, senza barra del browser.

## 3. Aggiornamenti
Per aggiornare il catalogo sostituisci `index.html` su GitHub: l'app si aggiorna da sola alla prima apertura con connessione.
Senza rete l'app resta usabile con l'ultima versione scaricata.

## Nota di sicurezza
I PIN degli agenti sono scritti dentro `index.html`: chi riceve il file o l'indirizzo può leggerli. Per una protezione reale i PIN e i dati devono stare su un server.
