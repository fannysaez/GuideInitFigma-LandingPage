<div align="center">
  <img src="./assets/icons/LogoFigma-LandingPage-Base.svg" alt="Figma Logo" width="70"/>


  # Guide Complet d'Initiation à Figma - Création d'une Landing Page


*Un guide détaillé pour maîtriser Figma de zéro*

[![Figma](https://img.shields.io/badge/Figma-3.0+-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/)
[![Design Tool](https://img.shields.io/badge/Design_Tool-UI/UX-09CF83?style=for-the-badge)](https://www.figma.com/)
[![Prototyping](https://img.shields.io/badge/Prototyping-Interactive-4B61FF?style=for-the-badge)](https://www.figma.com/)



![Logo Figma Landing Page](./assets/img/LandingPage-Validé.png)
  </div>

---

## Table des matières

- [Introduction](#introduction)
- [Prérequis](#prérequis)
- [Installation et configuration](#installation-et-configuration)
- [Interface de Figma](#interface-de-figma)
- [Création d'une Landing Page](#création-dune-landing-page)
  - [Structure de base](#structure-de-base)
  - [Design du header](#design-du-header)
  - [Section héros](#section-héros)
  - [Sections informatives](#sections-informatives)
  - [Formulaire de connexion](#formulaire-de-connexion)
  - [Footer](#footer)
- [Composants et styles](#composants-et-styles)
- [Prototypage](#prototypage)
- [Exportation](#exportation)
- [Collaboration](#collaboration)
- [Ressources additionnelles](#ressources-additionnelles)

---

```bash
📁 Figma
│── 📄 README.md           
├── 🖼️ Logo & Illustration
│   ├── Logo SVG centré
│   ├── Badges Figma / Design / Prototyping
│   └── Illustration d’aperçu (landing page validée)
├── 📝 Introduction
│   └── Présentation du guide et de ses objectifs (avec lien vers le tutoriel vidéo)
├── 📑 Table des matières
│   └── Liens internes vers les sections principales du guide
├── 🧰 Prérequis
│   └── Liste du matériel et des comptes nécessaires (ordinateur, navigateur, compte Figma)
├── ⚙️ Installation et configuration
│   ├── Création d’un compte Figma
│   ├── Utilisation via navigateur ou application
│   └── Création du premier fichier projet
├── 🖥️ Interface de Figma
│   └── Description de l’interface utilisateur : outils, calques, propriétés
├── 🎨 Création d’une Landing Page
│   ├── 📐 Structure de base
│   │   ├── Création d’un frame
│   │   └── Mise en place de la grille de mise en page
│   ├── 🧭 Design du header
│   │   ├── Barre de navigation
│   │   ├── Ajout du logo
│   │   ├── Menu de navigation
│   │   └── Bouton de connexion
│   ├── 🦸 Section héros
│   │   ├── Arrière-plan
│   │   ├── Titre principal
│   │   ├── Sous-titre
│   │   └── Image principale
│   ├── 🧾 Sections informatives
│   │   ├── Cartes de niveau (Bases, Avancé, Expert, Master)
│   │   └── Contenu de chaque carte (titre, texte, icônes)
│   ├── 🔐 Formulaire de connexion
│   │   ├── Panneau / bloc formulaire
│   │   ├── Titre du formulaire
│   │   ├── Champs Email & Mot de passe
│   │   ├── Bouton de connexion
│   │   └── Lien de récupération
│   └── 📎 Footer
│       ├── Zone de fond sombre
│       ├── Logo à gauche
│       ├── Liens au centre
│       └── Réseaux sociaux à droite
├── 🧩 Composants et styles
│   └── Création et gestion de styles (couleurs, textes, effets)
├── 🧪 Prototypage
│   └── Connexion des frames, interactions, animations
├── 📤 Exportation
│   └── Formats disponibles et options d’exportation (PNG, SVG, PDF, code)
├── 🤝 Collaboration
│   └── Partage, commentaires, travail en équipe sur Figma
├── 📚 Ressources additionnelles
│   └── Liens vers ressources utiles, templates, bibliothèques
```

---

</div>
<p align="center">
  <a href="Guide-Figma/Introduction.md">Suivant</a>
</p>


<!-- 

## Composants et styles

1. **Création de styles de couleurs**
   - Allez dans le panneau "Design" en haut à droite
   - Cliquez sur l'icône "+" à côté de "Color styles"
   - Créez des styles pour vos couleurs principales :
     - Fond sombre : #111827
     - Accent orange : #F59E0B
     - Texte blanc : #FFFFFF
     - Texte gris : #D1D5DB

2. **Création de styles de texte**
   - Allez dans le panneau "Design" en haut à droite
   - Cliquez sur l'icône "+" à côté de "Text styles"
   - Créez des styles pour vos textes :
     - Titre principal : Montserrat Bold, 48px
     - Sous-titre : Inter Regular, 18px
     - Titre de section : Inter Bold, 24px
     - Paragraphe : Inter Regular, 16px

3. **Création de composants**
   - Sélectionnez le bouton de connexion
   - Cliquez sur "Create Component" dans la barre d'outils supérieure
   - Renommez le composant "Button/Primary"
   - Créez une variante pour un état de survol

## Prototypage

1. **Création des interactions**
   - Allez dans l'onglet "Prototype" en haut à droite
   - Sélectionnez le bouton "Connexion" dans le header
   - Cliquez et faites glisser vers le panneau de connexion
   - Configurez l'interaction : "On Click" -> "Smart Animate"

2. **Prévisualisation du prototype**
   - Cliquez sur le bouton "Play" en haut à droite
   - Testez les interactions que vous avez créées

## Exportation

1. **Exportation des assets**
   - Sélectionnez les éléments à exporter
   - Dans le panneau de droite, ajoutez des paramètres d'exportation
   - Choisissez le format (PNG, SVG, JPG)
   - Cliquez sur "Export"

2. **Partage du design**
   - Cliquez sur le bouton "Share" en haut à droite
   - Définissez les permissions (Viewer, Editor, etc.)
   - Copiez le lien de partage

## Collaboration

1. **Commentaires et feedback**
   - En mode partage, cliquez sur l'icône de commentaire
   - Cliquez sur l'élément que vous souhaitez commenter
   - Tapez votre commentaire et appuyez sur Entrée

2. **Travail en équipe**
   - Invitez des collaborateurs via le bouton "Share"
   - Utilisez l'historique des versions pour suivre les modifications

## Ressources additionnelles

- [Documentation officielle de Figma](https://help.figma.com/)
- [Communauté Figma](https://www.figma.com/community)
- [Plugins recommandés pour Figma](https://www.figma.com/community/plugins)
- [Tutoriels vidéo sur la chaîne YouTube de Figma](https://www.youtube.com/c/Figmadesign) -->

