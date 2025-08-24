---
title: SF_ Adapt_ Adapter les savoir-faire du tronc commun pour l'EIA
aliases:
  - Adapter MIENA pour EIA
  - Adaptation tronc commun EIA
tags:
  - savoir_faire
  - MIENA
  - spécialisation
  - EIA
up: "[[CS_Spécialisation_MIENA_Spécialiser la MIENA pour concevoir un Environnement d’Apprentissage Intelligent (EIA)]]"
related:
  - "[[SF_ EIA1_ Concevoir le modèle de l'apprenant]]"
  - "[[SF_ EIA2_ Concevoir le modèle des interventions pédagogiques]]"
source: "[[DOC_ Paquette et al 2022_Chap14_Architecture d'une nouvelle méthode d'ingénierie des ENA_ MIENA]]"
---

# SAVOIR-FAIRE : Adapter les savoir-faire du tronc commun pour l'EIA

## 📌 Description
Ce savoir-faire consiste à **modifier les productions des axes pédagogique et médiatique** du tronc commun de la MIENA pour y intégrer les composantes intelligentes. Il ne s'agit pas de créer de nouveaux documents, mais d'enrichir et d'adapter les scénarios pédagogiques et les modèles médiatiques pour qu'ils puissent supporter et rendre visible la personnalisation de l'apprentissage.

Cette étape assure que l'intelligence de l'EIA est concrètement intégrée dans l'expérience de l'apprenant.

---
## 📚 Connaissances mobilisées

- **CONTEXTE_ Scénarios pédagogiques (SF_ P5)** : Comprendre en profondeur les scénarios existants pour y identifier les points d'intervention pertinents.
- **CONTEXTE_ Modèles médiatiques (SF_ M4)** : Comprendre la structure de l'interface pour y intégrer de nouveaux éléments d'affichage dynamique.
- **SF_ Scénarisation adaptative** : La procédure consistant à modifier un scénario pour qu'il puisse se brancher à des règles conditionnelles.
- **MOD_ Interface utilisateur adaptative** : La connaissance conceptuelle des différentes manières de présenter des informations personnalisées à un utilisateur.

---
## 🔄 Éléments de Documentation (ED) associés

### ➤ ED Entrants (Inputs)
* **ED P-9-EIA** : Modèle des interventions pédagogiques (qui dicte les adaptations à faire)
* **ED P-5* (320*)** : Scénarios pédagogiques des UA (le document à modifier)
* **ED M-4* (432*)** : Modèles médiatiques des ressources (le document à modifier)

### ➤ ED Sortant (Output)
* **Versions modifiées** des **ED P-5* (320*)** et **ED M-4* (432*)** qui intègrent les composantes de l'EIA.

---
## 📋 Format
- **Annotations et modifications** sur les modèles graphiques existants (scénarios, maquettes).
- **Ajouts aux descriptions textuelles** dans les ED concernés pour spécifier le comportement adaptatif.

---

## 🔎 QQOQCCP+ détaillé

### Qui ?
- Le **concepteur pédagogique**, qui adapte les scénarios.
- Le **spécialiste en médiatisation**, qui adapte les maquettes de l'interface.
- L'**équipe de projet**, qui valide la cohérence de ces adaptations.

### Quoi ?
- L'**intégration fonctionnelle et visuelle** des mécanismes de personnalisation dans l'ENA.
- La modification des scénarios pour y inclure des "points d'insertion" et la modification des interfaces pour afficher les recommandations.

### Où ?
- Au sein des activités des **axes pédagogique et médiatique**.
- Directement sur les documents de conception existants (scénarios, maquettes).

### Quand ?
- **Après** la conception des composantes intelligentes (**SF_ EIA1** et **SF_ EIA2**).
- Durant les **cycles de prototypage**, où ces adaptations sont testées et affinées.

### Comment ?
- En **annotant les scénarios pédagogiques** pour indiquer où et quand les agents conseillers doivent s'activer.
- En **ajoutant aux maquettes d'interface** des zones dédiées à l'affichage de messages, de conseils ou de ressources recommandées.
- En spécifiant le **comportement de l'interface** lorsque le contenu est adapté (ex: masquer une activité, en proposer une nouvelle).

### Combien ?
- Le nombre d'adaptations est directement proportionnel au nombre d'**interventions pédagogiques** définies dans l'**ED P-9-EIA**.

### Pourquoi ?
- Pour que la personnalisation conçue ne reste pas théorique mais soit **effectivement vécue par l'apprenant**.
- Pour **s'assurer que l'interface utilisateur peut gérer et afficher** les adaptations dynamiques générées par le système.
- Pour finaliser le cahier des charges technique avant la programmation de l'EIA.

### ✅ Preuves / Indicateurs de réussite
- Les versions finales des **ED P-5* (320*)** et **ED M-4* (432*)** montrent clairement les points d'adaptation.
- Le prototype de l'EIA implémente correctement ces adaptations (ex: un conseil apparaît au bon endroit dans l'interface, au bon moment du scénario).
- L'expérience utilisateur est fluide et la personnalisation semble naturelle et intégrée.