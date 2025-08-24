

## ✅ **Solutions pour typer les liens dans Obsidian (workarounds efficaces)**

### 1. **Utiliser des notes-relation ("typed link notes")**

Créer des notes qui décrivent **le type de lien**, ex. :

markdown

CopierModifier

`# [[Concept A]] → [[Spécialisation]] → [[Concept B]]`

Avec des fichiers comme :

- `Spécialisation.md` : décrivant le lien `S` selon Paquette.
    
- `Composition.md`, `Régulation.md`, `Application.md`, etc.
    
# [[Concept A]]
→ [[Spécialisation]] → [[Concept B]]

Cela permet d’utiliser **les graphes filtrés** par type de lien.

---

### 2. **Utiliser les liens Markdown avec commentaires**

Dans une note :

markdown

CopierModifier

`[[Concept B]] ← (type: S) [[Concept A]]`

[[Concept B]] ← (type: S) [[Concept A]]


ou

markdown

CopierModifier

`[[Utiliser un microscope]] (lien: Application A) → [[Observer des cellules]]`

[[Utiliser un microscope]] (lien: Application A) → [[Observer des cellules]]


---

### 3. **Utiliser Dataview ou DataviewJS**

Créer une structure typée dans le frontmatter et dans les corps de texte, par exemple :

markdown

CopierModifier

`--- type: concept liens:   - cible: Concept B     type: S   - cible: Procédure C     type: A ---`

Puis interroger ou visualiser ces liens dans un tableau avec Dataview.

---

### 4. **Utiliser un plugin tiers : Excalibrain ou Juggl**

- **[Excalibrain](https://github.com/zsviczian/excalibrain)** : permet de représenter visuellement des relations **typées** (parent, enfant, lien personnalisé).
    
- **Juggl** : plugin de graphe avancé avec des options pour typer les relations en les annotant.