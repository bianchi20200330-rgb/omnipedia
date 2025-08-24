---
title: SF_P3_Structurer le réseau des unités d’apprentissage (UA)
aliases:
  - Réseau des UA
  - Réseau des événements d'apprentissage
  - Structuration pédagogique MIENA
tags:
  - savoir_faire
  - MIENA
  - axe_pédagogique
  - structuration
up: "[[CS_ P_ Concevoir des scénarios pédagogiques adaptés aux profils des apprenants et aux objectifs d’apprentissage]]"
related:
  - "[[SF_P2_Définir les orientations pédagogiques]]"
  - "[[SF_P5_Concevoir les scénarios pédagogiques des UA]]"
source: "[[DOC_ Paquette et al 2022_Chap14_Architecture d'une nouvelle méthode d'ingénierie des ENA_ MIENA]]"
---

# SAVOIR-FAIRE : Structurer le réseau des unités d’apprentissage (UA)

## 📌 Description
Ce savoir-faire consiste à **concevoir l'architecture pédagogique globale de l'ENA**. Il s'agit de décomposer la formation en événements d'apprentissage (programmes, cours, modules) jusqu'aux plus petites unités terminales (les Unités d'Apprentissage ou UA). Le résultat est une carte visuelle qui montre le parcours de l'apprenant, les ressources nécessaires et les règles de progression.

Cette structure, appelée **Réseau des Événements d'Apprentissage (RÉA)**, est le cœur du devis pédagogique et est formalisée dans l'**ED 222* : Réseau des événements d'apprentissage**.

---
## 🔄 Éléments de Documentation (ED) associés

### ➤ ED Entrants (Inputs)
* **ED 102** : Objectifs de la formation
* **ED 104** : Publics cibles
* **ED 212*** : Modèle des connaissances
* **ED 214*** : Tableau des compétences
* **ED 220** : Orientations pédagogiques

### ➤ ED Sortant (Output)
* **ED 222*** : Réseau des événements d'apprentissage

---
## 📋 Format
- **Modèle graphique (graphe MOT/GMOT)** représentant la structure du programme, du cours ou du module de formation. Les nœuds du graphe sont les événements d'apprentissage, les ressources et les règles qui régissent les cheminements.

---

## 🔎 QQOQCCP+ détaillé

### Qui ?
- Le **concepteur pédagogique**, qui est le principal architecte de ce réseau.
- Le **spécialiste de contenu**, qui valide la logique et la pertinence de la décomposition du contenu.
- Le **gestionnaire de projet**, qui s'assure que la structure est réalisable dans les délais et budgets impartis.

### Quoi ?
- Un **modèle graphique (le RÉA)** qui représente la structure de la formation.
- Il contient les **événements d'apprentissage (ÉA/UA)**, les **ressources** (intrants/produits), et les **règles** (démarche, collaboration, évaluation) qui régissent le parcours.

### Où ?
- Au sein des activités de l'**axe pédagogique** de la méthode MIENA/MISA.
- À l'aide d'un outil de modélisation graphique (comme MOT/GMOT).

### Quand ?
- Principalement durant les **premiers et deuxièmes cycles** de conception.
- En **interaction forte et itérative** avec la modélisation des connaissances (**ED 212***) et des compétences (**ED 214***).

### Comment ?
- En se basant sur les **orientations pédagogiques (ED 220)** pour choisir le type de réseau (linéaire, hiérarchique, en réseau...).
- En décomposant les objectifs de formation en **Événements d'Apprentissage (ÉA)** de plus en plus fins.
- En identifiant les **Unités d'Apprentissage (UA)** comme les ÉA terminaux qui ne seront plus décomposés.
- En reliant les ÉA/UA et les ressources par des **liens typés** (Composition, Précédence, Intrant/Produit, Régulation).

### Combien ?
- La complexité du réseau varie : d'un **RÉA mononiveau** simple pour une formation courte, à un **RÉA multiniveaux** complexe pour un programme complet.

### Pourquoi ?
- Pour **donner une vision d'ensemble cohérente** du parcours d'apprentissage.
- Pour **s'assurer que toutes les connaissances et compétences visées sont couvertes** par au moins une UA.
- Pour **planifier la production** en découpant le projet en unités de travail claires (les UA).

### ✅ Preuves / Indicateurs de réussite
- L'**ED 222*** est produit, il est lisible et logiquement structuré.
- Le réseau est cohérent avec les orientations pédagogiques (**ED 220**) et couvre l'ensemble du modèle cognitif (**ED 212***).
- Chaque UA identifiée dans le réseau peut ensuite faire l'objet d'une description détaillée (**ED 224***) et d'un scénario pédagogique (**ED 320***).