# Analyse fonctionnelle ABC — Outil éducatif

<p align="center">
  <img src="icon.png" alt="Icône Analyse fonctionnelle ABC" width="220">
</p>

Outil web simple destiné à soutenir l'observation et l'analyse fonctionnelle de situations éducatives selon la logique **A-B-C** :

- **A — Antécédent** : ce qui se passe juste avant le comportement ;
- **B — Comportement** : description concrète et observable ;
- **C — Conséquence** : ce qui se passe immédiatement après.

L'objectif est d'aider les équipes à **observer plusieurs situations, rechercher des régularités et formuler des hypothèses prudentes**, afin de tester des adaptations concrètes de l'environnement et des réponses éducatives.

## Fonctionnalités

- gestion de plusieurs dossiers ;
- saisie structurée des observations ABC ;
- éléments de contexte présents avant la situation ;
- fréquence, durée et intensité du comportement ;
- plusieurs hypothèses fonctionnelles possibles ;
- modification et suppression des observations ;
- filtres par date et intensité ;
- synthèse des régularités observées ;
- sauvegarde locale dans le navigateur ;
- export / import JSON ;
- export CSV ;
- impression / enregistrement PDF ;
- mode d'emploi intégré.

## Confidentialité

Les données saisies sont enregistrées **localement dans le navigateur** avec `localStorage`. Elles ne sont pas envoyées vers GitHub et ne sont pas stockées dans le dépôt.

Pour un usage sur un ordinateur partagé ou pour une démonstration publique, il est recommandé d'utiliser des initiales ou un identifiant interne et d'éviter les informations nominatives inutiles.

**Ne pas déposer sur GitHub des exports JSON ou CSV contenant des données concernant des enfants.**

## Limites

Cet outil soutient l'analyse professionnelle. Il ne permet pas, à lui seul, d'établir avec certitude la fonction d'un comportement et ne remplace pas une évaluation clinique, médicale ou spécialisée lorsqu'elle est nécessaire.

Une même conduite peut avoir différentes fonctions selon le contexte et plusieurs facteurs peuvent intervenir simultanément.

## Icône et favicon

- `favicon.ico` : icône affichée dans l’onglet du navigateur ;
- `icon.png` : version haute résolution utilisée dans le README et comme icône pour certains appareils.

Les deux fichiers sont déjà reliés à `index.html`. Aucune modification supplémentaire n’est nécessaire pour GitHub Pages.

## Mise en ligne avec GitHub Pages

1. Créer un nouveau dépôt GitHub, par exemple `analyse-fonctionnelle-abc`.
2. Ajouter à la racine du dépôt les fichiers `index.html`, `README.md`, `favicon.ico`, `icon.png` et `.nojekyll`.
3. Dans le dépôt, ouvrir **Settings → Pages**.
4. Dans **Build and deployment**, sélectionner **Deploy from a branch**.
5. Choisir la branche **main** et le dossier **/(root)**, puis enregistrer.
6. Après quelques minutes, l'outil sera disponible à une adresse du type :
   `https://VOTRE-NOM.github.io/analyse-fonctionnelle-abc/`

## Auteur

**Menad Malek — Éducateur spécialisé**
