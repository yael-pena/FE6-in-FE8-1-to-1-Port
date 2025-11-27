# Fire Emblem: The Binding Blade - 1:1 Port to the FE8 Engine [Complete]
**Vanilla FE6 ported to the FE8 engine.**

<img width="480" height="360" alt="image" src="https://github.com/user-attachments/assets/d096e44f-2ea4-4ab6-af96-2ffd5554969c" />

![1f8b2fe20a8e35fdcaa682b8bdec927e123495db](https://github.com/user-attachments/assets/6aa50e6d-edb2-4942-ba23-ee4aecc4340e) ![d73a67f726b0018ce58d827c58f205a9d78f5dba](https://github.com/user-attachments/assets/ece8a973-c73b-4810-b456-e586fbe86506)

---------------------------------------------------------------------------------------------
### Fire Emblem: The Binding Blade — 1:1 FE8 Engine Port (Demo Showcase)

[![Video Demo](https://github.com/user-attachments/assets/8042de68-9be6-4c34-929d-6fd12c9a4f27)](https://youtu.be/ALplmdOk3sk)

---------------------------------------------------------------------------------------------
A faithful, technical, ground-up recreation of Fire Emblem: The Binding Blade inside the Fire Emblem 8 (Sacred Stones) engine — rebuilt event by event, map by map, mechanic by mechanic.

This project preserves the original FE6 experience, while taking advantage of FE8’s more modern engine, tools, and hacking ecosystem. It also serves as a fully-featured base for ROM hackers who want to build FE6 projects using FE8’s improved functionality.

Original FEUniverse Page: https://feuniverse.us/t/fire-emblem-the-binding-blade-1-1-port-to-the-fe8-engine-complete/27628

## Table of Contents
- [Download](#download)
- [About the Project](#about-the-project)
- [Features](#features)
- [Project Goals & Philosophy](#project-goals--philosophy)
- [Flags](#flags)
- [Credits](#credits)

## Download
Latest Version: v1.9 (3/11/2025)
→ Apply the UPS patch to a clean FE8 (U) ROM.

Download Patch: https://www.dropbox.com/scl/fo/ifc1s5lojaxgvqzq7pwxu/AFaC9BEno-IbyEXAd8ehkk0?rlkey=ti7yrw77cvkup1hoy1tocagrr&st=ss1i0q07&dl=0

### v1.9 Patch Notes
- Fixed Ch20B seize issue
- Fixed Ch23 seize issue
- Fixed Lilina → Gonzalez talk on Route B
<details>
<summary><strong> Previous Patch Notes </strong></summary>
  
v1.8 Patch Notes
- Secondary AI 06 and 07 fixed
  
v1.7 Patch Notes
- All promo items extended to 63
<img width="690" height="404" alt="image" src="https://github.com/user-attachments/assets/5aa7fdbd-0b60-4ae0-b9cc-648c9ef9705b" />


v1.6 Patch Notes
- Updated Character Titles to their latest localizations

  Bors: Iron Knight → Ostia’s Bastion

  Ogier: Little Hero → Ostia’s New Blade

  Elffin: Truth Seeker → Truth Beholden

  Zeiss: Ebony Rider → Ebon Bolt

v1.5 Patch Notes
- Merlinus death + persistence fixes

v1.4 Patch Notes
- Fixed various Defeat Boss Flag conditional statements.

- Fixed missing Chapter 13 event.

- Fixed Chapter 6 reinforcements.

- Changed Chapter 14x trap arrangements.

- Fixed Thea maxed out Mag stat.

v1.3 Patch Notes
- Orion’s Bolt fixed
- Casual Mode deployment bug fixed
- Crit bonuses, animations, and stat issues corrected

v1.2 Patch Notes
- Temporary Master Seal workaround
- Title Screen update
- Brunnya stat bug fixed

v1.1 Patch Notes
- Chapter 12 prep loop fixed
- Roy overworld movement fix
</details>

## About the Project
This is a **true 1:1 port** of Fire Emblem 6 recreated inside FE8.
When I say 1:1, I mean:
- Every chapter event re-scripted by hand
- Every enemy placement matched
- Every stat, conversation, and world map sequence ported
- Side-by-side testing against vanilla FE6
- Modern FE8 conveniences added only where necessary

Some visual and mechanical elements were updated or improved, such as portraits, palettes, blinking frames, and modernized translations.

This project was also built for other ROM hackers — with a focus on stability, consistency, and ROM space preservation.

## Features

### Optional Prologue
- A brand-new prologue inspired by FE6's original tutorial map

![bb234e4037be85a00e31fd9c0d1c2ff1f3c5101d](https://github.com/user-attachments/assets/265bddfb-af55-4532-a314-e49a6e0a1805)

### Casual Mode & Fixed Growths
- Modern QoL options built directly into the engine.

![8fd305c5ac6341564f410b425060466e2f354f91](https://github.com/user-attachments/assets/28920a91-5378-4bc5-ad0b-22337e22e8d2)

### World Map Shops & Armories
- Visit shops that match FE6’s original chapter inventory.

![9e905d7d13252805cde16a99b3ea640119fbcd63](https://github.com/user-attachments/assets/16b0e5ce-76ff-4d56-8833-a27dd586ec5e)

### Modern Route-Split Choice
- Choose Ilia or Sacae via menu after 16/16x, instead of EXP tracking.

![5a56334bbecd159777e055ea283b7c6c3f595489](https://github.com/user-attachments/assets/2b6cc936-483f-4d2e-bf56-52610be162a9)

### Updated Translation
Based on the latest community translation + localization fixes:
- Jutes → Juteaux
- The Blizzard Spear → The Freezing Lance
- The Tempest Bow → The Bow of Swift Wind
- …and many more
### Improved Visuals
- Blinking portraits
- Cleaner palettes
- Updated battle frames
- Select class animations updated or fixed

## Installation
1. Obtain a clean Fire Emblem 8 (USA) ROM.
2. Download the UPS patch from the link above.
3. Use NUPS or Multipatch to apply the patch.
4. Play on emulator or real hardware.

## Project Goals & Philosophy

This project was built with three goals:

### 1. Accuracy
A literal translation of FE6 into FE8, sticking as close to the source as possible.
### 2. Stability
Minimize unnecessary engine changes and preserve ROM space (final ROM: 20.6MB, leaving ~10MB free).
### 3. Usability
Give ROM hackers a clean base to build on, complete with modern FE8 features.

## Known Limitations / Cuts
- Gaiden chapters + Chapters 23–25 do not have world map nodes
- No Tower of Valni or Lagdou Ruins
- No skirmishes
- Some traps in 16x are static
- Spirit Dust added due to Str/Mag split
- Some high-budget FE6 animations replaced with FE8 equivalents (Aureola → Ivaldi, etc.)

## Flags

- 78 → Prologue completed 
- 79 → Lilina dead
- 7A → Route B taken
- 7B → Sacae chosen
- 7C → Sue dead
- 7D → Sin dead
- 7E → Dayan dead
- 83 → Galle dead
- 86 → Fae dead
- 8B–8D → Cath talk counters
- 8E → Cath dead
- 8F → Elffin dead
- 90 → Perceval recruited/dead
- 95 → Idunn hit by Binding Blade
- 99 → Good ending achieved
- A0–A3 → Zealot/Juno/Melady/Zeiss dead
- AC → Perceval crest check
- B2 → Douglas dead

## Credits
- FE6 [T2] Roy Master Lord — UltraFenix
- Roy Reskin (Echoes Style) — Jeorge_Reds & UltraFenix
- Elffin Reskin — UltraFenix
- Larum — Redbean
- Sue — Redbean
- Zephiel — UltraFenix
- Roy portrait — UltraFenix

…and all other contributors listed in original post
