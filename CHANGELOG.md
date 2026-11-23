# Changelog

## 1.3.8
- Needs Mod Drive 9000 1.4.9.
- **The settings are three pages now:** Atmosphere, Gameplay and Performance.
- The headphone fix row is gone; the fix always runs.
- Posture, stealth and defense no longer act on the previous floor's enemies after a ride, and the stealth finisher's hold ends with the floor.
- Your atmosphere tint applies to the new floor straight away.

## 1.3.7
- **Fixed: a boss finisher froze your fighter.** Bosses are no longer broken into a groggy state they have no finisher for (Jin-Die); they take a stagger and a damage window instead.
- Your own darkness and fog no longer flicker away for a few seconds when an atmosphere event starts.
- For POSTMORTEM's Blood Moon: the red tone and a dark red fog show even when other mods' atmosphere is switched off (it warns that the enemies are stronger).

## 1.3.6
- Needs Mod Drive 9000 1.4.5.
- For other mods: the "blood moon" tone of the atmosphere service tints the picture red through the light curves (the colour tint alone showed nothing in game).

## 1.3.5
- **Fixed: unplugging headphones froze the game.** A Windows audio bug (XAudio2) deadlocked the game when the audio device disappeared; the game now carries on.
- A counter moves your lock-on to the enemy you countered.
- The pause menu stays open during a fight, including its Debug / Mods / Multiplayer screens.
- With the A-jump button layouts, the dropkick prompt is back and shows the Y button.
- Button layouts step aside while a menu is open (A no longer jumps in menus).
- The stealth finisher holds its target.
- Removed the ride skip (it could hand control back before the elevator had arrived).
- For other mods: the atmosphere service can now set a colour tone (POSTMORTEM's Blood Moon uses it).

## 1.3.4
- For the LET IT DIE update of November 2026 (game 5.0.6). Needs Mod Drive 9000 1.4.4.
- New option: **Dodge cancels attacks** (on by default). Pressing dodge rolls at once, even in the middle of a swing, so it is easy to react with a dodge. A dodge needs stamina, as always.
- Posture bars use the game's own health bar art.
- In co-op, every player's posture is shown over their body (Let Us Die's new option "Posture bars over allies").
- Fixed: with a remapped guard button, guard cancel read the wrong button (and dodge stopped working on button layout 1).

## 1.3.3
- New option: **Guard cancels attacks and dodges** (on by default). Pressing guard raises it at once, even in the middle of a swing or a roll, so perfect guards are easier to time. Jump attacks and grabs are never cut.
- Shots from far away (crossbow bolts and other projectiles) get a slightly longer perfect guard window.
- With an A-jump button layout, the "dropkick" prompt shows whenever the dropkick is ready.

## 1.3.2
- New option: **Guard fatigue.** Holding a guard for a long time makes hits on it cost more posture, and enemies that have blocked for too long stop guarding for a moment. A perfect guard is always safe.
- New option: **Guard / dodge / jump buttons.** The game's layout, or A jump / X guard / B dodge, or A jump / B guard / X dodge, so guarding and dodging are separate buttons. A only jumps when there is nothing to interact with.
- Lock-on: switching targets can no longer drop the lock-on. If the new target is gone, the lock goes back to the last target or the nearest one.
- Co-op: an enemy's posture and posture break are the same for everyone in the party (a groggy enemy is groggy on every screen), and the floor atmosphere matches for everyone.

## 1.3.1
- Skip ride: the escalator ride is skipped for real now. The escalator's own trigger at the bottom starts the next floor as soon as you step on, instead of riding the whole way down.
- Skip ride: the elevator ride ends as soon as the next floor is ready, instead of waiting for the voice line at the end.
- Fixed: a skipped ride could leave the arrival camera somewhere off in the level.

## 1.3.0
- Needs Mod Drive 9000 1.3.8.
- New option: Stealth finisher (replaces the back drop). Sneak up behind an enemy and finish it with either weapon instead of the piledriver.
- Posture break: bare fists can guard and deflect armed hits (the game refuses a guard without a weapon).
- Posture break: a full posture bar now breaks an enemy that is guarding too (it could fill up with no finisher state following).
- Posture break: a plain block chips the attacker's posture a little (a deflect still fills far more).
- Improved defence: dodging AWAY from an attack counts as a perfect dodge when the swing would have reached you (it only counted when the hit passed through you).
- New options: Deflect sound and Perfect dodge sound (pick from the game's own guard sounds; the choice is played when you change it).
- Lock-on: a lock is released when the enemy stays out of sight behind a wall, and the lock button no longer picks mushroom beasts or enemies behind walls.

## 1.2.2
- New option: Posture break. Press guard just before a hit to deflect it: no damage, and the enemy is not interrupted, so a whole string can be deflected. Deflects and your hits fill the enemy's posture bar (above its head); a full bar breaks it -- haters are stunned and open to the finisher (no weapon mastery needed), other enemies stagger and take more damage for a moment.
- Posture break: blocking without deflecting fills your own posture bar (bottom centre); a full bar is a guard break.
- Posture break: a guard press during an attack's recovery raises the guard as soon as the swing has hit, instead of waiting for the animation.
- Improved defence: a perfect dodge now also counts against projectiles that fly past you (rockets, bullets), and a projectile guarded at the right moment is a Perfect Guard.
- The atmosphere census (a research log) is off unless you switch it on. It cost 0.1 to 0.2 s at the start of every level.
- Co-op: a perfect dodge can no longer ready a counter against a teammate.
- Improved targeting no longer locks on to enemies behind walls and floors (lock on behind you, the flick to the next target, the jump on a kill).
- Posture break: a deflect readies the counter, like a Perfect Guard (deflecting a projectile never led into a riposte).
- Posture break: an enemy's bar disappears the moment it dies, and beasts (frogs, turtles, crabs ...) have no posture bar.

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
