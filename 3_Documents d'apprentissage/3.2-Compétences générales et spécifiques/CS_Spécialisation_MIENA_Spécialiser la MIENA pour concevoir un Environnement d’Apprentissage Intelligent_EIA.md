---
title: CS_Spécialisation_MIENA_Spécialiser la MIENA pour concevoir un Environnement d’Apprentissage Intelligent_EIA
aliases:
  - Spécialisation EIA
  - Concevoir un EIA avec MIENA
tags:
  - compétence/spécifique
  - MIENA
  - spécialisation
  - EIA
up: "[[COMP_ Concevoir, développer et implanter un Environnement Numérique d’Apprentissage (ENA) à l’aide de la méthode MIENA]]"
related:
  - "[[CS_Spécialisation_MIENA_Spécialiser la MIENA pour concevoir un ENA autonome (CLOM ou MOOC)]]"
  - "[[CS_Spécialisation_MIENA_Intégrer la diversité culturelle dans un ENA]]"
source: "[[DOC_ Paquette et al 2022_Chap14_Architecture d'une nouvelle méthode d'ingénierie des ENA_ MIENA]]"
---

#axe/spécialisation_MIENA

[[COMP_ Concevoir, développer et implanter un Environnement Numérique d’Apprentissage (ENA) à l’aide de la méthode MIENA]]

| 🔢 Code | 💡 Savoir-faire (procédural) | 📘 Référence MIENA (Chap. 14) |
| --- | --- | --- |
| **SF-EIA1** | Concevoir le **modèle de l'apprenant**. | Section 2.1 (p. 539-540) |
| **SF-EIA2** | Concevoir le **modèle des interventions pédagogiques**. | Section 2.1 (p. 541) |
| **SF-Adapt** | **Adapter** les savoir-faire du tronc commun (scénarisation, médiatisation). | Section 2.1 (p. 541) |

### [[SF_ EIA1_ Concevoir le modèle de l'apprenant]]

- **Description** :
  Définir ce que le système doit savoir sur l'apprenant (connaissances maîtrisées, progression, préférences, etc.) et structurer ces informations dans un modèle dynamique. Ce savoir-faire inclut également la conception des activités d'évaluation (pré-tests, quiz, suivi des actions) qui permettent d'alimenter ce modèle.

- **Techniques utilisées** :
  - **Définition du contenu du modèle** : spécifier les informations à suivre sur l'apprenant (état cognitif, métacognitif, affectif).
  - **Conception des activités d'évaluation** : créer des pré-tests ou des évaluations continues pour collecter les données.
  - **Utilisation des inférences** pour mettre à jour le modèle à partir des interactions de l'apprenant.
  - **Production d'un document de conception** décrivant le modèle et ses mécanismes de mise à jour (**ED P-8-EIA**).

### [[SF_ EIA2_ Concevoir le modèle des interventions pédagogiques]]

- **Description** :
  Définir comment l'EIA va agir en fonction des informations contenues dans le modèle de l'apprenant. Ce savoir-faire consiste à créer des stratégies d'assistance, par exemple en concevant des **agents conseillers** qui fonctionnent sur la base de règles pédagogiques.

- **Techniques utilisées** :
  - **Définition de règles pédagogiques** de type "SI [condition sur le modèle de l'apprenant] ALORS [action de recommandation]".
  - **Conception d'agents conseillers** qui incarnent ces règles.
  - **Identification des points d'insertion** de ces agents dans les scénarios pédagogiques des UA.
  - **Production d'un document de conception** décrivant les règles des agents et leurs points d'insertion (**ED P-9-EIA**).

### [[SF_ Adapt_ Adapter les savoir-faire du tronc commun pour l'EIA]]

- **Description** :
  Modifier les savoir-faire existants des axes pédagogique et médiatique pour intégrer les composantes intelligentes. Il ne s'agit pas seulement d'ajouter de nouvelles fonctionnalités, mais d'adapter l'ensemble de la conception pour qu'elle puisse supporter la personnalisation.

- **Techniques utilisées** :
  - **Adapter les scénarios pédagogiques (SF_ P5)** en y intégrant les "points d'insertion" où les agents conseillers peuvent se déclencher.
  - **Adapter les modèles médiatiques (SF_ M4)** en prévoyant des zones dans l'interface pour afficher les recommandations, les rétroactions personnalisées ou les adaptations de contenu.
