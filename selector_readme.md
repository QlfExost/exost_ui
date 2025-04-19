# 🧩 exost_ui - Selector

Ce composant UI permet d'afficher une **boîte de sélection** stylisée avec plusieurs boutons colorés.  
Il permet à un joueur de **choisir une option parmi plusieurs propositions**.  
Il fait partie de la ressource `exost_ui`.

---

## 🚀 Utilisation

### ▶️ Appel côté client Lua :

```lua
local index, label = exports['exost_ui']:Selector(
    "Titre de la sélection",
    "Quel est votre métier préféré ?",
    "Policier", "blue",
    "Médecin", "red",
    "Mécano", "orange"
)

if index then
    print("✅ Choix :", label, "(index :", index, ")")
else
    print("❌ Aucun choix effectué")
end
