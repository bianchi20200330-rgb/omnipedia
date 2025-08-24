---
title: SF_ EIA2_ Concevoir le modèle des interventions pédagogiques
aliases:
  - Modèle d'intervention MIENA
  - Agents conseillers MIENA
tags:
  - savoir_faire
  - MIENA
  - spécialisation
  - EIA
up: "[[CS_Spécialisation_MIENA_Spécialiser la MIENA pour concevoir un Environnement d’Apprentissage Intelligent (EIA)]]"
related:
  - "[[SF_ EIA1_ Concevoir le modèle de l'apprenant]]"
source: "[[DOC_ Paquette et al 2022_Chap14_Architecture d'une nouvelle méthode d'ingénierie des ENA_ MIENA]]"
---

# SAVOIR-FAIRE : Concevoir le modèle des interventions pédagogiques

## 📌 Description
Ce savoir-faire consiste à **définir comment l'EIA va agir et réagir** en fonction des informations contenues dans le modèle de l'apprenant. Il s'agit de créer des stratégies d'assistance intelligentes, par exemple en concevant des **agents conseillers** qui fonctionnent sur la base de règles pédagogiques pour fournir des recommandations ou adapter le parcours.

C'est la deuxième grande activité ajoutée par la spécialisation EIA, qui dote l'ENA de son "intelligence" adaptative. Elle est formalisée dans un nouvel **ED P-9-EIA : Modèle des interventions pédagogiques**.

---
## 📚 Connaissances mobilisées

- **MOD_ Modèle des interventions pédagogiques** : La connaissance centrale à construire, qui formalise la logique d'adaptation de l'EIA.
- **SF_ Conception d'agents conseillers** : La procédure consistant à rédiger des règles claires et efficaces pour guider l'apprenant.
- **PRINC_ Règle pédagogique (Condition-Action)** : Le principe fondamental "SI [condition sur le modèle de l'apprenant] ALORS [action de recommandation]" qui structure la logique des agents.
- **DOC_ Fiche des interventions pédagogiques** : La capacité à structurer et à rédiger le nouvel ED P-9-EIA.
- **CONTEXTE_ Scénarios pédagogiques** : Savoir identifier les moments et les lieux pertinents (points d'insertion) dans les scénarios (ED P-5* (320*)) pour déclencher les interventions.

---
## 🔄 Éléments de Documentation (ED) associés

### ➤ ED Entrants (Inputs)
* **ED P-8-EIA** : Modèle de l'apprenant (la base de données pour les décisions)
* **ED C-2* (212*)** : Modèle cognitif principal (la référence pour les recommandations)
* **ED P-5* (320*)** : Scénarios pédagogiques des UA (le lieu d'intervention)

### ➤ ED Sortant (Output)
* **ED P-9-EIA** : Document définissant le modèle des interventions pédagogiques (ex: les règles des agents conseillers).

---
## 📋 Format
- **Texte structuré et/ou tableau de règles** décrivant la logique de chaque agent conseiller (condition, action).
- **Annotations sur les modèles graphiques** des scénarios pédagogiques (ED P-5* (320*)) pour indiquer les points d'insertion des agents.

---

## 🔎 QQOQCCP+ détaillé

### Qui ?
- Le **concepteur pédagogique**, qui définit la logique des interventions pour maximiser leur pertinence.
- Le **spécialiste technique**, qui s'assure que les règles sont implémentables par le système.
- Le **spécialiste de contenu**, qui valide la justesse des recommandations proposées.

### Quoi ?
- La **logique d'adaptation** de l'EIA.
- Un ensemble de **règles conditionnelles** qui comparent le modèle de l'apprenant au modèle du domaine pour déclencher des actions (conseils, recommandations, adaptations).

### Où ?
- Au sein de l'**axe pédagogique**, en tant qu'extension de la scénarisation.
- Dans un document de conception qui servira de cahier des charges pour la programmation de "l'intelligence" du système.

### Quand ?
- **Après** la conception du modèle de l'apprenant (**ED P-8-EIA**), car il en dépend directement.
- Durant les **cycles de conception et de prototypage**.

### Comment ?
- En **comparant** les informations du modèle de l'apprenant (ce qu'il sait) avec celles du modèle du domaine (ce qu'il devrait savoir).
- En **rédigeant des règles** de type "SI-ALORS" pour chaque intervention souhaitée.
- En **identifiant les "points critiques"** dans les scénarios d'apprentissage où ces règles doivent être évaluées (ex: à la fin d'une activité, après la consultation d'une ressource).

### Combien ?
- Un **ensemble de règles** regroupées par agents conseillers. Le nombre de règles peut varier de quelques-unes à plusieurs dizaines selon la complexité de l'EIA.

### Pourquoi ?
- Pour **fournir une assistance personnalisée et contextualisée** à l'apprenant.
- Pour **rendre l'ENA proactif** plutôt que simplement réactif aux clics de l'utilisateur.
- Pour **opérationnaliser la personnalisation** de l'apprentissage de manière systématique.

### ✅ Preuves / Indicateurs de réussite
- L'**ED P-9-EIA** est rédigé, et les règles sont claires, logiques et techniquement réalisables.
- Le prototype de l'EIA exécute les interventions comme prévu (ex: il affiche la bonne recommandation au bon moment pour un profil d'apprenant donné).
- Les interventions sont perçues comme utiles et pertinentes par les testeurs.