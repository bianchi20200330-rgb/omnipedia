---
aliases:
  - Architecture EIA
  - Modèle conceptuel d'un EIA
tags:
  - modèle
  - MIENA
  - EIA
  - personnalisation
type: Modèle
status: 🌱 Seed
domain: "[[Ingénierie Pédagogique]]"
created: 2025-08-10
updated: 2025-08-10
parent: "[[Répertoire des connaissances de la méthode MIENA]]"
child:
  - "[[CONC_ Modèle de l'apprenant]]"
  - "[[CONC_ Modèle des interventions pédagogiques]]"
related:
  - []
sibling:
  - "[[MOD_ MIENA]]"
  - "[[MOD_ Modèles éducatifs CLOM]]"
source: "[[DOC_ Paquette et al 2022_Chap14_Architecture d'une nouvelle méthode d'ingénierie des ENA_ MIENA]]"
summary: Le modèle conceptuel d'un Environnement d'Apprentissage Intelligent, basé sur l'interaction de quatre composantes (connaissances, apprenant, interventions, interface).
---

# MODÈLE : Architecture d'un EIA

## 📌 Description
Ce modèle conceptuel décrit l'**architecture fonctionnelle sur laquelle repose un Environnement d'Apprentissage Intelligent (EIA)**. Il est fondé sur l'interaction dynamique entre quatre composantes principales qui permettent au système de personnaliser l'apprentissage.

Comme le souligne Paquette et al. (2022, p. 539), il existe un "consensus dans les travaux sur les EIA" autour de ce modèle à quatre composantes. Toute spécialisation de la MIENA pour les EIA doit donc s'assurer de la conception de chacun de ces modules.

---
## 📚 Connaissances mobilisées et liens
Le modèle **[[MOD_ Architecture d'un EIA]]** est en relation avec d'autres connaissances de la manière suivante :

- **Composition (C)** : Le modèle **se compose de** quatre sous-modèles qui interagissent :
    - Composition:: [[MOD_ Modèle des connaissances du domaine]]
    - Composition:: [[CONC_ Modèle de l'apprenant]]
    - Composition:: [[CONC_ Modèle des interventions pédagogiques]]
    - Composition:: [[MOD_ Modèle de communication et de l'interface]]
- **Régulation (R)** : Il **régule** le savoir-faire de conception d'un EIA :
    - Régulation:: "[[CS_Spécialisation_MIENA_Spécialiser la MIENA pour concevoir un Environnement d’Apprentissage Intelligent (EIA)]]"
- **Intrant-Produit (I/P)** : Il **a pour produit** un système d'apprentissage personnalisé :
    - Produit:: [[CONC_ Environnement Numérique d’Apprentissage (ENA)]] de type EIA

---
## 🔄 Éléments de Documentation (ED) associés

### ➤ ED Entrants (Inputs)
* **ED C-2* (212*)** : Modèle cognitif principal (qui devient le modèle du domaine)

### ➤ ED Sortant (Output)
* **ED P-8-EIA** : Modèle de l'apprenant
* **ED P-9-EIA** : Modèle des interventions pédagogiques
* Versions adaptées des **ED de l'axe médiatique** pour le modèle de communication.

---
## 📋 Format
- **Modèle conceptuel**, souvent représenté par un schéma illustrant les flux d'information entre les quatre composantes.

---

## 🔎 QQOQCCP+ détaillé

### Qui ?
- Le **concepteur pédagogique** et le **spécialiste technique**, qui doivent collaborer étroitement pour concevoir et implémenter cette architecture.

### Quoi ?
- Une **architecture logicielle et pédagogique** qui permet à un ENA de s'adapter à l'apprenant.

### Où ?
- Au cœur de la **conception d'un EIA**, lors de la spécialisation de la méthode MIENA.

### Quand ?
- Dès les **premiers cycles de conception**, car cette architecture influence tous les aspects du projet.

### Comment ?
- En concevant ou en adaptant les quatre composantes :
    1. **Modèle du domaine** : Ce que l'ENA enseigne (fourni par l'axe cognitif de la MIENA).
    2. **Modèle de l'apprenant** : Ce que le système sait de l'apprenant (à concevoir via **SF_ EIA1**).
    3. **Modèle des interventions** : Comment le système agit (à concevoir via **SF_ EIA2**).
    4. **Modèle de communication** : Comment le système interagit avec l'apprenant (à concevoir dans l'axe médiatique).

### Combien ?
- **Une architecture unique** qui structure l'ensemble de l'EIA.

### Pourquoi ?
- Pour **créer un système capable de personnalisation**, qui peut diagnostiquer les besoins de l'apprenant et y répondre de manière adaptée.
- Pour **fournir un cadre de conception robuste et éprouvé** pour le développement d'ENA sophistiqués.

### ✅ Preuves / Indicateurs de réussite
- Les quatre composantes du modèle sont clairement définies dans le devis de l'ENA.
- Le prototype démontre une interaction fonctionnelle entre les quatre modèles (ex: le système utilise les données du modèle de l'apprenant pour déclencher une intervention et l'afficher via l'interface).sd