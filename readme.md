# Vérificateur de Nombre (Console)

Ce projet est une petite application en ligne de commande développée en **Node.js**. Elle invite l'utilisateur à saisir un nombre dans le terminal et affiche le résultat en retour.

## Prérequis

Pour exécuter ce projet, vous devez avoir installé :
* [Node.js](https://nodejs.org) (Version 18 ou supérieure recommandée)

## Installation

1. Assurez-vous d'être dans le dossier contenant le fichier de votre script (par exemple `index.js`).
2. Aucune dépendance externe n'est requise car le projet utilise le module natif `node:readline`.

## Utilisation

Pour lancer le script, ouvrez votre terminal dans VS Code (`Ctrl + ` `) et exécutez la commande suivante :

```bash
node index.js
```

### Exemple de fonctionnement :
```text
Entrez un nombre: 42
est un entier 42
```

## Fonctionnalités du code
* **Interactivité** : Utilise le module natif `readline` pour lire la saisie de l'utilisateur directement dans le terminal.
* **Conversion** : Convertit la chaîne de caractères reçue en type `Number`.
