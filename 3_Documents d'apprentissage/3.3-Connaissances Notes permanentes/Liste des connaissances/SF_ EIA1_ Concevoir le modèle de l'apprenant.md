---
title: SF_ EIA1_ Concevoir le modèle de l'apprenant
aliases:
  - Modèle de l'apprenant MIENA
  - Conception modèle apprenant
tags:
  - savoir_faire
  - MIENA
  - spécialisation
  - EIA
up: "[[CS_Spécialisation_MIENA_Spécialiser la MIENA pour concevoir un Environnement d’Apprentissage Intelligent (EIA)]]"
related:
  - "[[SF_ EIA2_ Concevoir le modèle des interventions pédagogiques]]"
source: "[[DOC_ Paquette et al 2022_Chap14_Architecture d'une nouvelle méthode d'ingénierie des ENA_ MIENA]]"
---

# SAVOIR-FAIRE : Concevoir le modèle de l'apprenant

## 📌 Description
Ce savoir-faire consiste à **définir ce que le système doit savoir sur l'apprenant** (ses connaissances déjà maîtrisées, sa progression dans les activités, ses préférences, etc.) et à structurer ces informations dans un modèle dynamique. Il inclut également la conception des activités d'évaluation (pré-tests, quiz, suivi des actions) qui permettront d'alimenter ce modèle.

C'est la première des deux grandes activités ajoutées par la spécialisation EIA. Elle est formalisée dans un nouvel **ED P-8-EIA : Modèle de l'apprenant**.

---
## 📚 Connaissances mobilisées

- **MOD_ Modèle de l'apprenant** : C'est la connaissance centrale à construire, définissant la structure des informations sur l'état cognitif, métacognitif ou affectif de l'apprenant.
- **SF_ Diagnostic cognitif** : La procédure consistant à concevoir des évaluations (tests, analyse des traces) qui permettent d'inférer l'état des connaissances de l'apprenant.
- **DOC_ Fiche du modèle de l'apprenant** : La capacité à structurer et à rédiger le nouvel ED P-8-EIA de manière claire et opérationnelle.
- **CONTEXTE_ Modèle des connaissances du domaine** : Comprendre que le modèle de l'apprenant est souvent une "superposition" ou un sous-ensemble du modèle cognitif principal (ED C-2* (212*)).

---
## 🔄 Éléments de Documentation (ED) associés

### ➤ ED Entrants (Inputs)
* **ED C-2* (212*)** : Modèle cognitif principal (sert de référence pour les connaissances à suivre)
* **ED P-5* (320*)** : Scénarios pédagogiques des UA (où les données sur l'apprenant sont collectées)

### ➤ ED Sortant (Output)
* **ED P-8-EIA** : Document définissant le contenu du modèle de l'apprenant et les activités d'évaluation qui l'alimentent.

---
## 📋 Format
- **Texte structuré et/ou modèle** décrivant les composantes du modèle de l'apprenant (ex: liste des compétences maîtrisées, historique des activités) et les spécifications des activités d'évaluation (ex: pré-test, quiz).

---

## 🔎 QQOQCCP+ détaillé

### Qui ?
- Le **concepteur pédagogique**, qui définit les informations pertinentes à suivre d'un point de vue pédagogique.
- Le **spécialiste technique**, qui s'assure que le modèle peut être implémenté et que les données peuvent être collectées.

### Quoi ?
- Une **représentation dynamique de l'état de l'apprenant**, mise à jour en continu par le système.
- La conception des **mécanismes de collecte de données** (évaluations, suivi des traces).

### Où ?
- Au sein de l'**axe pédagogique**, comme une extension des activités de conception.
- Dans un document de conception qui sera utilisé par l'axe médiatique pour l'implémentation technique.

### Quand ?
- **Après** la définition du modèle cognitif du domaine (**ED C-2* (212*)**), car celui-ci sert de base.
- Durant les **cycles de conception et de prototypage**.

### Comment ?
- En **définissant les variables** à suivre (ex: score à un quiz, temps passé sur une ressource, compétences maîtrisées).
- En **concevant des activités d'évaluation** (ex: un pré-test au début de l'ENA) qui initialisent et mettent à jour le modèle.
- En spécifiant comment les **interactions de l'apprenant** (clics, réponses) sont utilisées pour inférer son état.

### Combien ?
- **Un modèle de l'apprenant** pour l'ensemble de l'ENA, même s'il peut être composé de plusieurs parties.

### Pourquoi ?
- Pour **permettre la personnalisation**. Sans informations sur l'apprenant, le système ne peut pas s'adapter.
- Pour **fournir la base de données** sur laquelle le modèle des interventions pédagogiques (SF_ EIA2) pourra prendre des décisions.

### ✅ Preuves / Indicateurs de réussite
- L'**ED P-8-EIA** est rédigé, complet et techniquement réalisable.
- Le prototype de l'EIA est capable de suivre et d'afficher les progrès d'un apprenant.
- Les données collectées sont fiables et peuvent être utilisées par le modèle d'intervention.