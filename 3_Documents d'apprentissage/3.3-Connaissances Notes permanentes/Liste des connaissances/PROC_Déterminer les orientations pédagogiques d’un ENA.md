---
titre: Déterminer les orientations pédagogiques d’un ENA
code: PROC_Orientations_pedagogiques_ENA
type_objet: procédure
type_connaissance: procédurale
definition: |
  Procédure visant à structurer les orientations pédagogiques d’un environnement numérique d’apprentissage (ENA) à partir des compétences identifiées et des connaissances à mobiliser. Elle s’appuie sur les prescriptions du document ÉD 220 – Modèle pédagogique, qui définit les regroupements d’unités d’apprentissage, les intentions pédagogiques dominantes,  les modalités pédagogiques et les cheminements recommandés.
auteur: Normand Bianchi
date_creation: 2025-07-17
but: Structurer le modèle pédagogique à partir des compétences (ED 214) et connaissances (ED 212)
tags:
  - MISA
  - procédure
  - ENA
  - pédagogie
  - ED220
  - "#MIENA"
aliases:
  - Orientations pédagogiques ENA
  - Modèle pédagogique
  - PROC_Orientations
excalibrain:
  linkDirection: bidirectional
  showInbound: true
  showOutbound: true
  position:
    x: 600
    y: 320
modules:
  - MISA
entrées:
  - - - ED_212_Modele_des_connaissances
  - - - ED_214_Tableau_des_compétences
sorties:
  - - - ED_220_Modèle_pédagogique
juggl:
  nodeLabel: Procédure ED 220
  nodeClass: procedure
---
 
→ [[DOC_ ÉD 220_Modèle_pédagogique]] 

#ÉD220

## 🎯 But

Définir les **orientations pédagogiques fondamentales** d’un environnement numérique d’apprentissage (ENA) à partir des compétences (ÉD 214) et connaissances (ÉD 212) identifiées.

---

## 📘 Ce que prescrit le document ÉD 220

Le document ÉD 220 – Modèle pédagogique stipule que cette procédure doit :

- Regrouper les compétences en **unités d’apprentissage structurées**.
- Associer à chaque unité une **intention pédagogique dominante** (ex. : appropriation, mise en pratique, intégration…).
- Déterminer les **modalités pédagogiques** (expositive, exploratoire, interactive, tutorée, autonome…).
- Identifier les **types de cheminement** (linéaire, ramifié, adaptatif, libre…).
- Assurer la **cohérence du modèle pédagogique avec le modèle des connaissances (ÉD 212)**.

---

## 🛠️ Étapes recommandées

| Étape | Description |
|-------|-------------|
| 1. Regrouper | Regrouper les compétences et savoirs issus des ÉD 212 et 214 |
| 2. Intention | Associer une intention pédagogique dominante à chaque unité |
| 3. Modalité | Choisir la modalité pédagogique adaptée (collaborative, exploratoire...) |
| 4. Cheminement | Déterminer les enchaînements possibles entre les unités |
| 5. Validation | S’assurer de la cohérence globale avec les autres modèles du SA |

---

## 📄 Fiches ou formulaires à remplir

- Tableau des unités pédagogiques : titre, compétences visées, intentions, modalités, durée, cheminement
- Schéma de cheminement ou carte conceptuelle (optionnel mais recommandé)

---

## 🔄 Connexions avec les autres ÉD

| **ÉD source** | **Cette procédure s’appuie sur :** |
|--------------|-----------------------------------|
| ÉD 212       | Modèle des connaissances          |
| ÉD 214       | Tableau des compétences           |

| **ÉD destination** | **Elle alimente :** |
|--------------------|---------------------|
| ÉD 220             | Modèle pédagogique  |
| ÉD 222             | Scénarisation des unités d’apprentissage |

---

## 🧠 Conseils opérationnels

- Commencez par une **carte conceptuelle** ou un schéma de regroupement.
- Faites valider les intentions pédagogiques par les concepteurs ou experts du domaine.
- Tenez compte des **contraintes logistiques** (durée, public, technologie).
- Inspirez-vous de **modèles existants** pour les cheminements (linéaires, modulaires, adaptatifs…).

---

## 📚 Connaissances mobilisées

| Type de connaissance | Contenu mobilisé |
|----------------------|------------------|
| Conceptuelle         | Typologie des intentions pédagogiques, modalités |
| Procédurale          | Méthode de regroupement, construction des cheminements |
| Modèles              | Modèle MISA, structure du SA |
| Principes            | Progressivité, cohérence, accessibilité |
| Contextuelle         | Contraintes de diffusion, durée, public visé |
