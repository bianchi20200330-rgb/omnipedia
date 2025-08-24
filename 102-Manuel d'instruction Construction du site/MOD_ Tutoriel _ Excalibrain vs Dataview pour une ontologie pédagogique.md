# Tutoriel : Excalibrain vs Dataview pour une ontologie pédagogique

## 🎯 Objectif
Comparer **Excalibrain** (vue graphique) et **Dataview** (vue textuelle/logique) pour modéliser une **ontologie pédagogique** dans Obsidian.

---

## 🧱 Contexte : Modèle de domaine pédagogique
Prenons l’exemple d’un modèle de domaine en **physique thermique** avec :

- `[[Thermodynamique]]` : concept
- `[[Chaleur]]` : concept
- `[[Premier principe de la thermodynamique]]` : principe
- `[[Calcul du rendement thermique]]` : procédure

---

## 🖼️ Excalibrain : Vue graphique
### ✅ Ce qu’il montre
- Des bulles pour chaque note
- Des **flèches dirigées** représentant les relations (parent/enfant, liens typés)
- Navigation visuelle par clic

### 🔧 Configuration recommandée
Dans le YAML de chaque note :
```yaml
liens:
  - cible: [[Chaleur]]
    type_lien: C
```

Et dans les paramètres Excalibrain :
```yaml
parents:
  - liens
```

### 🧭 Avantages
- Vue intuitive
- Navigation rapide
- Idéal pour modéliser visuellement un **modèle de domaine**

---

## 📊 Dataview : Vue logique / textuelle
### ✅ Ce qu’il permet
- Générer des **listes dynamiques**
- Filtrer par type d’objet (`concept`, `procédure`, etc.)
- Afficher les liens typés

### 📄 Exemple de requêtes
#### Tous les concepts :
```dataview
table file.name as Concept, description
from ""
where type_connaissance = "conceptuelle"
```

#### Liens de spécialisation :
```dataview
table file.link as Source, liens.cible as Cible
from ""
where any(liens).type_lien = "S"
```

### 🧭 Avantages
- Analyse structurée
- Tableaux synthétiques
- Idéal pour diagnostiquer des profils ou tracer des compétences

---

## 🧩 Résumé comparatif

| Fonction                          | Excalibrain         | Dataview             |
|----------------------------------|----------------------|----------------------|
| Vue graphique                    | ✅ Oui               | ❌ Non               |
| Vue en tableau                   | ❌ Non               | ✅ Oui               |
| Navigation visuelle              | ✅ Oui               | ❌ Non               |
| Filtres et requêtes logiques     | ❌ Non               | ✅ Oui               |
| Représentation d’un graphe       | ✅ Oui               | ❌ Non               |
| Diagnostic de structure          | ⚠️ Limité            | ✅ Très utile        |

---

## 💡 Recommandation
Utilise **Excalibrain pour explorer et concevoir**, et **Dataview pour documenter, synthétiser et analyser** ta carte de connaissances.

---

> Intégré au vault : `obsidian_ontologie_pedagogique/Comparatif Excalibrain vs Dataview.md`
