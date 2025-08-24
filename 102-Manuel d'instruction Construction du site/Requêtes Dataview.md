## Requêtes Dataview

### 1. Lister tous les concepts
```dataview
table titre, description
from ""
where type_connaissance = "conceptuelle"
```

### 2. Lister tous les liens de type "S" (spécialisation)
```dataview
table file.link as Source, liens.cible as Cible
from ""
where any(liens).type_lien = "S"
```

### 3. Lister toutes les relations avec leurs types
```dataview
table file.link as Source, liens.cible as Cible, liens.type_lien as Type_de_lien
from ""
where liens
```

### 4. Lister par auteur
```dataview
table titre, type_connaissance, description
from ""
where auteur = "Normand Bianchi"
```
