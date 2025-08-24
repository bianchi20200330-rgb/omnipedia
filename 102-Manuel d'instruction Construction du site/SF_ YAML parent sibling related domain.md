

C'est la distinction la plus importante et la plus subtile pour créer un réseau de connaissances vraiment riche. La différence est une question de **nature de la relation**.

En résumé :

- **`Sibling` (Frère/Sœur) :** C'est une relation **spécifique et structurée**. Elle implique une similarité, un parallélisme ou une alternative. C'est un lien **précis**.
    
- **`Related` (Lié à) :** C'est une relation **générique et non structurée**. Elle sert de "fourre-tout" pour toute connexion pertinente qui n'est ni hiérarchique (`parent`/`child`) ni de pair (`sibling`). C'est un lien **flexible**.
    

---

### La Métaphore pour les distinguer

- `parent` / `child` : C'est un **arbre généalogique**. La lignée est claire.
    
- `sibling` : Ce sont les **frères et sœurs** dans cet arbre. Ils partagent les mêmes parents.
    
- `related` : Ce sont les **amis, collègues, et voisins de la famille**. Ils sont connectés, leur influence est importante, mais ils ne font pas partie de la structure familiale directe.


=========================================

Excellente question pour compléter le tableau final ! `domain` opère à un tout autre niveau que `sibling` et `related`. C'est une question d'**échelle** et de **fonction**.

Si `sibling` et `related` décrivent les relations _entre_ des notes proches, `domain` définit le **contexte global** dans lequel toutes ces relations existent.

---

### Synthèse Finale : La Place de Chacun

Utilisons une métaphore simple : l'adresse postale d'une idée.

#### 1. `domain` : Le Pays ou la Province de l'Idée

- **Rôle :** Le **Continent Thématique**. C'est le champ de connaissance le plus large auquel la note appartient.
    
- **Question à laquelle il répond :** "À quel grand sujet appartient cette idée, peu importe où elle se trouve dans la hiérarchie ?"
    
- **Fonction principale :** **Regroupement global**. Il vous permet de rassembler d'un coup toutes les notes d'un même sujet pour des tableaux de bord ou des synthèses (très puissant avec Dataview).
    

#### 2. `parent` : La Ville et la Rue de l'Idée

- **Rôle :** La **Position Hiérarchique**. C'est l'idée directement supérieure.
    
- **Question à laquelle il répond :** "De quelle idée plus générale celle-ci découle-t-elle ?"
    
- **Fonction principale :** **Structure verticale**. Il construit l'arborescence de votre pensée.
    

#### 3. `sibling` : Le Voisin sur la Même Rue

- **Rôle :** L'**Alternative Directe**. C'est une note de même nature et de même niveau hiérarchique.
    
- **Question à laquelle il répond :** "Quelle est l'autre option ou l'autre version de cette idée ?"
    
- **Fonction principale :** **Comparaison et navigation latérale**.
    

#### 4. `related` : La Référence "Voir Aussi"

- **Rôle :** La **Connexion Pertinente mais Non-Structurée**. C'est un lien vers une idée qui est connectée d'une manière intéressante mais qui n'appartient pas à la même structure hiérarchique directe.
    
- **Question à laquelle il répond :** "Quelle autre idée, même très différente, est importante à connaître en lien avec celle-ci ?"
    
- **Fonction principale :** **Enrichissement et découverte (sérendipité)**.
    

---

### L'Exemple Ultime

Prenons une note très spécifique : **`[[Chunking (Psychologie Cognitive)]]`** (le découpage de l'information).

YAML

```
# --- Le Contexte Global ---
domain: [[Ingénierie Pédagogique MOC]]

# --- La Structure Hiérarchique ---
parent: [[Théorie de la Charge Cognitive]]

# --- La Navigation Latérale ---
sibling: [[Technique de la Répétition Espacée]]

# --- Les Connexions Riches ---
related: [[Mnémotechnique]], [[Design UX pour la lisibilité]]
---
```

**Analyse complète :**

- **`domain` :** Cette note sur le "Chunking" fait partie de votre grand vault sur l'**Ingénierie Pédagogique**. Si vous faites une recherche sur ce domaine, elle apparaîtra.
    
- **`parent` :** Elle est un concept enfant de la **Théorie de la Charge Cognitive**.
    
- **`sibling` :** Elle est une **technique de mémorisation**, tout comme la **Répétition Espacée**. Ce sont deux outils de même niveau que l'on pourrait comparer.
    
- **`related` :** Elle est liée à la **Mnémotechnique** (un domaine plus large) et au **Design UX** (une application dans un autre champ).
    

En résumé, vous avez maintenant une pyramide de liens, du plus général au plus spécifique :

1. **`domain`** (Très global : la forêt)
    
2. **`parent`** (Hiérarchique : la branche)
    
3. **`sibling`** (Parallèle : la branche d'à côté)
    
4. **`related`** (Associatif : une liane vers une autre forêt)