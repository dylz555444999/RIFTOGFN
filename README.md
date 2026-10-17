<div align="center">

# 🎮 OG Rift

**Relive classic Fortnite, offline, with live events.**

![Mode](https://img.shields.io/badge/mode-singleplayer-blue)
![Runtime](https://img.shields.io/badge/.NET%20Core-3.1-512BD4)
![Versions](https://img.shields.io/badge/Fortnite-1.8%20→%2015.50-purple)
![Status](https://img.shields.io/badge/multiplayer-cancelled-red)

[Download](#-download) · [Quick Start](#-quick-start) · [Live Events](#-supported-live-events) · [Versions](#-supported-fortnite-versions) · [Commands](#-console-commands) · [FAQ](#-faq--troubleshooting)

</div>

---

> [!IMPORTANT]
> **Rift Multiplayer has been indefinitely cancelled.**
> This project is **Singleplayer only**.

## ✨ Features

- 🕹️ Play classic Fortnite builds from Chapter 1 Season 1 to Chapter 2 Season 5
- 🎆 Re-experience iconic live events
- 🚗 Spawn vehicles and items with console commands
- 💻 Fully offline

## 📥 Download

| What | Link |
| --- | --- |
| **Rift Singleplayer (latest)** | https://rebrand.ly/Rift-Latest |
| **.NET Core 3.1 (required)** | https://rebrand.ly/DotNet-Sdk-Download |
| **Fortnite Builds Archive** | https://github.com/llamaqwerty/fortnite-builds-archive |

## 🚀 Quick Start

1. Install **.NET Core 3.1** (link above).
2. Download and extract the latest **Rift Singleplayer** build.
3. Point Rift at your chosen Fortnite build from the [Builds Archive](https://github.com/llamaqwerty/fortnite-builds-archive).
4. Launch Rift and pick a supported version.
5. In game, press `~` or `F8` to open the console.

## 🌟 Supported Live Events

| Version | Event |
| :---: | --- |
| 4.5 | 🚀 Rocket Event |
| 5.41 | 🧊 Cube Lake |
| 6.21 | 🦋 Butterfly Event |
| 9.40 | ⚔️ Final Showdown |
| 10.40 / 10.40.1 | 🕳️ The End |
| 12.41 | 🎤 Travis Scott Presents: Astronomical |
| 12.61 | 🔧 The Device |
| 14.60 | 🌌 Galactus |

Start the current version's event from the console:

```
cheatscript StartEvent
```

> The **8.51 Unvaulting Event** is not supported.

## 📦 Supported Fortnite Versions

<details>
<summary><b>Chapter 1</b> (Seasons 1 – X)</summary>

| Season | Versions |
| --- | --- |
| C1 S1 | 1.8, 1.8.1, 1.8.2, 1.9, 1.9.1, 1.9.2, 1.10 |
| C1 S2 | 1.11, 2.1, 2.2, 2.3, 2.4, 2.4.2, 2.5, 2.5.1 |
| C1 S3 | 3.0, 3.1, 3.2, 3.3, 3.4, 3.5, 3.5.1, 3.6.0 |
| C1 S4 | 4.0, 4.1, 4.2, 4.3, 4.4, 4.4.1, 4.5 |
| C1 S5 | 5.0, 5.1, 5.2, 5.3, 5.4, 5.41 |
| C1 S6 | 6.0, 6.01, 6.10, 6.20, 6.21, 6.30, 6.31 |
| C1 S7 | 7.0, 7.10, 7.20, 7.30, 7.40, 7.41 |
| C1 S8 | 8.0, 8.1, 8.2, 8.3, 8.4, 8.5, 8.51* |
| C1 S9 | 9.0, 9.10, 9.20, 9.30, 9.40, 9.41 |
| C1 SX | 10.00, 10.10, 10.20, 10.30, 10.40, 10.40.1 |

\*Unvaulting Event is not supported.

</details>

<details>
<summary><b>Chapter 2</b> (Seasons 1 – 5)</summary>

| Season | Versions |
| --- | --- |
| C2 S1 | 11.00, 11.01, 11.10, 11.11, 11.20, 11.30, 11.31, 11.40, 11.41, 11.50, 11.51 |
| C2 S2 | 12.00, 12.10, 12.20, 12.30, 12.40, 12.41, 12.50, 12.60, 12.61 |
| C2 S3 | 13.00, 13.10, 13.20, 13.30, 13.40 |
| C2 S4 | 14.00, 14.10, 14.20, 14.30, 14.40, 14.50, 14.60 |
| C2 S5 | 15.00, 15.10, 15.20, 15.30, 15.40, 15.50 |

</details>

## ⌨️ Console Commands

Open the console with `~` (Tilde) or `F8`.

| Command | What it does |
| --- | --- |
| `cheatscript StartEvent` | Starts the current version's live event |
| `cheatscript SpawnVehicle <VehicleID>` | Spawns a vehicle |
| `cheatscript SpawnItem <ItemID>` | Spawns a pickup on the ground |
| `cheatscript GiveItem <ItemID>` | Gives the item straight to you |

### 🚗 Vehicle IDs

| Vehicle | ID |
| --- | --- |
| Mech | `TestMechVehicle` |
| ATK | `GolfCartVehicleSK` |
| Driftboard | `JackalVehicle_Athena` |
| Baller | `OctopusVehicle` |
| Quad Crasher | `AntelopeVehicle` |
| Plane | `FerretVehicle` |
| Cannon | `PushCannon` |
| Shopping Cart | `ShoppingCartVehicleSK` |
| Surfboard | `SurfboardVehicle_Athena` |

```
cheatscript SpawnVehicle GolfCartVehicleSK
```

### 🎒 Item IDs

Full list: https://pastebin.com/NQPcw6mj

```
cheatscript GiveItem <ItemID>
```

## ❓ FAQ / Troubleshooting

**Will multiplayer come back?**
No. Rift Multiplayer is indefinitely cancelled.

**The launcher won't start.**
Make sure **.NET Core 3.1** is installed (not just a newer .NET version).

**The console won't open.**
Try both `~` and `F8`.

**An event doesn't trigger.**
Check that your version is in the [live events table](#-supported-live-events) and that you ran `cheatscript StartEvent` in game.

**Found a bug?**
Open an [issue](../../issues) with your Fortnite version, what you did, and what happened.

## ⚖️ Disclaimer

OG Rift is a fan-made, non-commercial project and is **not affiliated with, endorsed by, or sponsored by Epic Games or Fortnite**. Fortnite and all related assets are trademarks and property of Epic Games, Inc.
