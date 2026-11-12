# Heavenly Designs

A visuals, performance and combat plug-in for **LET IT DIE**, built on [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000). Its options are under **Options, then Mod Drive 9000, then Heavenly Designs**. It works in the base game and in POSTMORTEM.

## Features

### Quality pack
Applied to your game's settings files by the installer (the originals are backed up):
- texture pool 1024 MB;
- anisotropic filtering on characters and weapons;
- 2048 shadows;
- a high-precision lighting buffer (no banding in dark scenes).

### Faster loading
- A map load waits at most **5 s** for textures instead of 20 s.
- **Faster loading:** a frame cap during loads, so the loading work gets the time instead of drawing.
- **Remember missing localization files:** the game stops looking for the same missing files on every load.
- **Skip package re-verification:** level packages are no longer read twice.
- **Quick server replies:** menus that talk to the game's offline server open faster.

### Skips
- **Skip ride cinematics:** the elevator and escalator rides (not the stepping in and out).
- **Skip transition summaries:** the summary screen when you take an escalator continues by itself.

### Loot
- **Instant drops:** a kill drops its reward as the enemy dies, not two seconds later.
- **Reward pickup:** dropped kill coins and SPIRIT fly to you instead of scattering.

### Combat
Each is its own switch:
- **Improved targeting:** the lock-on camera follows the target, and a flick of the right stick (or a mouse swipe) moves the lock to the next enemy. A lock is dropped when the enemy stays behind a wall, and mushroom beasts are not picked.
- **Improved defence:** a dodge through an attack, or just out of its reach, is a perfect dodge. Attack right after one, or after a Perfect Guard, to counter.
- **Posture break:** press guard just before a hit to deflect it. Deflects and your own hits fill the enemy's posture bar, and a full bar opens the enemy for a finisher. Blocking without deflecting fills your own bar. Bare fists can guard and deflect too.
- **Stealth finisher:** behind an unaware enemy, either attack button finishes it with that weapon (replaces the back drop).
- **Deflect sound** and **Perfect dodge sound:** choose the sound each one plays.

### Atmosphere
- **Darkness** and **fog**, each 0-100.
- **Fog colour** (grey, white, green, red, black), a **clear radius** around you, fog that **reacts to movement**, a **fog layer**, and **fog wisps** with a choice of wisp effect.
- **Flickering lights** and a **lantern** (a light around you).
- **Film grain** (0-100), **light glow** (bloom, %), **ink outlines**, and a **colour tone** (neutral, cold, sickly, sepia, blood).
- **Randomized floor atmosphere:** each floor rolls one preset: Clear, Dusk, Morning Mist, Ground Fog, Toxic Haze, Blood Moon, Blackout, Silent Hill or The Abyss.
- **Atmosphere events from other mods:** POSTMORTEM's depth gloom and floor events (blackouts, fog nights, blood moons) can dress the floor through Heavenly Designs.

### Measuring
- Load times and the slowest server requests, recorded for anyone who wants to see where the time goes.

## Install

1. Install [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000) first.
2. Download `HeavenlyDesigns-<version>.zip` from [Releases](../../releases), close the game, and unzip it into the LET IT DIE folder.
3. Open `ModDriveInstaller\ModDrive9000.exe` and choose **Apply mods to the game**.

**Updates and removal:** in `ModDriveInstaller\ModDrive9000.exe`, under **Mods**. The settings files go back to the originals.

LET IT DIE belongs to GungHo Online Entertainment / Supertrick Games. This is an unofficial fan project.
