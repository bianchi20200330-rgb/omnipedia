---
aliases:
  - Analyser les tests utilisateurs
  - Registre des changements MIENA
tags:
  - savoir_faire
  - MIENA
  - prototypage
  - test
type: Savoir-faire
status: 🌱 Seed
domain: "[[Ingénierie Pédagogique]]"
created: 2025-08-10
updated: 2025-08-10
parent: "[[3_Documents d'apprentissage/3.3-Connaissances Notes permanentes/Liste des connaissances/CS_ Prototyper et tester les composantes d'un ENA]]"
child: []
related: []
sibling:
  - "[[SF_ PROTO3_ Mener les tests auprès des utilisateurs]]"
source: "[[DOC_ Paquette et al 2022_Chap14_Architecture d'une nouvelle méthode d'ingénierie des ENA_ MIENA]]"
summary: Analyser les données collectées lors des tests pour identifier les problèmes et formuler des demandes de révision claires qui serviront d'intrants pour le cycle de développement suivant.
---

# SAVOIR-FAIRE : Analyser les résultats et consigner les changements

## 📌 Description
Ce savoir-faire consiste à **analyser les données collectées lors des tests pour identifier les problèmes, les points forts et les pistes d'amélioration**. Il s'agit de synthétiser les retours et de formuler des demandes de révision claires qui serviront d'intrants pour le cycle de développement suivant.

Cette étape est le moteur du processus itératif de la MIENA, car elle transforme les données brutes des tests en décisions concrètes pour l'amélioration de l'ENA. Elle est formalisée dans l'**ED G-6* (542*) : Registre des changements postvalidation**.

---
## 📚 Connaissances mobilisées et liens
Le savoir-faire **[[SF_ PROTO4_ Analyser les résultats et consigner les changements]]** est une connaissance procédurale (SF). Elle est en relation avec d'autres connaissances de la manière suivante :

- **Régulation (R)** : Il **est régulé par** les principes qui le guident :
    - Régulation:: [[PRINC_ Principes de l'analyse de données qualitatives]]
- **Composition (C)** : Il **se compose de** savoir-faire plus spécifiques :
    - Composition:: [[SF_ Analyse de données de test]]
    - Composition:: [[SF_ Rédaction de demandes de changement]]
- **Intrant-Produit (I/P)** : Il **prend en intrant** les données brutes et **a pour produit** un document structuré :
    - Intrant:: [[DOC_ Données de test brutes]]
    - Produit:: [[DOC_ Registre des changements]]
- **Application (A)** : Il **s'applique dans** un contexte précis :
    - Application:: [[CONTEXTE_ Fin de cycle de prototypage]]

---
## 🔄 Éléments de Documentation (ED) associés

### ➤ ED Entrants (Inputs)
* Les **données de validation brutes** issues du savoir-faire [[SF_ PROTO3_ Mener les tests auprès des utilisateurs]].

### ➤ ED Sortant (Output)
* **ED G-6* (542*)** : Registre des changements postvalidation

---
## 📋 Format
- **Tableau des demandes de changement**. Chaque entrée du tableau décrit une demande de révision en précisant le demandeur, le type, la description, l'évaluation de la demande, la décision et le suivi.

---

## 🔎 QQOQCCP+ détaillé

### Qui ?
- L'**équipe de conception** (gestionnaire, pédagogue, spécialiste médiatique), qui analyse collectivement les résultats.
- Le **gestionnaire de projet**, qui est responsable de la tenue du registre des changements et de la priorisation des révisions.

### Quoi ?
- La **transformation des retours utilisateurs en actions concrètes** pour le prochain cycle.
- La **documentation formelle** des décisions de révision.

### Où ?
- Au sein des **activités de gestion** de la méthode MIENA.
- Dans un document partagé (le registre des changements) qui sert de mémoire au projet.

### Quand ?
- À la **fin de chaque cycle de test**, après la collecte des données.
- **Avant** de commencer la planification du cycle de développement suivant.

### Comment ?
- En **analysant les données** qualitatives (commentaires) et quantitatives (taux d'erreur) pour identifier les problèmes récurrents.
- En **synthétisant chaque problème** dans une "demande de changement" claire.
- En **évaluant l'impact et l'effort** de chaque demande de changement.
- En **prenant une décision** (accepter, refuser, reporter) pour chaque demande.
- En **consignant le tout** dans le registre des changements.

### Combien ?
- **Un registre des changements unique** pour l'ensemble du projet, qui est enrichi à la fin de chaque cycle de test.

### Pourquoi ?
- Pour **s'assurer que les retours utilisateurs ne sont pas perdus** et sont traités de manière systématique.
- Pour **piloter le processus itératif sur la base de preuves** et non d'intuitions.
- Pour **garder une traçabilité** des problèmes identifiés et des décisions prises tout au long du projet.

### ✅ Preuves / Indicateurs de réussite
- L'**ED G-6* (542*)** est rempli de manière rigoureuse et est à jour.
- Les décisions consignées dans le registre sont claires et justifiées.
- Le plan de travail du cycle suivant (**ED G-3***) est directement influencé par les décisions prises dans le registre des changements.