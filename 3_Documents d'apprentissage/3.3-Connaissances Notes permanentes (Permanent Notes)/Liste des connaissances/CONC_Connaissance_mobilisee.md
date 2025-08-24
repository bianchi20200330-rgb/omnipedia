---
titre: Connaissance mobilisée
code: CONC_Connaissance_mobilisee
type_objet: concept
type_connaissance: conceptuelle
definition: 
  Désigne une connaissance identifiée comme essentielle à la réalisation d'une compétence ou d'une activité d’apprentissage, 
  telle que formalisée dans le modèle de connaissances (ÉD 212) et référencée dans le tableau des compétences (ÉD 214).
exemples: >
  - "Procédure de diagnostic" utilisée pour la compétence : Diagnostiquer une panne
  - "Concept de cycle cellulaire" mobilisé dans une tâche de simulation en biologie
caracteristiques:
  - Ancrée dans le modèle de connaissances (ÉD 212)
  - Reliée à une ou plusieurs compétences du tableau ÉD 214
  - Peut être de tout type : concept, fait, procédure, principe, etc.
  - Sert de base au choix des contenus, activités et évaluations
utilisation_typique: >
  Dans l’ÉD 214, la colonne “Connaissances mobilisées” contient les références aux entités cognitives de l’ÉD 212.
  Cette relation constitue un lien de mobilisation (souvent de type ‘usage’, ou ‘composition’ selon Paquette).
liens:
  - type_lien: C
    cible:
      - ED_212_Modele_des_connaissances
    commentaire: La connaissance mobilisée est issue du modèle de connaissances.
  - type_lien: A
    cible:
      - ED_214_Tableau_des_competences
    commentaire: Elle est mobilisée dans la formulation de compétences spécifiques.
note: >
  Bien que certains outils utilisent un lien de type 'U' (Usage), ce type n’est pas officiel dans la typologie de Paquette.
  On lui préférera les liens de type C (composition), A (association) selon les cas.
auteur: Normand Bianchi
date_creation: 2025-07-17
---
 [[DOC_ ED_214_Tableau_des_compétences]]   → [[CONC_ Connaissance mobilisée (réf. ÉD 212) – Quoi]] 

#Paquette_et_al_2022 

# Connaissance mobilisée

Une connaissance mobilisée est une entité du modèle de connaissances (ÉD 212) qui sert de **base cognitive ou procédurale** à la réalisation d’une compétence (ÉD 214). Elle peut être un fait, un concept, une procédure ou un principe.

Elle permet de **relier le contenu cognitif aux objectifs pédagogiques** et de **structurer la conception des activités d’apprentissage et d’évaluation**.



Exemples:

- -des **concepts** (ex. : tension électrique, cellule eucaryote),
    
- des **faits** (ex. : la Terre tourne autour du Soleil),
    
- des **procédures** (ex. : procédure d’accueil client),
    
- des **principes** (ex. : loi de l’offre et de la demande),
    
- des **jugements / critères / attitudes** (ex. : esprit critique, précision terminologique).