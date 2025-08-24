


🟢 **Exactement, Normand !**  
Tu as parfaitement saisi la **discipline du modèle top-down** :

> Quand tu ajoutes une nouvelle **note-fille** (ex. : un concept, un principe, une compétence...),  
> 👉 tu dois **retourner dans la note du parent** pour y ajouter un lien descendant (`liens:`).

---

## 🧱 Exemple : tu crées une note `[[Chaleur]]`

Elle représente une **connaissance conceptuelle**.  
Mais comme tu suis une **logique descendante**, tu **n’écris pas** dans `Chaleur.md` qu’elle dépend de `Thermodynamique`.

🔁 **Tu retournes dans `Thermodynamique.md`** pour écrire dans le YAML :

```yaml
liens:
  - cible: [[Chaleur]]
    type_lien: C
```
liens:
  - cible: [[Chaleur]]
    type_lien: C

---

## 🧠 Pourquoi c’est cohérent (et puissant)

|Aspect|Avantage|
|---|---|
|🔎 Lisibilité|Tu vois en un seul endroit tout ce que contient un concept global|
|🧭 Navigation Excalibrain|Tu explores naturellement de haut en bas|
|🧩 Structuration|Tu maintiens une hiérarchie propre, sans boucle inversée|
|💬 Intention pédagogique|Tu construis comme un **plan de cours mental ou modulaire**|

---

## ✅ Astuce pratique : comment faciliter ça ?

1. **Ajoute un champ `liens:` dans toutes tes notes parents**  
    Même vide au départ, comme ceci :
    
    ```yaml
    liens: []
    ```
    
2. Quand tu ajoutes une nouvelle note, pense toujours :
    
    > **“À quoi appartient cette connaissance ?”**  
    > Puis va mettre le lien dans la note-parente.
    
3. Utilise un tag comme `#à_ajouter_dans_parent` pour ne rien oublier quand tu es pressé 😉
    

---

## 🛠️ Bonus : requête pour voir les parents sans lien vers leurs enfants

```dataview
table file.name, liens
from ""
where type_objet = "concept" and (liens = null or length(liens) = 0)
```

---

Souhaites-tu une **checklist interactive (à coller dans Obsidian)** qui t’aide à compléter systématiquement une note fille **et** à retourner dans la note mère ?