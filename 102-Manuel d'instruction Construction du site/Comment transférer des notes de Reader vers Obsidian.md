#chatGPT 

#type/SF 
## Méthode 2 : Exportation manuelle depuis Reader

Si vous préférez un contrôle total sur les notes que vous importez, vous pouvez exporter manuellement vos surlignages depuis Reader.

### Étapes à suivre :

1. **Accéder à vos surlignages dans Reader** :
    
    - Ouvrez le document souhaité dans Reader.
        
    - Cliquez sur l'onglet **Carnet de notes** dans la barre latérale droite.
        
2. **Exporter les surlignages** :
    
    - En bas du carnet de notes, cliquez sur **Exporter**.
        
    - Choisissez l'option **Télécharger les annotations** pour obtenir un fichier Markdown contenant vos surlignages et notes.[stefanimhoff.de+2Reddit+2Obsidian Forum+2](https://www.reddit.com/r/readwise/comments/18ul3mk/obsidian_export/?utm_source=chatgpt.com)
        
3. **Importer dans Obsidian** :
    
    - Placez le fichier Markdown exporté dans le dossier de votre choix au sein de votre coffre Obsidian.
        

Cette méthode est idéale pour des exportations ponctuelles ou pour une gestion manuelle de vos notes.

---
## Méthode 1 : Synchronisation automatique via le plugin officiel Readwise pour Obsidian

Cette méthode permet une synchronisation continue et personnalisable de vos surlignages et notes depuis Readwise vers Obsidian.

### Étapes à suivre :

1. **Installer le plugin Readwise Official dans Obsidian** :
    
    - Ouvrez Obsidian et accédez à **Paramètres** → **Plugins de la communauté**.
        
    - Désactivez le **Mode restreint** si nécessaire.
        
    - Cliquez sur **Parcourir** et recherchez **Readwise Official**.
        
    - Installez et activez le plugin.[GitHub+2docs.readwise.io+2Reddit+2](https://docs.readwise.io/readwise/docs/exporting-highlights/obsidian?utm_source=chatgpt.com)
        
2. **Connecter votre compte Readwise** :
    
    - Dans les paramètres du plugin, connectez-vous à votre compte Readwise pour autoriser la synchronisation.
        
3. **Configurer les options de synchronisation** :
    
    - Choisissez la fréquence de synchronisation (automatique à l'ouverture d'Obsidian ou manuelle).
        
    - Définissez le dossier de destination pour les notes importées.
        
    - Personnalisez le format des notes exportées à l'aide des modèles Jinja2 si souhaité.
        
4. **Lancer la synchronisation** :
    
    - Utilisez la palette de commandes (**Ctrl+P** ou **Cmd+P**) et recherchez **Readwise Official: Sync your data now** pour déclencher une synchronisation manuelle.[docs.readwise.io+1Reddit+1](https://docs.readwise.io/readwise/docs/exporting-highlights/obsidian?utm_source=chatgpt.com)
        

Une fois configurée, cette méthode permet une intégration fluide de vos surlignages et notes dans Obsidian, avec des options de personnalisation avancées.

===============
## Personnalisation avancée avec les modèles Jinja2

Le plugin Readwise pour Obsidian permet une personnalisation poussée du format des notes importées grâce aux modèles Jinja2. Vous pouvez ainsi définir :[GitHub](https://github.com/readwiseio/obsidian-readwise?utm_source=chatgpt.com)

- Le titre des pages.
    
- Les métadonnées (auteur, URL, catégorie, etc.).
    
- La structure des surlignages.
    
- L'inclusion ou non de certaines informations (par exemple, ignorer les surlignages avec un tag spécifique).[GitHub](https://github.com/readwiseio/obsidian-readwise?utm_source=chatgpt.com)[docs.readwise.io](https://docs.readwise.io/readwise/docs/exporting-highlights/obsidian?utm_source=chatgpt.com)
    

Pour en savoir plus sur la personnalisation des modèles, consultez la documentation officielle de Readwise.