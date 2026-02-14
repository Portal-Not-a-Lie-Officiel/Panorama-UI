# 💠 P2CE UI Redesign - [Nom de Ton Mod]

Ce dossier contient l'interface utilisateur (UI) personnalisée pour **Portal: Not a Lie**, basée sur le travail original de **ddddpplo**. L'interface utilise le framework **Panorama** de Valve pour offrir une expérience moderne et fluide dans le style "New Aperture".

---

## 🚀 Structure du Projet

* **`layout/`** : Contient les fichiers XML qui définissent la structure visuelle des menus.
* **`styles/`** : Fichiers CSS (PSS) pour les couleurs, les animations et le design global.
* **`scripts/`** : Logique JavaScript pour les interactions et la gestion des chapitres.
* **`images/`** : Icônes, fonds d'écran et vignettes des chapitres.

---

## 📖 Configuration des Chapitres

Pour modifier les titres ou les maps, tout se passe dans le fichier de script principal. 

> [!IMPORTANT]
> **Chemin du fichier :** `D:\SteamLibrary\steamapps\common\Portal 2 Community Edition\notalie\panorama\scripts\pages\main-menu\chapter-select.ts` (ou .json selon ta version).

### Liste des Chapitres Actuels :

| Chapitre | Titre | Map (BSP) | Ambiance |
| :--- | :--- | :--- | :--- |
| **01** | **Initialisation Stérile** | `sp_a1_intro` | Réveil, style New Aperture blanc. |
| **02** | **Vecteurs de Mobilité** | `sp_a1_course` | Introduction aux mécaniques. |
| **03** | **Réconfiguration Dynamique** | `sp_a1_factory` | Usine en mouvement. |

---

## 🛠️ Instructions de Modification

### Modifier un Titre
1. Ouvre le script de gestion des chapitres.
2. Localise la variable `chapters`.
3. Change la valeur de `title: "Ancien Nom"` par `"Nouveau Nom"`.

### Ajouter une Image de Fond
Les images doivent être au format `.png` ou `.svg` et placées dans :
`panorama/images/chapters/`

---

## 📜 Crédits
* **Base UI** : [ddddpplo](https://github.com/ddddpplo/p2ce-ui-redesign)
* **Modding & Design** : KITSUNe
* **Moteur** : Portal 2: Community Edition (P2CE)

---
  *Fait avec amour pour la communauté Portal.*
