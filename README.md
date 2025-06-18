# 🌌 Kerbal Star Systems 2 \[v3.0.1]

**Kerbal Star Systems 2** (KSS2) is a massive interstellar expansion for *Kerbal Space Program*, pushing exploration far beyond Kerbol with rich, handcrafted star systems—some grounded in real astronomy, others purely fantastical.

As the spiritual successor to **KSS1** and **Galaxies Unbound**, KSS2 blends scientific plausibility with creative worldbuilding to deliver one of the most ambitious experiences ever made for KSP.

---

## 🚀 Key Features

* 🪐 **Realistic + Fictional Systems** – Explore exoplanets and imagined alien worlds
* 🌍 **Expanded Universe** – Discover systems light-years from Kerbol
* 🔁 **Career Integration** – Contracts and anomalies built for interstellar progression
* 🌌 **Visual Immersion** – Supports volumetric clouds, terrain shaders, wormhole effects

---

## 🖥️ System Requirements

* **KSP Version**: 1.12.x
* **RAM**: 16 GB minimum
* **GPU**: 1–2 GB VRAM recommended

---

## 📦 Installation Guide

### 1. Download KSS2

Remove any **older versions** of KSS2 or **Galaxies Unbound** before installing.

Install the following into your `GameData` folder:

* `KSS2_Core.2.0.zip`
* Your selected systems (e.g. `SystemAlphaCentauri`, `SystemLuhman16`, etc.)
* *(Optional)* `ContractPack.2.0.zip` for career contracts

KSS2 supports **Volumetric EVE** for enhanced visuals. *(Legacy EVE is not compatible.)*

Your KSS2 folder should look like this:

```
GameData/
└── KSS2/
    ├── Core
    ├── SystemAlphaCentauri
    ├── ContractPack   ← optional
    ├── KSS2Settings.cfg
    └── KSS2_License.md
```

---

### 2. Required Dependencies *(Install All)*

