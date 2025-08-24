

> **“Chaque note a une place dans l’ensemble”**,  
> je veux dire que :  
> **chaque élément que tu crées (note, concept, compétence…) est intégré dans une structure plus large, cohérente et connectée.**

---

## 🔎 Concrètement, cela signifie que ta note :

1. **Fait partie d’un système** :  
    Elle est liée à au moins une autre note — elle **n’est pas orpheline**.
    
2. **A un ou des liens explicites** :
    
    - Elle **provient d’un parent** (`parents:`)
        
    - Elle **conduit à des enfants** (`liens:` ou `children:`)
        
    - Elle **a un rôle défini** (concept, compétence, principe, etc.)
        
3. **Est intégrée dans une logique pédagogique ou conceptuelle** :
    
    - Soit dans un **modèle de domaine**
        
    - Soit dans un **scénario**
        
    - Soit dans un **profil de compétence**
        

---

## 📘 Exemples

### 🔸 Mauvais exemple : note isolée

```markdown
# Rendement thermique
La quantité d’énergie utile divisée par l’énergie totale reçue.
```

❌ Cette note :

- n’a **aucun parent** (pas liée à une compétence, concept ou procédure)
    
- ne dit **ni ce qu’elle est**, ni où elle s’insère
    
- est donc **difficile à retrouver, à exploiter, à enseigner**
    

---

### ✅ Bon exemple : note intégrée

```yaml
---
titre: Rendement thermique
type_objet: procédure
type_connaissance: procédurale
parents:
  - lien: [[Calculer le rendement thermique]]
    type_lien: C
---
```

👉 Là, tu sais :

- Ce que c’est (`procédure`, `connaissance procédurale`)
    
- À quelle compétence elle appartient
    
- Quel est **son rôle dans l’ensemble**
    

---

## 🎯 Pourquoi c’est important ?

Parce que **ton système de connaissance devient** :

- plus **navigable** (avec Excalibrain),
    
- plus **interrogeable** (avec Dataview),
    
- plus **transmissible** (pour un autre formateur ou un apprenant),
    
- plus **diagnosticable** (tu vois ce qui est isolé ou manquant),
    
- et surtout : plus **vivant**.
    

---

Souhaites-tu un outil (fichier, requête ou visuel) pour **repérer les notes orphelines** dans ton vault Obsidian ?