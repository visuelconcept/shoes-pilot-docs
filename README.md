# Shoes Pilot — Documentation utilisateur

Site de **documentation utilisateur** de Shoes Pilot (MES de suivi de production
pour usines de chaussures), construit avec [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

> 📖 Site publié : **https://visuelconcept.github.io/shoes-pilot-docs/**

Ce dépôt **public** ne contient **que la documentation** (pas de code
applicatif). Le code de l'application vit dans le dépôt privé
`visuelconcept/shoes-pilot-asf40`.

## Contenu

```
mkdocs.yml             Configuration du site (thème, i18n FR/PT, navigation)
requirements-docs.txt  Dépendances Python (MkDocs Material, plugins)
user-docs/             Pages du site
  index.md             Accueil  (.pt.md = version portugaise)
  prise-en-main/       Rôles & accès, connexion
  operateur/           Parcours opérateur (pointage)
  superviseur/         Parcours superviseur (rebut, supervision, opérateurs)
  administration/      Parcours admin (étiquettes, export, postes)
  assets/screenshots/  Captures d'écran (fr/ et pt/)
```

Le site est **bilingue FR / PT** (plugin `mkdocs-static-i18n`, suffixe `.pt.md`).

## Aperçu local

```bash
python -m venv .venv
.venv/Scripts/activate        # Windows  (source .venv/bin/activate sous Unix)
pip install -r requirements-docs.txt
mkdocs serve                  # http://127.0.0.1:8000
```

## Déploiement

À chaque push sur `main`, GitHub Actions build le site et le publie sur GitHub
Pages (`.github/workflows/docs.yml`). Pré-requis une seule fois :
**Settings → Pages → Source : GitHub Actions**.

## Captures d'écran

Les captures sont **générées automatiquement** par la suite de tests Playwright
(`e2e/`) du dépôt applicatif privé, à partir de l'application en fonctionnement
avec données de démo. Elles sont ensuite copiées dans `user-docs/assets/screenshots/`.

Tant que la première génération n'a pas eu lieu, des **placeholders** unis
occupent ces emplacements. Procédure de génération : voir le `e2e/README.md` du
dépôt applicatif.
