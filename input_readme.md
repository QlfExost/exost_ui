# 📦 Exost UI – Input NUI pour FiveM

Une interface NUI légère, esthétique et responsive pour recueillir des **informations textuelles ou numériques** en jeu via un champ d'input personnalisé.

---

## ✨ Caractéristiques

- Interface responsive, clean, centrée
- Support des tailles d’input : `small`, `mid`, `large`
- Support du type `numbers` (chiffres uniquement)
- Personnalisable : titre, description, type, limite de caractères
- Validation par **Entrée** / Annulation par **Échap**
- Retour direct via `local result = exports['exost_ui']:Input(...)`
- Totalement compatible clavier/souris

---

## 📥 Installation

1. Place la ressource dans ton dossier `resources/`
2. Ajoute `ensure exost_ui` dans ton `server.cfg`
3. Assure-toi que ta ressource appelle bien cette UI via l’export ci-dessous

---

## ⚙️ Utilisation

```lua
local result = exports['exost_ui']:Input(
  "Nom",               -- 🏷️ Titre affiché
  "Entrez votre nom",  -- 📄 Description affichée
  "mid",               -- 🔠 Type d’input : small | mid | large | numbers
  50                   -- 🔢 Nombre de caractères max
)
```
---

Après, vous pourrez utiliser la variable définie dans votre script.

---

[Aperçu](img/img_input.png)
