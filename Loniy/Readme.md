# 🌟 DexHub by Loniy

A powerful script hub for Roblox — currently supporting **Rivals** with advanced features.

---

## 🎮 Supported Games & Features

| Game   | Features                                  |
|--------|-------------------------------------------|
| Rivals | Aimbot, Skin Changer, ESP, More coming... |

---

## 🛠 Version

**V1.4** – *Updated: 2025/07/18*

---

## 📜 Script (Copy & Paste)

```lua
getgenv().Key = "" -- Enter your Key here

getgenv().Settings = {
    Theme = "Default",    -- Rayfield theme (Default, Amber Glow, Amethyst, Bloom, Dark Blue Green, Light,  Ocean, Serenity,)
    SaveConfig = true,    -- Save your configuration
    LoadConfig = true     -- Auto-load saved configuration
}

loadstring(game:HttpGet("https://raw.github.com/RequideSync/Project/main/Loniy/Rivals.lua"))()
