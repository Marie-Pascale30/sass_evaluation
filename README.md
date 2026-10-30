# Evaluation – Créer un système de thèmes avec variables et mixins

## Objectif de l'évaluation

Dans cette évaluation, vous allez optimiser et modulariser les styles d'un site web en utilisant les variables et mixins SCSS, tout en configurant un système de thèmes dynamique (clair/sombre). L'objectif est d'appliquer map.get() pour gérer les couleurs et d'organiser les styles de manière plus flexible et scalable.

---

## Instructions

1. Analysez les fichiers SCSS fournis et identifiez les styles répétitifs et non optimisés.
2. Ajoutez les couleurs dans \_theme.scss pour les thèmes clair et sombre.
3. Utilisez map.get() pour appliquer les couleurs dynamiques aux styles existants.
4. Complétez les mixins dans \_mixins.scss pour éviter la duplication de styles.
5. Vérifiez que .dark-mode fonctionne correctement, permettant de basculer entre les thèmes clair et sombre.
6. Compilez

---

## Fichiers fournis

```plaintext
/sass_evaluation
├── css/
│   ├── style.css      # Fichier CSS compilé
├── scss/
│   ├── style.scss     # Fichier SCSS principal
│   ├── _variables.scss  # Variables globales (à compléter)
│   ├── _mixins.scss     # Mixins partiellement définis (à compléter)
│   ├── _theme.scss      # Système de thèmes partiellement implémenté
│   ├── _header.scss     # Styles du header
├── js/
│   ├── script.js       # Script JS permettant de basculer entre thèmes
├── index.html         # Page HTML pour tester les styles
├── README.md          # Explication du projet
```

_Une page Notion vous a été transmise pour accéder à cette évaluation. Veuillez vous y rendre afin d'obtenir toutes les informations concernant celui-ci._
