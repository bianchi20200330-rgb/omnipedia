
Oui, absolument.

C'est l'un des grands avantages de mettre les mots-clés dans le YAML. **Tout mot-clé que vous placez dans la section `tags:` du YAML est automatiquement détecté par Obsidian et s'ajoute à la liste des mots-clés dans le panneau de droite**.

---

## Comment ça fonctionne

Obsidian analyse en permanence l'ensemble de votre "vault" (votre collection de notes). Lorsqu'il lit une note, il regarde deux endroits pour trouver les mots-clés :

1. **Le YAML** : Il analyse la section `tags:` au début du fichier.
    
2. **Le corps du texte** : Il cherche tous les mots précédés d'un `#`.
    

Il fusionne ensuite ces deux listes pour créer l'index complet que vous voyez dans le panneau des mots-clés à droite.

---

## Pourquoi c'est une bonne pratique

Placer vos mots-clés principaux dans le YAML, comme nous l'avons décidé, est une excellente pratique pour plusieurs raisons :

- **Organisation** : Cela garde vos métadonnées propres et séparées du contenu de votre note.
    
- **Puissance pour les plugins** : C'est la méthode la plus fiable pour que des plugins comme **Dataview** puissent interroger vos notes.
    
- **Cohérence** : Cela vous encourage à définir les catégories principales de votre note dès le début.