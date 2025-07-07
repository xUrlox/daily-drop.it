# README.md
```
# daily-drop.it Static Site
Questo repository contiene il template per il micro-sito "DailyDrop.it" da pubblicare con GitHub Pages.

## Struttura
- `index.html`: pagina principale con tre bottoni di link affiliati.

## Setup GitHub Pages
1. Crea un nuovo repository pubblico chiamato `daily-drop.it`.
2. Copia questo contenuto nel repo.
3. Esegui commit & push su `main`.
4. Vai su Settings → Pages → Branch: `main` → `/ (root)` → Save.
5. Il sito sarà live in `https://<tuo-username>.github.io/daily-drop.it`.

## Personalizzazione
- Sostituisci i placeholder `XXXXXXXX` con i tuoi codici affiliato Amazon.
- Puoi aggiungere CSS custom in `<style>` o creare `style.css`.
```

---

<!-- index.html -->
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DailyDrop.it – Top Gadget</title>
  <style>
    body { font-family: sans-serif; background: #f4f4f4; color: #333; padding: 2rem; text-align: center; }
    h1 { margin-bottom: 0.5rem; }
    p { margin-bottom: 1.5rem; }
    .btn { display: block; margin: 1rem auto; padding: 0.8rem 1.2rem;
           background: #0073e6; color: #fff; text-decoration: none;
           border-radius: 0.5rem; width: 80%; max-width: 300px; }
    .btn:hover { background: #005bb5; }
  </style>
</head>
<body>
  <h1>DailyDrop.it</h1>
  <p>3 gadget geniali sotto i 30€</p>
  <a class="btn" href="https://amzn.to/3XXXXXXXX1" target="_blank">Dispenser dentifricio</a>
  <a class="btn" href="https://amzn.to/3XXXXXXXX2" target="_blank">Mini aspirapolvere USB</a>
  <a class="btn" href="https://amzn.to/3XXXXXXXX3" target="_blank">Organizer cavi magnetico</a>
</body>
</html>
