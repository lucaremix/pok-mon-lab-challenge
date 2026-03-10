<p align="center">
  <img src="assets/logo.png" width="900" />
</p>

<h1 align="center">Pokémon Lab Challenge</h1>

<p align="center">
  <a href="https://github.com/lucaremix/pokemon-lab-challenge/releases/latest">
    <img src="https://img.shields.io/github/v/release/lucaremix/pokemon-lab-challenge?style=for-the-badge" />
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-All%20Rights%20Reserved-red?style=for-the-badge" />
  </a>
</p>

<p align="center">
  A custom Pokémon challenge where you don't catch — you <strong>synthesize</strong>.<br/>
  Beat events, collect DNA, and engineer your team in the lab.
</p>

---

## 🚀 Installation

Download and run the installer from the [latest release](https://github.com/lucaremix/pokemon-lab-challenge/releases/latest):

```
PokemonLabLauncher_Setup_v1.0.0.exe
```

The installer includes the launcher and lets you choose which games to install.

> **Requires:** WebView2 Runtime — pre-installed on Windows 11, [free download](https://developer.microsoft.com/microsoft-edge/webview2/) for Windows 10.

---

## 🎮 Games

| Game | Base ROM |
|------|----------|
| **Sacred Gold & Storm Silver** | Drayano's enhanced remake of HeartGold / SoulSilver |
| **Blaze Black & Volt White** | Drayano's enhanced remake of Black / White |

Each game runs its own full lab system — events, crafting, and Pokémon pool are separate.

---

## 🧬 How It Works

```
Beat an event → Claim DNA rewards → Craft moves & Pokémon → Export .pk4/.pk5 → Import via PKHeX → Play
```

### Lab Machines

- **DNA Machine** — Filter the Pokémon pool by type, BST, and IVs. Generate a random match, then configure nature, ability genome, and moves before downloading the file.
- **Move Machine** — Combine Damage, Class, and Type Cores to synthesize custom moves.
- **Melting Machine** — Disassemble a Pokémon to recover 3 random materials (50% chance to also recover the DNA Ball).
- **Bag** — Full inventory of all your DNA, Cores, Genomes, moves, and Pokémon.

---

## 🧪 Crafting Materials

| Item | Used for |
|------|----------|
| **DNA Ball** | One per Pokémon synthesis |
| **Type DNA** | Filter pool by typing |
| **BST / IV DNA** | Minimum stat requirements |
| **Nature DNA** | Lock a specific nature |
| **Shiny / Legendary DNA** | Special pool access |
| **Damage / Class / Type Cores** | Move crafting |
| **Genomes** | Ability pool selection |

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Backend | ASP.NET Core (.NET 10), C# |
| Frontend | Vanilla HTML / CSS / JS |
| Pokémon files | [PKHeX.Core](https://github.com/kwsch/PKHeX) |
| Desktop launcher | WinForms + WebView2 |

---

## 📝 Credits

- ROMs: **Sacred Gold, Storm Silver, Blaze Black, Volt White** by [Drayano](https://x.com/Drayano60)
- Pokémon file format: [PKHeX](https://github.com/kwsch/PKHeX) by kwsch
- Pokémon © 1995–2026 Nintendo / Game Freak
