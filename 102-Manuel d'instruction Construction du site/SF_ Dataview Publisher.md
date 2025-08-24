

C'est une excellente question qui touche à un point technique très important de la publication de vault Obsidian.

La réponse courte est : **non, l'index ne se mettra pas à jour automatiquement sur le site web final**.

Voici l'explication détaillée :

### Le site web est "statique" ❄️

Quand vous publiez votre vault Obsidian, le processus prend une "photographie" de votre vault à un instant T et le transforme en un site web **statique**. Cela signifie que les pages du site sont des fichiers HTML fixes.

- **Dans Obsidian** : Le plugin Dataview est un programme actif. Il peut lire votre vault en temps réel et exécuter la requête pour afficher une liste à jour chaque fois que vous ouvrez la note.
    
- **Sur le site web** : Il n'y a plus de programme Dataview qui tourne en arrière-plan. Il n'y a que des pages HTML. La requête Dataview ne peut donc plus s'exécuter.
    

### ✅ La solution : "Cuire" les résultats avant de publier

Pour que votre index de mots-clés fonctionne sur votre site web, il faut "cuire" (_to bake_) les résultats de la requête avant de publier. Cela signifie qu'il faut transformer la liste dynamique en une **liste en Markdown simple et fixe**.

Il existe des plugins communautaires qui peuvent automatiser ce processus pour vous, comme **"Dataview Publisher"**.

**Comment ça marche :**

1. Vous gardez votre requête Dataview dans votre note.
    
2. Avant de publier, vous exécutez une commande du plugin "Dataview Publisher".
    
3. Le plugin va alors exécuter la requête et **remplacer le bloc de code Dataview par le résultat en Markdown**.
    
4. Vous publiez ensuite votre vault. La page contiendra une liste de liens en Markdown simple, qui fonctionnera parfaitement sur le site web.
    

En résumé, l'index sur votre site web sera une **version statique** de l'index au moment où vous l'avez "cuit" et publié. Il ne se mettra pas à jour si vous ajoutez de nouvelles notes, à moins que vous ne répétiez le processus de "cuisson" et de publication.

---

Cette vidéo sur le plugin Dataview Publish vous montre comment installer et configurer le plugin pour publier facilement vos requêtes Dataview.