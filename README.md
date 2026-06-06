# Kaktus Dizajn — 3D Portfolio (Aleksa Jovanović)

Interaktivni 3D portfolio (Three.js). Sadržaj foldera:
- `portfolio-3d.html` — sajt
- `img/` — sve slike (coveri, brend book strane, mockup-ovi, social radovi)

## Postavljanje na GitHub Pages

1. U repo (npr. `kaktusdizajn`) napravi folder, npr. `portfolio/`.
2. Ubaci `portfolio-3d.html` i ceo `img/` folder u taj folder (moraju ostati zajedno).
3. Commit + push na `main`.
4. GitHub → Settings → Pages → Source: `main` / root (ili `/docs` ako tako koristiš).
5. Sajt: `https://<korisnik>.github.io/<repo>/portfolio/portfolio-3d.html`
   - Ako hoćeš čist URL, preimenuj `portfolio-3d.html` u `index.html` → `.../portfolio/`.

## VAŽNO — kako se testira lokalno
Ne otvaraj duplim klikom (`file://`) — neke teksture i 3D tada ne rade.
Pokreni mali server u folderu pa otvori u browseru:

    python -m http.server 8000

pa idi na `http://localhost:8000/portfolio-3d.html`

## Napomena
3D (WebGL) ne radi u nekim ugrađenim/preview okruženjima — na pravom serveru (GitHub Pages, localhost) se prikazuje normalno. Najbolje u Chrome/Edge/Firefox.
