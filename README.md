# E.D.G. Construcción — Corporate Landing & Portfolio

Official website and digital portfolio for **E.D.G. Construcción**, a specialized Paraguayan general contracting and civil engineering firm based in Fernando de la Mora, Paraguay.

## Overview

- **Firm:** E.D.G. Construcción
- **General Director & Owner:** Esteban Dávalos González (RUC: `5348627-7`)
- **Technical Supervision:** Ing. Civil Aracely Bericua
- **Address:** 11 de Setiembre c/ Isla Po'i, Fernando de la Mora, Central, Paraguay
- **Contact:** `+595 981 353 858` · `dabalozesteban@gmail.com`

## Featured Projects in Portfolio

1. **Hormetal Paraguay** — Heavy reinforced concrete retaining walls and bulkheads.
2. **Punto Farma Logistic Hub (Ñemby)** — 2,500 m² waffle slab (losa casetonada) for **Tecinci S.A.**
3. **Villa Morra Gastronomic Complex (Asunción)** — Reinforced concrete commercial structure on Malutín street for **Empropar S.A.**
4. **Gated Community Residences (Buenos Aires)** — Gray-work structural framing with classic concrete moldings and fair-faced slabs.
5. **Procrear Urban Development (San Antonio de Areco)** — Climbing modular formwork and structural slabs.
6. **Sárraga Residential Building (Villa Ortúzar, CABA)** — Multi-story reinforced concrete residential tower.
7. **Campo Aguará Estate (Lincoln)** — Modern cantilevered concrete galleries and rural infrastructure.

## Project Structure

```
edg-construccion/
├── assets/
│   └── images/
│       ├── hormetal_tabique.jpg
│       ├── punto_farma_casetonado.jpg
│       ├── villa_morra_obra.jpg
│       ├── country_obra_gris.jpg
│       ├── procrear_encofrados.jpg
│       ├── sarraga_altura.jpg
│       ├── campo_aguara.jpg
│       └── logo_original.jpg
├── index.html              # Main production page with relative asset paths
├── index-standalone.html   # Standalone version with inlined assets for zero-dependency previews
├── README.md               # Project documentation
└── .gitignore
```

## Deployment & Hosting

### Option 1: GitHub Pages
1. Push this repository to GitHub.
2. Navigate to **Settings > Pages**.
3. Under **Build and deployment**, select **Source: Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` directory, then click **Save**.

### Option 2: Local Preview
Open `index.html` directly in any modern web browser or run:
```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .
```
