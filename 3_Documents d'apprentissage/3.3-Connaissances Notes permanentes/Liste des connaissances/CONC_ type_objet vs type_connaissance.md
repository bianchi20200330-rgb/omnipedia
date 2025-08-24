# 🧱 Fiche : `type_objet` vs `type_connaissance` dans la modélisation pédagogique (inspirée de Paquette)

> 🎓 Comprendre la différence entre la **fonction structurelle** d’un objet et la **nature du savoir** qu’il mobilise.

---

## 1. 🎯 `type_objet` = Rôle structurel dans le système d’apprentissage

| `type_objet:`        | Fonction ou rôle dans le modèle                          | Exemple                       |
|----------------------|-----------------------------------------------------------|-------------------------------|
| `concept`            | Élément abstrait, notion fondamentale                    | [[Énergie]]                   |
| `procédure`          | Série d’actions ordonnées                                 | [[Mesurer une température]]   |
| `principe`           | Loi ou régularité générale entre concepts                 | [[Loi d’Ohm]]                 |
| `activité`           | Ce que fait un apprenant                                  | [[Réaliser une expérience]]   |
| `ressource`          | Document ou outil de soutien                              | [[Vidéo sur la gravité]]      |
| `objectif`           | But à atteindre                                           | [[Comprendre l’accélération]] |
| `compétence`         | Capacité intégrée et mobilisable                          | [[Analyser une situation clinique]] |
| `scénario`           | Séquence pédagogique structurée                           | [[Module 3 : Résolution de problème]] |

---

## 2. 🧠 `type_connaissance` = Nature du savoir représenté ou mobilisé

| `type_connaissance:` | Définition                                                 | Exemple                       |
|----------------------|-------------------------------------------------------------|-------------------------------|
| `conceptuelle`       | Savoir abstrait, généralisable                              | [[Thermodynamique]]           |
| `factuelle`          | Fait ou donnée vérifiable                                   | [[Température de l’eau]]      |
| `procédurale`        | Savoir-faire, savoir comment faire                          | [[Mesurer la pression]]       |
| `comportementale`    | Savoir-être, attitude, posture                              | [[Travailler en équipe]]      |
| `métacognitive`      | Savoir s’auto-réguler et évaluer son propre apprentissage   | [[Planifier une tâche complexe]] |

---

## 3. 🧩 Exemple combiné

```yaml
---
titre: Mesurer la température
type_objet: procédure
type_connaissance: procédurale
description: Méthode standardisée pour relever une température à l’aide d’un thermomètre.
---
```

- 🔹 **Objet** : une procédure (structure d’action)
- 🧠 **Connaissance mobilisée** : savoir-faire (procédural)

---

## 4. 📘 Dans un graphe MOT ou Excalibrain

```
[Concept : Thermodynamique]
     ↓ (Composition)
[Procédure : Mesurer la température]
     ↓ (Application)
[Activité : TP en laboratoire]
     ↓ (Appuyée par)
[Ressource : Vidéo explicative]
```

Chaque objet est **typé**, et les liens sont également **typés**.

---

## ✅ En résumé

| Élément            | Question clé                                      |
|--------------------|---------------------------------------------------|
| `type_objet:`      | “Quel est le rôle structurel de cet élément ?”    |
| `type_connaissance:` | “Quel type de savoir cela représente ou active ?” |

📘 Tu peux combiner les deux dans tes propriétés YAML pour une modélisation complète.
