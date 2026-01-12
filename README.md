# intro_devops

Découverte des github actions

## ViteJS Hello World Application

Ce projet est une application ViteJS Hello World avec un pipeline CI/CD configuré.

## Pipeline CI

Le pipeline CI s'exécute dans l'ordre suivant :

1. **Lint** - Vérification du code avec ESLint
2. **Format** - Vérification du formatage avec Prettier
3. **Snyk** - Analyse de sécurité des dépendances

## Scripts disponibles

- `npm run dev` - Lance le serveur de développement
- `npm run build` - Build l'application pour la production
- `npm run preview` - Prévisualise le build de production
- `npm run lint` - Vérifie le code avec ESLint
- `npm run format` - Vérifie le formatage avec Prettier
- `npm run format:fix` - Corrige automatiquement le formatage
- `npm run snyk` - Lance l'analyse de sécurité Snyk

## Installation

```bash
npm install
```

## Développement

```bash
npm run dev
```

## Configuration Snyk

Pour utiliser Snyk dans le pipeline CI, vous devez configurer le secret `SNYK_TOKEN` dans les paramètres de votre repository GitHub.