* 🔗 [Kopernicus](https://github.com/kopernicus/kopernicus/releases) *(v217+)*
* 🌌 [Kopernicus Expansion-er](https://github.com/VabienArt/KopernicusExpansion-Continueder/releases) *(for wormholes & effects)*
* 🛠️ [KSP Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes/releases) *(fixes 1.12 bugs)*
* 🧩 [NiakoUtils](https://github.com/pkmniako/Kopernicus_VertexMitchellNetravaliHeightMap/releases) *(bundled)*
* 🌀 [VertexHeightOblateAdvanced](https://github.com/jamespglaze/VertexHeightOblateAdvanced/releases/tag/1.1.4) *(bundled)*

---

### 3. Visual Enhancements *(Optional but Recommended)*

* ☁️ [Volumetric EVE](https://www.patreon.com/c/blackrack/posts) – Clouds, auroras, geysers *(paid mod)*
* 🌅 [Scatterer](https://github.com/LGhassen/Scatterer/releases) – Atmospheric scattering and ocean shaders
* 🪨 [Parallax Continued](https://github.com/Gameslinx/Parallax-Continued/releases/tag/1.0.1) – High-detail terrain and tessellation
* 🌌 [Singularity](https://github.com/LGhassen/Singularity) – Visuals for black holes and wormholes
* 🌠 [INSTANTIATOR](https://github.com/TheWhiteGuardian/Unofficial_INSTANTIATOR) – Deep space effects like pulsars
* 🔭 [Distant Object Enhancement](https://github.com/net-lisias-ksp/DistantObject) – Long-range object visibility *(not needed with Scatterer)*
* ✨ [PlanetShine](https://forum.kerbalspaceprogram.com/topic/173138) – Planetary glow and ambient lighting

---

## ⚙️ Configuration Overview

Edit `KSS2Settings.cfg` in the KSS2 folder to customize your gameplay:

#### 🔧 Core Options

* `KerbolRevamp = False` – *(upcoming)* revamp of stock system
* `HomeSwitch = True` – set **Alva** as homeworld instead of Kerbin
* `DistanceFactor = 1` – adjust system spacing (0.5, 1, 10, 100)
* `Rescale = 1` – scale all systems *(requires Sigma Dimensions)*

#### 🌍 Expansions

* `PandorExpansion = True` – adds the lush moon **Pandor** to Novin
* `HabitableProximaB = True` – makes **Proxima b** a viable home

#### 🛰️ Features

* `Wormholes = True` – enable interstellar travel
* `KerbolWormhole = True` – connects Kerbol ↔ Alpha Centauri
* `Anomalies = True` – unlock hidden deep space features *(requires Blueshift)*
* `Exotics = True` – enables rare, high-difficulty challenges
* `SunAsteroids / ExtraSolarAsteroids = True` – asteroid belts

#### 📡 CommNet

* `InterstellarCommNet = True` – adds long-range relay coverage

---

## 🔌 Compatibility

### ✅ Supported Mods

* [Sterling Systems](https://forum.kerbalspaceprogram.com/topic/219609)
* [Contract Configurator](https://github.com/KSP-RO/ContractConfigurator) *(v2.1.3+)*
* [Kerbalism](https://forum.kerbalspaceprogram.com/topic/190382)
* [Kerbal Health](https://forum.kerbalspaceprogram.com/topic/155313)
* [Community Resource Pack](https://github.com/UmbraSpaceIndustries/CommunityResourcePack)
* [Rational Resources](https://forum.kerbalspaceprogram.com/topic/184875)
* [Blueshift](https://github.com/Angel-125/Blueshift) *(enable anomalies in settings)*
* [WildBlueTools](https://github.com/Angel-125/WildBlueTools)
* **Space Dust Next** *(expanded resource support)*

### 🌍 Planet Pack Compatibility

* [Kcalbeloh System](https://github.com/jcyuan06/Kcalbeloh-System/releases/tag/v1.1.8)
* [Celestial Harmony](https://github.com/ProximaCentauri-star/Celestial-Harmony)
* **KSRSS** – only compatible in *scaled mode*
* [OPM (Outer Planets Mod)](https://github.com/Poodmund/Outer-Planets-Mod)

---

## 🚫 Not Compatible

* Principia
* Galaxies Unbound
* Older versions of KSS2
* KSRSS (*in full replacement mode*)
* Parallax 1 & 2
* Komplexity

Mods not listed are untested — install at your own risk.

---

## ⚠️ Known Issues

* **Legacy EVE is not supported**. Use **Volumetric EVE** only.
* **Maneuver Tool Bug** – KSP 1.12’s stock planner can cause scene/timewarp issues.
  → Use [KSP Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes)
  ![screenshot](https://raw.githubusercontent.com/KSPModdingLibs/KSPCommunityFixes/master/Screenshots/settings.gif)
* **Visual Tip** – Set *Texture Quality* to **Full** to avoid black planet bugs.

---

## 🎯 Career Integration

KSS2 features a **custom contract system** designed for Career Mode.
Unlock mid-to-late game contracts as your space program evolves — guiding you toward new systems, mysteries, and anomalies.

---

## 💬 Community & Support

* [🌐 Discord Server](https://discord.com/invite/8mKywDaujE) – Ask questions, get updates, share ideas
* [📺 YouTube Channel](https://www.youtube.com/channel/UCrEUo4-6hNuVxUPEKNv8EcA) – Previews, dev logs, and showcases

> 🛑 *KSP Forum support has been discontinued due to community conflicts and shifting moderation policies.*

---

## ❤️ Support KSS2 on Patreon

If you love the project and want to help it grow, consider becoming a supporter:
Your contributions help cover time, tools, and continued development.

[**🎁 Become a Patron**](https://www.patreon.com/c/StarCrusher96)

> 🔒 **Note:** KSS2 is **not being sold**. All support is voluntary. The mod remains free and public — Patreon simply helps keep the project alive.

---

## 🙏 Credits & Thanks

This project wouldn’t be what it is without the dedication of contributors and the support of the community. Special thanks to:

* **TheSpacePotato**
* **OoglakKerman**
* **JadeOfMaar**
* **Caden**
* **Chaotic Protocol**
* **CiaraRayneCloud**
* ...and **everyone who has supported KSS2 over the years** — whether by testing, feedback, encouragement, or just exploring the stars with us. 🖤

---

## 📜 License & Legal Notice

**Kerbal Star Systems 2** © 2025 by **StarCrusher96** is licensed under
[**CC BY-NC-ND 4.0**](https://creativecommons.org/licenses/by-nc-nd/4.0/).

This allows:

* ✅ Non-commercial redistribution
* ✅ Sharing with proper credit
* ❌ No modifications
* ❌ No asset reuse or redistribution

> ⚠️ **All textures** (unless stated otherwise) are **All Rights Reserved**. Reuse or redistribution is not allowed without written permission.
