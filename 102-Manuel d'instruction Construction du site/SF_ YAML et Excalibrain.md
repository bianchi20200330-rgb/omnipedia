

🟢 **Oui, Excalibrain reconnaît parfaitement la partie `liens:` dans le YAML**, à condition que tu le configures pour cela dans ses **paramètres de “Field Mapping”**.

---

## ✅ Étapes pour qu’Excalibrain reconnaisse `liens:` comme des relations :

### 1. Dans chaque note, structure ton YAML comme ceci :

```yaml
---
titre: Thermodynamique
type_connaissance: conceptuelle
liens:
  - cible: [[Énergie]]
    type_lien: S
  - cible: [[Chaleur]]
    type_lien: C
---
```

> 🔹 `liens:` est une **liste**  
> 🔹 Chaque entrée contient un `cible:` qui pointe vers une autre note  
> 🔹 `type_lien:` est facultatif pour Excalibrain, mais utile pour toi (ou pour Dataview)

---

### 2. Configure Excalibrain pour qu’il lise ce champ

#### 🧭 Dans Obsidian :

- Ouvre les **Paramètres → Excalibrain**
    
- Cherche la section **“Field Mapping”** ou **“Parent field names”**
    
- Ajoute `liens` dans la liste des champs à interpréter comme des relations
    

Par exemple :

```yaml
parents:
  - liens
```

Cela dit à Excalibrain :

> "Va lire les valeurs dans `liens:` pour identifier les parents (ou enfants) de cette note."

---

### 3. Résultat visuel :

En ouvrant `[[Thermodynamique]]`, tu verras :

- Des flèches sortantes vers `[[Énergie]]` et `[[Chaleur]]`
    
- Si tu as activé “Directed links”, les flèches auront un sens
    

---

## 🧠 Astuce

Même si Excalibrain **ne lit pas `type_lien:`**, tu peux l'utiliser :

- Pour structurer ta pensée
    
- Pour trier et filtrer avec **Dataview**
    
- Pour générer des graphes plus riches plus tard
    

---

Souhaites-tu que je t’envoie un exemple complet :

- D’une **note avec champ `liens:` bien formaté**
    
- D’une **configuration Excalibrain minimale**
    
- Et d’une **note type YAML prête à coller** ?

**********************************************************

## En résumé

Tu peux choisir librement entre :

### 🔹 `parents:` + `lien:` (si tu préfères remonter aux sources)... NON!

yaml

CopierModifier

`parents:   - lien: [[Compétence générale]]     type_lien: S`

===============================================================

### 🔸 ou `liens:` + `cible:` (si tu pars du haut vers le bas)  OUI!

yaml

CopierModifier

`liens:   - cible: [[Sous-compétence 1]]     type_lien: S`

===========================================================
Mais ne mélange pas les deux styles dans la même note.