# 🎂 Matteo Birthday App

Geburtstags-App für Matteo (wird 13!) mit:
- 🏃 **Matteo Run** – Jump'n'Run Spiel im Mario-Style
- 🔫 **Nerf Jagd** – Moorhuhn-Style Zielschießen
- 🧠 **Mega-Quiz** – Mathe, Wissen & Matteo-Insider
- 🏆 **13 Achievements** mit Aura-System
- 🎁 **Überraschungs-Gutschein** (VR Gaming in Berlin)

## Deployment mit GitHub Pages

```bash
# Repo erstellen und pushen
gh repo create matteo-birthday --public --source=. --remote=origin
git add .
git commit -m "Happy Birthday Matteo!"
git push -u origin main

# GitHub Pages aktivieren
gh api repos/{owner}/{repo}/pages -X POST -f source.branch=main -f source.path=/
```

Dann live unter: `https://DEIN-USERNAME.github.io/matteo-birthday`

## Dateien

- `index.html` – Die komplette App (alles in einer Datei)
- `manifest.json` – PWA-Manifest für Homescreen-Installation
- `icon-192.png` – App-Icon 192x192
- `icon-512.png` – App-Icon 512x512

## Für Matteo

Schick ihm den Link mit dieser Nachricht:

> Hey Matteo, Happy Birthday! 🎂
> Öffne den Link und speicher dir die App:
> 👉 [DEIN LINK]
> iPhone: ⬆️ Teilen → "Zum Home-Bildschirm"
> Android: ⋮ Menü → "Zum Startbildschirm hinzufügen"
