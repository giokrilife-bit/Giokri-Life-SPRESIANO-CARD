# GiOKri Loyalty V1

Prima PWA demo per il progetto loyalty dei negozi di Spresiano.

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository GitHub, ad esempio `giokri-loyalty`.
2. Carica `index.html`, `manifest.json` e `icon.svg` nella cartella principale.
3. Vai in **Settings → Pages**.
4. In **Build and deployment** seleziona **Deploy from a branch**.
5. Seleziona `main` e `/ (root)`.
6. Salva.
7. Apri l'indirizzo GitHub Pages del repository dallo smartphone.
8. Dal browser scegli **Aggiungi alla schermata Home**.

## Cosa fa questa V1

- Home con saldo punti
- Regola 1 euro = 1 punto
- Registrazione acquisto
- Selezione negozio
- Foto dello scontrino
- Storico acquisti
- Obiettivi punti
- Premi dimostrativi
- Elenco dei primi 10 negozi
- Profilo cliente
- Interfaccia mobile/PWA

## Importante

Questa è una V1 dimostrativa: i dati sono salvati nel `localStorage` del dispositivo e non sono condivisi con GiOKri Life.

Nella V2 si potrà collegare Supabase per:
- account reali
- database centrale
- gestione scontrini
- verifica da parte di GiOKri Life
- punti reali
- premi
- pannello amministratore
- statistiche dei negozi
- prevenzione dei duplicati/frode
