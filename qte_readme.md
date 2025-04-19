# 🎯 exost_ui - QTE (Quick Time Event)

Ce composant UI permet d’afficher un mini-jeu de type **QTE inspiré de Dead by Daylight** dans FiveM.  
Il affiche une **zone verte** à atteindre avec une **aiguille qui tourne sur le bord du cercle**, et attend que le joueur appuie sur une touche précise au bon moment.  
Il fait partie de la ressource `exost_ui`.

---

## 🚀 Utilisation

### ▶️ Appel côté client Lua :

```lua
local success, time = exports['exost_ui']:Qte("E", 3000, 15, 270)

if success then
    print("✅ Réussi en", time, "ms")
else
    print("❌ Échec après", time, "ms")
end
