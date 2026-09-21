LUMINARPLUS — SITO V3

Questa versione contiene:
- index.html
- cartella assets con tutte le immagini usate dal sito
- logo Luminarplus
- .nojekyll per GitHub Pages
- telefoni ufficiali
- WhatsApp ufficiale
- Instagram ufficiale

IMPORTANTE PER LE IMMAGINI SU GITHUB:
NON caricare solo il file ZIP dentro GitHub.
Devi estrarre il contenuto del ZIP e caricare:
    index.html
    .nojekyll
    assets/
        luminarplus-logo.png
        hero.jpg
        project-*.jpg

La cartella "assets" deve stare NELLO STESSO LIVELLO di index.html.

Struttura corretta:
luminarplus.github.io/
├── index.html
├── .nojekyll
└── assets/
    ├── luminarplus-logo.png
    ├── hero.jpg
    ├── project-arch.jpg
    └── ...

Se su GitHub hai solo index.html, le immagini NON possono essere trovate.

Il sito usa percorsi relativi come:
assets/hero.jpg
assets/project-arch.jpg

Questi funzionano quando la cartella assets è presente accanto a index.html.
GitHub Pages richiede che index.html sia nella radice della sorgente pubblicata (o nella cartella docs se hai configurato docs come sorgente).
