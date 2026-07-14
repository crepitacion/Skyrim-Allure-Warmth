# Skyrim Allure & Warmth (SNW) - Modlist v1.4.1

> *"An elegant, provocative, and cozy Skyrim experience."*

---

## 📖 Description

**Skyrim Allure & Warmth (SNW)** is a carefully curated modlist for **Skyrim Special Edition (1.6.1170)** that balances three fundamental pillars:

- **Allure:** A stunning visual aesthetic with detailed bodies (CBBE 3BA / HIMBO), advanced physics (CBPC / Faster HDT-SMP), suggestive armors, and atmospheric lighting that enhances every corner of Skyrim.

- **Warmth:** A cozy and immersive gameplay experience, with followers that have personality (INIGO, Nether's Follower Framework), expanded dialogue (RDO, More to Say), and a world that feels alive and responsive.

- **Solid Gameplay:** Combat (Valravn), magic (Mysticism), loot (Summermyst), and progression (The Art of Smithing) overhauls that refresh the experience without straying from Skyrim's essence.

**This is not an explicit NSFW list.** SNW is designed for players seeking a **"sexy and provocative"** adventure in terms of aesthetics and armors, but without explicit pornographic content.

---

## ✨ Key Features

| Category | Featured Mods |
|-----------|-----------------|
| **Core & Frameworks** | SKSE64, Address Library, SPID, JContainers, Engine Fixes, Community Shaders, Papyrus Extender |
| **UI & Controls** | SkyUI, TrueHUD, True Directional Movement, SmoothCam, iWant Widgets |
| **Graphics & Bodies** | CBBE 3BA, HIMBO, CBPC, Faster HDT-SMP, BnP Skins, SMIM, DynDOLOD |
| **Lighting & Ambience** | Lux, Lux VIA, Azurite Mists, Enhanced Landscapes, Enhanced Vanilla Trees |
| **Gameplay & Overhauls** | Mysticism, Summermyst, Valravn, Lawless, Gourmet, The Art of Smithing |
| **Content & Quests** | Beyond Skyrim - Bruma, Wyrmstooth, The Forgotten City |
| **Followers & Dialogue** | INIGO, Nether's Follower Framework, RDO, More to Say |
| **Animations** | Open Animation Replacer, Pandora Behaviour Engine, Animation Motion Revolution |
| **Visual Customization**| RaceMenu, OBody NG, KS Hairdos, Community Overlays, Wet Function Redux |

---

## ⚙️ Root Builder Management

This list uses **[Root Builder](https://www.nexusmods.com/skyrimspecialedition/mods/31720)** (v2.3.0+) to manage Skyrim's root folder files (SKSE64, Engine Fixes, etc.).

### Why Root Builder?
- Keeps your Skyrim root folder clean.
- Allows managing SKSE64, Engine Fixes, and other `.dll` files directly from MO2.
- Facilitates creating multiple profiles with different configurations.

### Setup
1. Install Root Builder from Nexus Mods.
2. Activate it in MO2: `Plugins → RootBuilder → Enabled`.
3. Install mods containing root files (SKSE64, Engine Fixes, etc.) normally in MO2.
4. Root Builder will automatically move them to the root folder when you launch the game.

### Mods Requiring Root Builder in this List
- Skyrim Script Extender (SKSE64)
- Engine Fixes
- SSE Display Tweaks
- (Any other mod that installs `.dll` or `.exe` files in the root folder)

---

## 💻 Performance & System Requirements

### Recommended Hardware

| Component | Minimum (1080p) | Recommended (1440p) |
|-----------|-----------------|----------------------|
| **CPU** | Intel i5-8400 / AMD R5 2600 | Intel i7-10700 / AMD R7 3700X |
| **GPU** | GTX 1660 Super / RX 580 (6GB) | RTX 3060 / RX 6700 XT (8GB+) |
| **RAM** | 16 GB | 32 GB |
| **Storage** | SSD (60 GB) | SSD NVMe (70 GB) |
| **OS** | Windows 10/11 | Windows 11 |

### In-Game Performance
- **1080p (FHD):** 45-60 FPS in most areas, minimum 32 FPS in demanding scenes.
- **1440p (QHD):** Stable performance with 2K textures and medium DynDOLOD settings.
- **Configuration:** The list uses Community Shaders (no ENB) and Lux for lighting, which improves performance compared to traditional ENBs.

### Performance Tuning
- Use 2K textures instead of 4K (the list uses 2K by default).
- Reduce DynDOLOD resolution to "Medium" or "Low".
- Disable optional particle or mist mods (Azurite Mists, etc.).

---

## 📋 Requirements

### Mandatory
- **Game:** Skyrim Special Edition (v1.6.1170) with all Creations and DLCs.
- **Mod Manager:** Mod Organizer 2 (v2.5.0+) with Root Builder (v2.3.0+).
- **Tools:** SKSE64 (v2.2.6), BodySlide, DynDOLOD, xLODGen, Pandora Behaviour Engine.
- **Storage:** ~60 GB of free space (including DynDOLOD and xLODGen outputs).

### Operating System
- Windows 10/11 (64-bit) only.

---

## 📦 Compatible Versions

| Component | Version |
|-----------|---------|
| **Skyrim SE** | 1.6.1170.0 (AE) |
| **SKSE64** | 2.2.6 |
| **Root Builder** | 2.3.0+ |
| **MO2** | 2.5.0+ |
| **BodySlide** | 5.6.0+ |
| **DynDOLOD** | 3.0.0+ |
| **xLODGen** | 96+ |

---

## 🔧 Installation

### 1. Game Preparation
```bash
# Clean your Skyrim installation (recommended)
# Ensure you have version 1.6.1170 with all Creations
