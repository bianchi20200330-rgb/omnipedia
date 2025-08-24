
Très bonne question 👌 Je vais clarifier.

---

## 🧩 **Alias dans Obsidian**

### 1. Définition

Un **alias** est un **autre nom** que vous pouvez donner à une note, pour la retrouver ou y faire référence plus facilement.

---

### 2. Où ça se met ?

👉 **Uniquement dans le YAML** (le petit bloc en haut de la note, entre `---`).

Exemple dans une note appelée **Connaissances factuelles** :

```yaml
---
aliases: [CF, Faits, Données de base]
tags: [type/FAITS]
---
# Connaissances factuelles

Définition : ...
```

---

### 3. Comment ça marche ?

- Votre note s’appelle **Connaissances factuelles.md**
    
- Mais grâce aux alias :
    
    - `[[CF]]`
        
    - `[[Faits]]`
        
    - `[[Données de base]]`
        

redirigeront **tous vers la même note**.

Cela permet d’alléger vos liens, surtout quand vos titres de notes sont longs.

---

### 4. Alias dans le texte narratif ?

❌ Non, on ne met pas “alias” directement dans le corps du texte.  
✅ On les utilise **indirectement** en créant des liens plus courts ou plus naturels.

Exemple dans votre narration :

```markdown
Cette compétence mobilise [[CF]] et [[Connaissances procédurales]].
```

Le lecteur clique sur `CF` → arrive sur _Connaissances factuelles_.

---

## ✅ Résumé

|Élément|Où ça se met ?|À quoi ça sert ?|
|---|---|---|
|**Alias**|Dans le YAML d’une note|Donner des **noms alternatifs** à une note|
|Utilisation pratique|Dans vos `[[...]]`|Raccourcir, alléger, adapter selon le contexte|

---

Voulez-vous que je vous montre un **exemple complet** avec :

1. Une note de **Connaissance** avec alias,
    
2. Une note de **Compétence** qui y fait référence avec alias dans le texte ?