---
titre: Fiche des balises utiles de Templater pour Obsidian
date_creation: 2025-05-11
tags: #templater #obsidian #automatisation #productivité
---

# ⚙️ Fiche des balises Templater pour automatiser vos notes dans Obsidian

## 📅 Date et heure
| Balise Templater                           | Résultat                                  |
|---------------------------------------------|-------------------------------------------|
| <% tp.date.now("YYYY-MM-DD") %>            | Date actuelle au format AAAA-MM-JJ        |
| <% tp.date.now("HH:mm") %>                 | Heure actuelle (24h)                      |
| <% tp.date.now("dddd, MMMM Do YYYY") %>    | Date complète formatée (ex : Lundi, Mai 11e 2025) |

## 📝 Informations sur la note
| Balise Templater                           | Résultat                                  |
|---------------------------------------------|-------------------------------------------|
| <% tp.file.title %>                        | Nom du fichier actuel (sans extension)    |
| <% tp.file.path() %>                       | Chemin complet de la note                 |
| <% tp.file.creation_date("YYYY-MM-DD") %>  | Date de création du fichier               |

## 🔗 Liens et organisation
| Balise Templater                           | Résultat                                  |
|---------------------------------------------|-------------------------------------------|
| [[<% tp.date.now("YYYY-MM-DD") %>]]        | Lien vers la note du jour (Daily Note)    |
| [[<% tp.file.title %>]]                    | Lien vers la note elle-même               |

## 🎯 Utilisations avancées
| Balise Templater                           | Usage                                     |
|---------------------------------------------|-------------------------------------------|
| <%* tp.user.custom_function() %>            | Appeler une fonction utilisateur personnalisée |
| <% tp.cursor %>                            | Place le curseur à cet endroit après insertion |

## 💡 Astuce
- Vous pouvez insérer des **variables, dates, titres, liens dynamiques dans vos modèles.**
- Les balises Templater doivent être insérées **via "Templater : Insert template"** et non via l'insertion native d'Obsidian.

## 🔧 Exemples de modèle prêt à l’emploi
```markdown
---
date: <% tp.date.now("YYYY-MM-DD") %>
heure: <% tp.date.now("HH:mm") %>
titre: <% tp.file.title %>
---

# <% tp.file.title %>

## Objectif du jour
> Note prise le <% tp.date.now("dddd, MMMM Do YYYY") %> à <% tp.date.now("HH:mm") %>.
```

## Ressources utiles
- [Documentation officielle Templater](https://silentvoid13.github.io/Templater/)
- [Forum Obsidian Templater](https://forum.obsidian.md/t/templater-dynamic-templates/)
