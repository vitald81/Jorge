# Directives du projet

## Création de sites web / interfaces

Pour tout site, landing page, page ou composant d'interface, utiliser les skills installés dans `.claude/skills/` :

1. **`design-taste-frontend`** (taste-skill) — point de départ pour construire un site : système de mise en page, hero, sections, assets prêts à l'emploi. Suivre son `SKILL.md` (démarrer depuis `assets/starter.html`).
2. **`ui-ux-pro-max`** — choisir le design system (style, palette, typographies) selon le type de produit :
   `python3 .claude/skills/ui-ux-pro-max/scripts/search.py "<type de produit> <secteur>" --design-system -p "<Nom>"`
3. **`impeccable`** — critique, audit et finition (`audit`, `critique`, `polish`, `typeset`, `layout`…) avant de livrer.
4. **Skills d'Emil Kowalski** — animations et finesse d'interaction :
   - `emil-design-eng` (principes de design engineering), `animate`, `choreograph`, `improve-animations`, `review-animations`, `animation-performance`, `find-animation-opportunities`
   - `pick-ui-library`, `prototype`, `break-ui` (tests de robustesse de l'UI), `apple-design`

Ordre de travail : design system (ui-ux-pro-max) → construction (design-taste-frontend) → animations (skills Emil) → audit et polish (impeccable) → vérification accessibilité/responsive.

## Serveur MCP

- `21st` (`.mcp.json`) — recherche et récupération de composants 21st.dev. Nécessite la variable d'environnement `API_KEY_21ST` (clé sur https://21st.dev/settings/api-keys).
