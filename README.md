# CustomLog
# Logseq Custom Mods

Ce dépôt contient des fichiers personnalisés pour customiser Logseq.  
Tu peux les utiliser pour améliorer l'interface avec un thème clair, des animations, des effets interactifs et une sidebar ultra personnalisée.

## Fichiers inclus

- **custom.css** : Feuille de style CSS pour modifier l'interface de Logseq.
- **custom.js** : Script JavaScript pour ajouter des interactions avancées (menu flottant, modals draggables, etc.).
- **example-config.edn** : Exemple de configuration à intégrer dans ton fichier `config.edn` de Logseq.

## Instructions

1. **Téléverse le dépôt sur GitHub** ou clone-le en local.

2. **Référence les fichiers dans ton `config.edn`** en ajoutant les lignes suivantes :

   ```edn
   :custom-css-url "file:./chemin/vers/ton/dépôt/custom.css"
   :custom-js-url "file:./chemin/vers/ton/dépôt/custom.js"
