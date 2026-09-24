# Làctics Foix · Propuestas de rediseño

Cuatro versiones de la landing page de Làctics Foix (Granja Cal Manyà, Torrelles de Foix) y una página índice para compararlas.

| Carpeta | Propuesta |
|---|---|
| `index.html` | Índice con capturas, resumen y comparativa |
| `v1-classica/` | Clàssica refinada: misma identidad, más clara y usable |
| `v2-fresca/` | Fresca i moderna: bento, filtros, FAQ, modo oscuro |
| `v3-artesana/` | Artesana de pagès: kraft, ilustración propia, proceso |
| `v4-botiga/` | Botiga i comanda: lista de encargo enviable por correo |
| `assets/img/` | Fotos de la granja optimizadas (JPG + WebP) |
| `assets/previews/` | Capturas usadas en el índice |

Sitio 100 % estático, sin build ni dependencias (solo Google Fonts).

## Publicar en GitHub Pages

```bash
git init && git add . && git commit -m "Propuestas web Làctics Foix"
git branch -M main
git remote add origin https://github.com/<usuario>/lactics-foix.git
git push -u origin main
```

Luego en GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`**.
La web quedará en `https://<usuario>.github.io/lactics-foix/`.

La carpeta `original/` (copia de la web actual, incluida `hero.jpg`) está excluida en `.gitignore` y no se publica.

## Probar en local

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Crèdits i llicències

- **Icones:** basades en [Lucide](https://lucide.dev) / [Feather](https://feathericons.com), llicència ISC / MIT. Text complet a `assets/LICENSE-icones.txt`.
- **Il·lustracions** (paisatge de la proposta 3, mapa il·lustrat, favicon): dibuixos originals fets per a aquestes propostes.
- **Tipografies:** Google Fonts (SIL Open Font License).
- **Fotos, textos, nom i logotip «lf»:** propietat de Làctics Foix · Granja Cal Manyà.
