---
![Université de Tunis El Manar](utm.png)
![Institut Supérieur d'Informatique](isi.png)
# Application de Gestion de Formation

### Mini Projet - Base de Données

**Réalisé par :**  
Montassar Tayachi  
Nermine Bouzidi

**Année universitaire 2024/2025**

---

# Rapport de Projet : Application de Gestion de Formation

## 1. Introduction
La formation professionnelle continue est essentielle pour l’évolution des compétences des employés et la performance des entreprises. Ce projet vise à concevoir et développer une application web permettant la gestion complète des formations au sein du centre « Excellent Training » de la société « Green Building ».

## 2. Objectifs du Projet
- Informatiser la gestion des formations, des participants, des formateurs et des statistiques.
- Faciliter la planification, le suivi et l’évaluation des sessions de formation.
- Offrir des droits adaptés à chaque type d’utilisateur (administrateur, responsable, simple utilisateur, formateur).

## 3. Analyse des Besoins
### Acteurs principaux
- **Administrateur** : Accès illimité, gestion des utilisateurs, domaines, structures, profils, et toutes les tâches des autres acteurs.
- **Responsable Centre** : Consultation et analyse des statistiques.
- **Simple Utilisateur** : Gestion des formateurs, formations et participants.
- **Formateur** : Animation des formations et gestion de la présence des participants.

### Principales fonctionnalités
- Authentification et gestion des droits (JWT, Spring Security).
- Gestion des utilisateurs et des rôles.
- Gestion des structures, profils, domaines.
- Gestion des formations (création, modification, ajout de participants).
- Gestion des participants et des formateurs.
- Gestion de la présence des participants par le formateur.
- Consultation, génération et filtrage des statistiques.

## 4. Architecture technique
L’application repose sur une architecture moderne et modulaire :

- **Backend** : Spring Boot (Spring Web, Spring Data JPA, Lombok, etc.), sécurité assurée par Spring Security et authentification JWT.
- **Base de données** : PostgreSQL
- **Frontend** : React.js
- **UI/UX** : Tailwind CSS et Material UI pour des interfaces modernes et responsives
- **Tests d’API** : Postman
- **Génération de données de test** : Faker.js

Ce choix de technologies permet de garantir la robustesse, la sécurité, la maintenabilité et la scalabilité de la plateforme.

## 5. Modélisation UML
### 5.1 Diagramme de cas d'utilisation
![Diagramme Use Case UML](Diagramme%20Use%20Case%20UML.svg)

### 5.2 Diagramme de classes
![Diagramme de Classes](Diagramme%20de%20Classes.svg)

### 5.3 Diagrammes de séquence
#### Simple utilisateur
![Gestion par le simple utilisateur](Gestion%20par%20le%20simple%20utilisateur.svg)

#### Responsable centre
![Consultation et analyse par le responsable](Consultation%20et%20analyse%20par%20le%20responsable.svg)

#### Administrateur
![Gestion globale par l'administrateur](Gestion%20globale%20par%20l'administrateur.svg)

#### Formateur
![Actions du formateur](Actions%20du%20formateur.svg)
![Séquence du formateur](sequence_formateur.svg)

## 6. Conclusion
Ce projet offre une solution complète, moderne et évolutive pour la gestion de la formation professionnelle. Il permet d’automatiser les tâches, d’améliorer la traçabilité et la prise de décision, tout en garantissant la sécurité et la simplicité d’utilisation.

---

*Annexes : diagrammes UML, extraits du cahier des charges, captures d’écran (à insérer selon avancement).*
