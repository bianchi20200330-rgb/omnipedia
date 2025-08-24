
# 📋 Tableau de référence des champs YAML pour Excalibrain et Dataview

Ce tableau résume quels champs sont :
- ✅ lus par **Excalibrain** pour générer le graphe
- ✅ exploitables par **Dataview**
- ✅ utiles pour la **lecture humaine** et la structuration

| Champ YAML       | Utilisé par Excalibrain | Utilisé par Dataview | Utile pour l'humain | Rôle principal                                           |
|------------------|--------------------------|------------------------|----------------------|----------------------------------------------------------|
| `parents:`       | ✅ (si configuré)         | ✅                     | ✅                   | Déclare les parents (logique ascendante, bottom-up)      |
| `children:`      | ✅ (si configuré)         | ✅                     | ✅                   | Déclare les enfants (logique descendante, top-down)      |
| `liens:`         | ✅ (si configuré)         | ✅                     | ✅                   | Champ personnalisé pour désigner enfants ou parents       |
| `lien:`          | ✅ (interne à `parents:`) | ✅                     | ✅                   | Note cible (équivalent de `cible:`), utilisé dans un lien |
| `cible:`         | ✅ (interne à `liens:`)   | ✅                     | ✅                   | Note cible dans une relation descendante                 |
| `type_lien:`     | ❌                        | ✅                     | ✅                   | Type de relation (C, S, A…) selon la typologie Paquette  |
| `commentaire:`   | ❌                        | ✅                     | ✅                   | Précision sur le sens du lien                            |
| `type_objet:`    | ❌                        | ✅                     | ✅                   | Sert à filtrer les notes : concept, compétence, etc.     |
| `type_connaissance:` | ❌                   | ✅                     | ✅                   | Sert à classifier selon la typologie Bianchi             |
| `tags:`          | ❌ (Obsidian natif)       | ✅                     | ✅                   | Mots-clés pour recherche et classification                |

---

## 🧠 Conseil d’usage

Même si Excalibrain **n’utilise pas tous les champs**, ils ne posent **aucun conflit**.

✅ Tu peux les inclure **dans toutes tes relations YAML** pour plus de rigueur, et les exploiter dans Dataview.

---

