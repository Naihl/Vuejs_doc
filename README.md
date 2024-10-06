# Comment démarrer un projet Vue.js

## Introduction

Bienvenue dans ce guide pour démarrer un projet Vue.js. Ce document vous guidera à travers les étapes nécessaires pour créer, configurer et déployer un projet Vue.js.

### Prérequis

- Node.js et npm installés sur votre machine.
- Utilisation de Visual Studio Code


### Étape 1: Créer une application Vue

```sh
npm create vue@latest
```	

Cette commande permettra de lancer l'éxecution de create vue pour créer une nouvelle application Vue.js. Vous serez invité à répondre à quelques questions pour configurer votre projet. 

```sh	
✔ Project name: … <votre-nouveau-projet>
✔ Add TypeScript? … No / Yes
✔ Add JSX Support? … No / Yes
✔ Add Vue Router for Single Page Application development? … No / Yes
✔ Add Pinia for state management? … No / Yes
✔ Add Vitest for Unit testing? … No / Yes
✔ Add an End-to-End Testing Solution? … No / Cypress / Nightwatch / Playwright
✔ Add ESLint for code quality? … No / Yes
✔ Add Prettier for code formatting? … No / Yes
✔ Add Vue DevTools 7 extension for debugging? (experimental) … No / Yes
```

### Étape 2: Naviguer dans le répertoire du projet  

```sh
cd <votre-nouveau-projet>
```

### Étape 3: Lancer le serveur de développement

```sh
npm run server
```

### Étape 4: Ouvrir le navigateur

Ouvrez votre navigateur et accédez à l'adresse suivante: [http://localhost:8080](http://localhost:8080)

Vous devriez voir votre application Vue.js en cours d'exécution.
Maintenant il est temps de commencer à développer votre application.

### Étape 5: Construire le projet pour la production

Une fois votre projet terminé, vous pouvez le construire pour la production en exécutant la commande suivante:

```sh
npm run build
```

Cette commande générera un dossier `dist` contenant les fichiers de votre application prêts pour la production.