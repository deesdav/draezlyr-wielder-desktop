# Draezlyr Wielder Desktop

**Draezlyr Wielder Desktop** je multiplatformní desktopová aplikace postavená na Electronu, Vite a Reactu. Projekt je ve vývoji a bude postupně doplňován o funkcionalitu.

## 🔧 Použité technologie

- [Electron](https://www.electronjs.org/) – pro běh desktopové aplikace
- [Vite](https://vitejs.dev/) – moderní buildovací nástroj
- [React](https://react.dev/) – komponentní JavaScriptová knihovna pro frontend
- [Tailwind CSS](https://tailwindcss.com/) – utility-first CSS framework pro styling

## 🚀 Spuštění projektu

1. Naklonuj repozitář:

   ```bash
   git clone https://github.com/deesdav/draezlyr-wielder-desktop.git
   cd draezlyr-wielder-desktop

2. Nainstaluj závislosti:

    ```bash
    npm install

3. Spusť aplikaci:

    ```bash
    npm run start

## 🖥️ Vytvoření desktopové aplikace (instalační balíček)

Pokud chceš vytvořit instalátor pro Windows/Linux/macOS, spusť následující příkaz:
    ```bash
    npm run make

Výsledný instalační soubor se objeví ve složce out/. Ten lze poté spustit a nainstalovat aplikaci na plochu jako klasický desktopový program.

## 📁 Struktura projektu

```bash
.
├── src/            # Frontend - React komponenty
├── electron/       # Main proces - Electron backend
├── public/         # Statické soubory
├── package.json    # Základní konfigurace projektu a skriptů
└── vite.config.ts  # Konfigurace pro Vite
