# LUZON LIGHTING — luzonlight.com

Static web of **LUZON LIGHTING**, the commercial & industrial lighting
division of **LUZON GROUP**.

> Engineered light. Elevated spaces.
>
> Architectural elegance. Industrial performance.

## Stack

- Static HTML + CSS (Tailwind v4 compiled) + tiny JS runtime
- Brand palette: matte black / graphite / charcoal + LUZON orange `#e94e2c`
- Fonts: Tenor Sans (display) · Inter Tight (sans) · JetBrains Mono (mono) · CameraPlainVariable (display italic)
- Images: 6 cinematic scenes (lobby, façade, retail, office, warehouse, product hero) + LUZON logo

## Project layout

```
luzonlight-web/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── styles.css                          # Tailwind compiled CSS
    ├── app.js                              # JS runtime
    ├── routes.js                           # routing
    ├── logo-luzon.png                      # official LUZON LIGHTING logo
    ├── hero-lobby.jpg                      # luxury lobby
    ├── facade.jpg                          # premium architectural façade
    ├── retail.jpg                          # flagship retail
    ├── office.jpg                          # boardroom / corporate
    ├── warehouse.jpg                       # industrial high-bay
    ├── product-hero.jpg                    # luminaire studio shot
    └── fonts/
        ├── CameraPlainVariable.woff2
        └── CameraPlainVariableRegularItalic.woff2
```

## Run locally

```bash
# Just open the file
open index.html

# Or serve it (recommended — some browsers block module loading from file://)
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy

This is a fully static site. Any static host works:

- **Netlify** — drag-and-drop the folder, or connect this repo and pick the root as publish directory.
- **Vercel** — `vercel deploy --prod` from the project root.
- **Cloudflare Pages** — connect repo, build command empty, output directory `/`.
- **GitHub Pages** — push to `main`, then *Settings → Pages → Branch: main / Folder: /*.

## Brand

- Primary orange: **#e94e2c**
- Background graphite: **oklch(14% .005 60)**
- Text foreground: **oklch(95% .005 80)**
- Wordmark: `LUZON` (white) + `on` reinterpreted as a power button (orange) + `lighting` (white) + flame accent (orange)

© LUZON GROUP. LUZON LIGHTING™ is a trademark of LUZON GROUP.
