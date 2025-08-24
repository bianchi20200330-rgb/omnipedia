---
titre: SF_ Sens des liens entre connaissances
type_objet: procédure
type_connaissance: cognitive
liens:
  - cible:
      - - MOD_ Types de connaissances
    type_lien: S
    commentaire: le SF est un **cas d’application** du modèle **Types de connaissances**
  - cible:
      - - 
    type_lien: 
    commentaire: 
tags:
  - Paquette_et_al_2022
  - liens
auteur: Normand Bianchi
date: 2025-07-19
---

[[SF_ Sens des liens entre connaissances ou objets du SA]] → [[MOD_ Types de connaissances]] 

#Paquette_et_al_2022 

## ✅ Clarification du lien entre :

- **[[CONC_…]]** : une **connaissance (concept, procédure, principe, etc.)** définie dans l’ÉD 212
    
- et
    
- **[[DOC_ ED_214_Tableau_des_compétences]]** : la **compétence** (ou tableau de compétences) où cette connaissance est **mobilisée**.
    

---

## 🧠 Quel est le **sens logique du lien** ?

> **La compétence mobilise la connaissance.**  
> Autrement dit : la **connaissance est utilisée dans la compétence**, mais ce n’est pas la connaissance qui contient la compétence.

Donc :

### ✅ Le **lien logique correct** va de :

```markdown
[[ED_214_Tableau_des_competences]] —mobilise→ [[CONC_Connaissance]]
```

ou, si vous êtes dans la fiche de la **compétence**, vous pouvez écrire :

```markdown
Mobilise : [[CONC_...]]
```

---

## ❌ Ce qui serait **incorrect ou inverse** :

```markdown
[[CONC_Connaissance]] → [[ED_214_Tableau_des_competences]]
```

(car ce serait comme dire : _la connaissance utilise la compétence_, ce qui n’a pas de sens pédagogique).

---

## ✅ Variante en langage plus typé (Paquette 2002 – types de liens)

|**Lien**|**Type Paquette**|**Sens**|**Exemple**|
|---|---|---|---|
|mobilise|lien d’usage (U)|compétence → connaissance|[[C1_Diagnostiquer]] —U→ [[P3_Procédure]]|
|repose sur|lien de dépendance|compétence → connaissance|[[C2_Expliquer]] —dépend de→ [[C6_Schéma]]|

---

## 🧩 Rappel du principe général :

### 🎯 En YAML ou en base de connaissances :

> Les liens sont **généralement définis depuis l’objet courant vers ce qu’il mobilise, utilise, dépend, ou spécialise**.

---

## 🧠 Cas concret : modélisation dans le fichier d’une **compétence** (ÉD_214)

Vous êtes dans :

```yaml
titre: Diagnostiquer une panne
type_objet: compétence
type_connaissance: compétence procédurale
liens:
  - cible:
      - CONC_Procédure_diagnostique
      - CONC_Composants_de_base
    type_lien: U
    commentaire: Connaissances mobilisées pour la réalisation de la compétence.
```

✅ Ici, vous êtes **dans la fiche de la compétence**, donc c’est **la compétence qui pointe vers les connaissances** (logique descendante).  
Le lien est **correct**.

---

## ❌ Mauvais sens : dans une fiche de **connaissance**, vous auriez :

```yaml
titre: Procédure de diagnostic
type_objet: connaissance procédurale
liens:
  - cible:
      - ED_214_Tableau_des_competences
    type_lien: ?
    commentaire: utilisée par la compétence (sens inverse)
```

C’est **possible**, mais **non recommandé** sauf si vous avez besoin d’un **graphe inversé** ou bidirectionnel.  
Dans MISA / Paquette, la bonne pratique est que :

> 🔁 Les **liens descendent du plus global vers les éléments mobilisés.**

---

## ✅ Règle simple pour YAML narratif ou ontologique

|**Si je suis dans…**|**Alors le lien va vers…**|**Exemple de type_lien**|
|---|---|---|
|une **compétence**|les **connaissances mobilisées** (ÉD 212)|`U` (usage), `mobilise`|
|une **activité ou tâche**|les **compétences nécessaires** (ÉD 214)|`requiert`|
|un **document ou contenu**|les **connaissances ou compétences transmises**|`explique`, `illustre`|
|un **modèle (ex. ÉD 210)**|les **types ou entités incluses**|`structure`, `spécifie`|

---