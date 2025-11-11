# README - Projet React Navigation

##  Description du Projet
**React Navigation** est une application web moderne développée avec React qui démontre les concepts fondamentaux du développement front-end moderne. Cette application inclut la navigation, le rendu conditionnel, les listes dynamiques et l'intégration de médias.

##  Liens du Projet

###  Drive du Projet Complet
**[ Télécharger tous les fichiers du projet](https://drive.google.com/file/d/1ugjJmaRqy8g-oILJZYzZs777BPPqzHDE/view?usp=sharing)**

###  Démonstration Vidéo


https://github.com/user-attachments/assets/7d309d34-6201-4880-9419-ca52d3f0276f


https://github.com/user-attachments/assets/914d026c-8576-47e3-b4ac-e153d0d4f6e7


https://github.com/user-attachments/assets/464f3ea5-9244-4218-b3a7-6410db3f5798


https://github.com/user-attachments/assets/15cdfe9f-a2c8-4794-8b1e-8b7a84a28368


https://github.com/user-attachments/assets/83aba9e7-a286-4ca9-a105-ce56ef657230


https://github.com/user-attachments/assets/a18904df-a170-4ef1-980d-bd46dcfc1f1c


https://github.com/user-attachments/assets/8fd4d8cb-77cd-4bfb-9750-1c7873e45d15


https://github.com/user-attachments/assets/bb3fdda9-3525-4459-abd2-a56867c79101



###  Application en Ligne
**[🌐 Voir l'application déployée](http://localhost:3000/)**

##  Fonctionnalités

###  Navigation
- **React Router DOM** pour une navigation SPA (Single Page Application)
- 3 pages principales : Accueil, À propos, Contact
- Navigation fluide sans rechargement de page

###  Interface Utilisateur
- Design **ultra-moderne** avec thème sombre violet/rose/cyan
- **Animations CSS** avancées et effets glassmorphism
- Interface **responsive** adaptée à tous les appareils
- **Micro-interactions** et feedback utilisateur

###  Composants Interactifs
- **Système de connexion** avec rendu conditionnel
- **Lecteur audio** fonctionnel avec playlist
- **Liste de tâches** interactive avec progression
- **Galerie d'images** immersive
- **Notifications** dynamiques
- **Formulaire de contact**

##  Technologies Utilisées

- **React 18** - Bibliothèque front-end
- **React Router DOM** - Gestion de la navigation
- **CSS3** - Styles avancés avec variables CSS
- **HTML5** - Structure sémantique
- **JavaScript ES6+** - Logique applicative

##  Structure du Projet

```
tp-navigation/
├── public/
│   ├── sounds/                 # Fichiers audio
│   │   ├── digital-symphony.mp3
│   │   └── cyber-dreams.mp3
│   └── index.html
├── src/
│   ├── components/
│   │   ├── App.js             # Composant principal
│   │   ├── App.css            # Styles globaux
│   │   ├── index.js           # Point d'entrée
│   │   ├── Accueil.js         # Page d'accueil
│   │   ├── Apropos.js         # Page À propos
│   │   ├── Contact.js         # Page Contact
│   │   ├── Connexion.js       # Composant connexion
│   │   ├── ListeTaches.js     # Gestionnaire de tâches
│   │   ├── LecteurAudio.js    # Lecteur multimédia
│   │   ├── Galerie.js         # Galerie d'images
│   │   ├── Logo.js            # Composant logo
│   │   ├── Notifications.js   # Système de notifications
│   │   └── ListeCourses.js    # Liste dynamique
│   └── assets/                # Ressources statiques
├── package.json
└── README.md
```

##  Installation et Démarrage

### Prérequis
- Node.js (version 14 ou supérieure)
- npm ou yarn

### Installation

1. **Extraire et installer**
```bash
unzip tp-navigation.zip
cd tp-navigation
npm install
```

2. **Démarrer l'application**
```bash
npm start
```

L'application sera accessible à l'adresse : `http://localhost:3000`

### Scripts Disponibles

```bash
npm start      # Démarre le serveur de développement
npm test       # Lance les tests
npm run build  # Crée une version de production
npm run eject  # Éjecte la configuration (irréversible)
```

## Utilisation de l'Application

### Page d'Accueil (`/`)
- **Logo animé** avec effets de particules
- **Lecteur audio** avec contrôles complets
- **Liste de tâches** interactive
- **Galerie d'images** responsive
- **Statistiques** en temps réel

### Page À Propos (`/apropos`)
- Présentation des fonctionnalités
- Section "Développé par Aicha Barahou"
- Cartes de fonctionnalités avec icônes

### Page Contact (`/contact`)
- **Formulaire de contact** fonctionnel
- **Liste de courses** dynamique
- Section informations développeur

### Composants Interactifs

####  Lecteur Audio
- Boutons Lecture/Pause, Précédent/Suivant
- Barre de progression interactive
- Liste de lecture cliquable
- Mode simulation automatique

####  Gestionnaire de Tâches
- Marquer les tâches comme terminées
- Ajouter/supprimer des tâches
- Barre de progression automatique
- Statistiques en temps réel

####  Système de Notifications
- Compteur de notifications
- Ajout/suppression de notifications
- Rendu conditionnel


##  Palette de Couleurs

```css
:root {
  --primary: #8B5FBF;      /* Violet principal */
  --secondary: #FF6B9D;    /* Rose accent */
  --accent: #00D4AA;       /* Cyan highlight */
  --background: #0F0F1E;   /* Fond sombre */
  --surface: #1A1A2E;      /* Surfaces */
  --text: #FFFFFF;         /* Texte principal */
}
```

##  Personnalisation

### Modifier les couleurs
Éditez les variables CSS dans `src/App.css` :

```css
:root {
  --primary: #VotreCouleur;
  --secondary: #VotreCouleur;
  /* ... */
}
```

### Ajouter de nouvelles pages
1. Créer un nouveau composant dans `src/`
2. Ajouter la route dans `App.js`
3. Ajouter le lien dans la navigation

### Ajouter des sons
Placer les fichiers MP3 dans `public/sounds/` et mettre à jour `LecteurAudio.js`

##  Responsive Design

L'application s'adapte automatiquement :
- **Desktop** : Layout complet avec sidebars
- **Tablette** : Adaptation des grilles
- **Mobile** : Navigation empilée, contenu optimisé

##  Dépannage

### Problèmes Courants

**Les sons ne fonctionnent pas :**
- Vérifier que les fichiers MP3 sont dans `public/sounds/`
- Le mode simulation se active automatiquement

**Styles non chargés :**
- Vérifier l'import de `App.css` dans `App.js`

**Navigation ne marche pas :**
- Vérifier l'installation de `react-router-dom`

### Solutions

```bash
# Réinstaller les dépendances
rm -rf node_modules
npm install

# Redémarrer le serveur
npm start
```


## Support

**Développé par :** Aicha Barahou  
**Email :** aicha.barahou@email.com  
**Technologies :** React, React Router, CSS3, JavaScript  
**Date :** 2024

** [Contactez-moi pour toute question](mailto:aicha.barahou@email.com)**



** L'application est maintenant opérationnelle avec toutes les fonctionnalités implémentées !**
