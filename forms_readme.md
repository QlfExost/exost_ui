# 📦 Exost UI – Formulaires NUI pour FiveM

Une interface NUI verticale et élégante pour recueillir **plusieurs champs de texte personnalisés** en jeu. Parfait pour des fiches, des rapports, des créations de personnage, etc.

---

## ✨ Caractéristiques

- Interface noire, centrée et responsive
- Scroll vertical si trop de champs
- Design full Poppins avec un style GTA-like
- Titre et description en haut
- Boutons "Confirmer" (✅) et "Annuler" (❌) stylisés
- Fermer avec **Échap** à tout moment
- Retour d’un tableau contenant toutes les valeurs via :
  `local result = exports['exost_ui']:Forms(...)`

---

## 📥 Installation

1. Place la ressource dans ton dossier `resources/`
2. Ajoute `ensure exost_ui` dans ton `server.cfg`
3. Appelle l’UI depuis ton script via l’export ci-dessous

---

## ⚙️ Utilisation

```lua
local result = exports['exost_ui']:Forms(
  "Prénom", "prenom",
  "Nom de famille", "nom",
  "Âge", "age"
)

Format : "Texte affichée", "valeur récupérée dans le result."

```

---

Puis dans votre script:
```lua
local prenom = result.prenom
local nom = result.nom
local age = result.age
```

[Aperçu](img/img_forms.png)
