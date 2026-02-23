# Wizard Quest

Wizard Quest is a **3D Unreal Engine 5.4** game project built as a **Blueprint-only baseline** for developing a more complex experience. The goal is to provide a clean starting point with a lightweight foundation that’s easy to extend with new mechanics, content, and polish.

## Built With

- **Unreal Engine 5.4**
- **Blueprints only** (no C++)

## What’s Included (Current Baseline)

- A playable 3D project foundation in UE 5.4
- A **spell casting system** where spells vary by:
  - **Weapon type**
  - **How long the fire button is held** (charge time)
- Spells have different **visuals** and **projectile speed** based on the above

## What’s Not Included (Yet)

This repo is intentionally minimal and does **not** currently include:

- Dungeons / structured level progression
- Sound effects / audio pass
- Cooldowns (spell timing is driven by input/charge rather than cooldown timers)

## Getting Started

### Prerequisites

- **Unreal Engine 5.4** installed (via Epic Games Launcher)
- A machine capable of running Unreal Engine projects (GPU recommended)

### Open the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/kostenarov/Wizard-Quest.git
   ```
2. Open the `.uproject` file in Unreal Engine 5.4.
3. Let Unreal update/convert files if prompted.

### Play

- Open the project in the Unreal Editor and click **Play**.

## Project Notes (Git + Unreal)

Unreal projects generate local build/editor artifacts that should not be committed. Ensure typical generated folders are ignored (commonly `Binaries/`, `Intermediate/`, `Saved/`, `DerivedDataCache/`).

If you add lots of assets (textures, audio, large meshes), consider **Git LFS** to avoid bloating the repo history.

## Roadmap Ideas

Since this is meant to be a baseline, typical next steps might include:

- [ ] More weapon types / spell variants (data-driven tuning)
- [ ] Enemy AI and combat encounters
- [ ] UI (HUD, menus, settings)
- [ ] Audio (SFX, music, mixing)
- [ ] Save/load and progression
- [ ] Better level structure and content pipeline

## License

MIT License. See `LICENSE`.