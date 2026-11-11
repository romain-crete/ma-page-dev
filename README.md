# Ma page de développeur

Page de présentation professionnelle de Romain CRÉTÉ, concepteur développeur d'applications en formation : profil, compétences et projets. HTML et Tailwind CSS 4, construite avec Vite.

## Installation et lancement

Prérequis : Node.js (LTS) et Git.

- `npm install` : installer les dépendances
- `npm run dev` : lancer le serveur de développement (http://localhost:5173)
- `npm run build` : construire le site pour la production dans `dist/`
- `npm run lint` et `npm run format:check` : vérifier la qualité et le formatage du code

## Mon poste

- PC portable HP (24 Go RAM DDR5, 1 To SSD)
- Système d'exploitation : Windows 11
- Terminal : Git Bash
- Éditeur : VS Code avec extensions (Prettier, ESLint, Tailwind CSS)
- Navigateur de test principal : Chrome

## Règles du dépôt

- **Format des commits** : respect strict de Conventional Commits 1.0.0 (`type: description`).
- **Types autorisés** : `feat`, `fix`, `docs`, `build`, `ci`, `chore`.
- **Règles de rédaction** : en français, verbe à l'infinitif, pas de majuscule inutile, pas de point final.
- **Pourquoi cette règle** :
    - standard utilisé en entreprise.
    - filtrer l'historique proprement par type d'intervention sans perdre de temps.
    - relie directement chaque commit au numéro de version du projet (`feat` pour une version mineure, `fix` pour un patch de correction).

    ## GitHub Flow

1. **Branchement** : Tout travail commence à partir d'une branche issue de `main` à jour.
2. **Qualité (QA)** : Validation des scripts de formatage, de lint et de build avant l'envoi.
3. **Pull Request** : Ouverture d'une PR vers `main` avec le modèle de PR et le lien vers l'issue (`Closes #2`).
4. **Relecture et Fusion** : Validation et fusion de la PR sur la branche principale.
