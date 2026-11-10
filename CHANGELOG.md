# Changelog

## 1.2.1
- **You are invulnerable during a counter** (after a perfect dodge or Perfect Guard): from the warp until the counter attack, the ranged counter or the groggy move ends.
- **Perfect dodge works against projectiles and explosions** (fireworks, arrows, bullets, rockets): any hit that would land in the first moment of your dodge counts, and the counter goes to whoever fired it.
- **Lock-on jumps to the next enemy** when the enemy you are locked on to dies (the nearest one you can lock). Releasing the lock yourself still releases it.

## 1.2.0
- **New option: Improved defence** (on by default). A **perfect dodge** (an enemy attack that lands in the first moment of your dodge) takes no damage at all and readies a counter; so does a **Perfect Guard**. Attack right after it and you are at that enemy's side: it staggers and your attack hits 1.5x as hard. When the enemy is nearly dead (a quarter of its health or less) and your weapon's mastery has the groggy finisher, the counter is the full groggy move instead.
- **Counters with a gun, bow or other ranged weapon** do not teleport: you lock on and turn to face the enemy, it staggers, and for as long as you keep firing (up to 2.5 seconds) every shot flies straight at it and does 1.5x -- a slow magnum and an assault rifle get the same boost for the same time.
- Fixed: counters did not start with guns that shoot while moving (fireworks launcher, assault rifle, crossbow and others).
- **Improved targeting locks on behind you**: pressing lock-on with no enemy in front locks the nearest enemy around you. Mushroom beasts are never picked by it or by pointing the stick, and pressing lock-on while locked releases the lock again.
- **Improved targeting keeps the lock up to about twice as far** (28 m instead of 15).
- In a POSTMORTEM game the improved defence / targeting tuning values in settings.txt are ignored (the shipped values are used), so they cannot be raised for its leaderboard.
- Improved targeting is now on by default.

## 1.1.0
- **New option: Improved targeting** (off by default). While you are locked on (R3) the camera stays behind you and keeps the enemy in view, like Dark Souls, instead of only turning when you strafe. Point the right stick toward the enemy you want, from the one you are locked on to, to switch to it. With a mouse, swipe left or right instead (as in Dark Souls 3 / Elden Ring); the option "Mouse swipe to switch target" sets how big a swipe it takes. If no enemy lies the way you point, the lock goes to the enemy nearest to that direction, however far round it is (pointing north with the only other enemy to the south switches to it).

## 1.0.1
- Supports the LET IT DIE update of 2026-10-20 (Steam build 25923506).

## 1.0.0 (first public release)
- Quality pack: texture pool, anisotropic filtering, 2048 shadows, high-precision G-buffer.
- 5 s texture-streaming wait on map loads instead of 20 s.
- Options in the Mod Drive 9000 tab: fast loading, skips, atmosphere events.
