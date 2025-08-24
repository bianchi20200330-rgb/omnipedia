
Voici **comment créer des hyperliens internes dans une note Obsidian** :

---

## 🔗 1. **Créer un lien vers une autre note**

Utilisez des doubles crochets `[[nom de la note]]`

**Exemple :**

```markdown
Voir aussi : [[Prologue - Qu'est-ce qu'un Américain ?]]
```

- Cela créera un lien vers une note appelée exactement :  
    `Prologue - Qu'est-ce qu'un Américain ?`
    
- Si elle n’existe pas encore, Obsidian proposera de la créer.
    

---

## 🧩 2. **Créer un lien vers un **titre spécifique** dans une autre note**

Ajoutez un `#` après le nom de la note pour pointer vers un titre de section.

**Exemple :**

```markdown
[[Ailleurs, chez moi|Douglas Kennedy#Jazz : le grand répertoire américain]]
```

- Si la note s’appelle **Douglas Kennedy** (ou _Ailleurs, chez moi_), et qu’elle contient un titre `## Jazz : le grand répertoire américain`, ce lien vous y mènera.
    

---

## 🪧 3. **Créer un lien avec un nom affiché personnalisé**

Utilisez le symbole `|` pour spécifier un texte à afficher différent du nom de la note.

**Exemple :**

```markdown
[[Prologue - Qu'est-ce qu'un Américain ?|Lire le prologue]]
```

Cela affichera : **Lire le prologue** (en lien).

---

## 📎 4. **Créer un lien vers une **ancre spécifique** (si vous utilisez des ancres Markdown)**

Moins courant, mais possible si vous utilisez des balises HTML comme :

```markdown
<a name="monancre"></a>
```

Puis utilisez :

```markdown
[[Ma note#^monancre]]
```

---

## ✏️ 5. **Créer un lien à partir d’un tag ou d’un mot-clé**

Si vous structurez vos notes avec votre typologie (par exemple : `#CONC`, `#MOD`, etc.), vous pouvez créer des **index** :

```markdown
- [[Concepts clés]]
- [[Modèles et théories]]
```

Puis dans chacune de ces notes :

```markdown
#CONC [[Définition de l’Américain]]
#MOD [[La pensée conservatrice]]
```

---

Souhaitez-vous que je vous prépare un **modèle de page de type inventaire de connaissances** (selon vos catégories CONC, FAITS, MOD, etc.) avec des hyperliens internes déjà prêts à copier-coller dans Obsidian ?