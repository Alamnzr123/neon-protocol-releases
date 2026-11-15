# Neon Protocol 2088 — Cyber-Noir Detective Visual Novel

**Neon Protocol 2088** is a cyberpunk-noir detective visual novel developed by **DIGASS Games**, set in the year 2088 within the metropolis of Neo-Jakarta. Players take on the role of **Silas Rayne**—a private investigator and former officer of the KPD’s Cybernetics Division—tasked with investigating the murder of Director Tanaka on the 88th floor of the SynTek Tower, while uncovering a conspiracy involving the quantum AI known as **Erebus-09**.

---

# Neon Protocol 2088 - Releases

Windows installer (x64, NSIS).
Silent install: Neon-Protocol-2088-Setup-X.Y.Z.exe /S

## Installer exit codes

| Code | Meaning |
|------|---------|
| 0 | Installation successful |
| 1 | Installation cancelled by the user |
| other (non-zero) | Installation aborted because of an installer error (for example, not enough disk space or files in use) |

No reboot is required. The installer does not download additional files.

---

## Official Links

- **Upgrade / Full Game (Itch.io)**: [https://digassmyid.itch.io/neon-protocol-2088](https://digassmyid.itch.io/neon-protocol-2088)
- **Support & Patreon Membership**: [https://www.patreon.com/cw/digass](https://www.patreon.com/cw/digass)

---

## Key Features

### 1. Complete 20-Chapter Storyline with 4 Branching Endings
- **Chapters 1–20 (Acts I–IV)** cover the entire investigative arc, spanning from the crime scene in the 88th-floor penthouse to the climactic confrontation against the **Erebus-09** system. - **4 Branching Endings**:
- `TRUE_ROMANCE_NYX` (A romantic bond with **Nyx Vespera**)
- `ALLIANCE_VANCE` (A tactical alliance with **Vance Kross**)
- `SHADOW_SYNDICATE` (Taking control of the underground network)
- `GHOST_IN_RAIN` (A classic *noir* solo detective route)
- **Multi-Language (4 Languages)**: Indonesian (`id`), English (`en`), Simplified Chinese (`zh`), and Japanese (`ja`), with full localization support for the UI, characters, hints, endings, and all dialogue across Chapters 1–20.

### 2. Free vs. Paid Content Breakdown (Chapters 1–20)
Both the **Collectible CG Gallery (24 items)** and the **Weekly Cases (20 episodes, `CHAPTER 01`–`CHAPTER 20`)** are categorized by access level:

| Chapter Range | Access Status | Tier Description |
| :--- | :--- | :--- |
| **Chapters 1 – 3** (+ Bonus Cover, Banner & City Concept) | **Free (`FREE`)** | Accessible directly in your browser |
| **Chapters 4 – 10** (+ Bonus Vance Showdown) | **Paid · Tier 1 ($3)** | Street Operative (`STREET_OPERATIVE`) |
| **Chapters 11 – 16** | **Paid · Tier 2 ($7)** | Shadow Syndicate (`SHADOW_SYNDICATE`) |
| **Chapters 17 – 20** (Act IV Finale & VIP CGs) | **Paid · VIP ($15)** | Megacorp Architect (`MEGACORP_ARCHITECT`) / Full Edition on Itch.io | ### 3. Visual Novel Gameplay Mechanics & Atmosphere
- **Dynamic Weather System & Atmospheric Tints**: Backgrounds shift dynamically between *Acid Rain*, *Neon Fog*, and *Cyber ​​Storm* using CSS animations and color overlays (blue/purple/electric tints).
- **Detective Intuition Meter**: An overlay indicator on the HUD that changes color and status based on the scene's atmosphere and the player's cumulative choices.
- **Choice Staggered Animation**: A staggered entrance animation for dialogue option buttons.
- **Skip-to-Checkpoint & Auto-Play**: Quick navigation to the next choice point or chapter transition, along with an *Auto-Play* feature.
- **Save/Load (3 Dedicated Slots) + Quick Save**: Local save management featuring chapter summaries and progress tracking for clues.
- **Investigation Board, Codex & Achievements**: An interactive evidence board, a lore encyclopedia for Neo-Jakarta (Codex), and 12 unlockable achievements.

### 4. Audio System & AI Concept Art
- **Procedural Noir BGM & Scene-Specific SFX**: Adaptive background music based on the scene mode (`rain`, `mystery`, `romance`, `tension`, `action`), with automated sound effect triggers linked to scene keywords and character emotional expressions.
- **Character Vocal Bites & Synthesized Voice**: Procedural character vocal effects and a *Text-to-Speech* feature powered by the Web Speech API (can be toggled via **Audio Settings**).
- **Generate Concept Art (`/api/concept-art`)**: On-demand generation of concept illustrations for the current scene location, utilizing `@google/genai` (`gemini-3.1-flash-lite-image`) via an Express backend endpoint.

© **DIGASS Games** — *Neon Protocol 2088*
