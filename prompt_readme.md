
# 📦 exost_ui - Prompt de Confirmation

Ce composant UI permet d'afficher une boîte de confirmation stylisée dans FiveM avec un design propre, réactif et animé. Il fait partie de la ressource `exost_ui`.

---

## 🚀 Utilisation

### ▶️ Appel côté client Lua :

```lua
local result = exports['exost_ui']:Prompt("Titre de confirmation", "Souhaitez-vous vraiment effectuer cette action ?")

if result then
    print("✅ Utilisateur a confirmé")
else
    print("❌ Utilisateur a annulé")
end

---

[Aperçu](img/img_prompt.png)
