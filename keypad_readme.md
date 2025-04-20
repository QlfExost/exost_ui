# 🔢 exost_ui - Clavier Numérique (Keypad)

Ce composant UI affiche un clavier numérique sécurisé (type code PIN) permettant à l'utilisateur d'entrer un code. L'interface est interactive, stylisée et compatible clavier/souris, avec animation et sons de succès/échec.

---

## 🚀 Utilisation

### ▶️ Appel côté client Lua :

```lua
local result = exports['exost_ui']:Keypad("1234") -- code attendu

if result then
    print("✅ Code correct")
else
    print("❌ Code incorrect")
end
```
---

[Aperçu](img/img_keypad.png)
