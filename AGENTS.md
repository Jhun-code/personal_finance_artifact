# AGENTS.md

## Objectif du projet
Application web monopage (SPA) de gestion et de suivi de finances personnelles interactif.
Elle permet d'enregistrer des transactions (revenus et dépenses par catégorie), de visualiser la répartition des dépenses avec un graphique interactif (Chart.js), de suivre des objectifs de budget mensuel et de persister les données localement via `localStorage`.

## Conventions de code
- **Technologies** : HTML5, CSS3 Vanilla (avec variables CSS), JavaScript ES6+ Vanilla, Chart.js via CDN.
- **Structure** : Application autonome (CSS dans `<style>`, JS dans `<script>` à l'intérieur de `index.html`).
- **Langue** : Interface et commentaires en français (`lang="fr"`).
- **Style & Thème** : Utilisation de variables CSS centralisées dans `:root` (`--bg`, `--card`, `--primary`, `--income`, `--expense`, `--warning`, etc.) et mise en page responsive via CSS Grid / Flexbox.
- **Gestion d'état** : État local géré en mémoire et synchronisé avec `localStorage` (`transactions` et `budgets`).

## Commande de test
Aucune suite de tests automatisés n'est actuellement configurée dans le dépôt.
- **Test visuel et manuel** : Servir le fichier `index.html` via un serveur HTTP local (ex: `python3 -m http.server 8000` ou `npx serve .`) et vérifier le fonctionnement dans un navigateur web.

## Fichiers autorisés
- `index.html` (code source principal de l'application)
- `README.md` (documentation générale du projet)
- `AGENTS.md` (directives et consignes pour les agents IA)
