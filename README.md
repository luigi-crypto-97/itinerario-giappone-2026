# Giappone 2026 — Guida di viaggio 🇯🇵

Guida completa e personalizzata per 15 giorni fra **Osaka, Kyoto e Tokyo** (8–23 agosto 2026):
itinerario giorno per giorno, mappe interattive, tips, budget, frasi con pronuncia, curiosità e checklist.

**Guida online:** una volta attivato GitHub Pages, sarà visibile su
`https://<tuo-username>.github.io/giappone-2026/`

## Come pubblicare

1. Crea un repository su GitHub chiamato `giappone-2026` (pubblico).
2. Carica il contenuto di questa cartella (o push da terminale, vedi sotto).
3. Su GitHub: **Settings → Pages → Build and deployment → Source: "Deploy from a branch"**, branch `main`, cartella `/ (root)` → **Save**.
4. Dopo ~1 minuto la guida è online all'indirizzo indicato sopra.

## Push da terminale

```bash
cd giappone-2026
git init
git add .
git commit -m "Guida Giappone agosto 2026"
git branch -M main
git remote add origin https://github.com/<tuo-username>/giappone-2026.git
git push -u origin main
```

## Note

- Tutto è in un **unico file** (`index.html`): nessuna dipendenza da installare.
- Le mappe sono incorporate da Google Maps e si caricano dal browser del visitatore.
- Nessun dato sensibile (niente codici di prenotazione, PIN o contatti).
- Orari, prezzi e disponibilità vanno verificati sui canali ufficiali prima della partenza.
