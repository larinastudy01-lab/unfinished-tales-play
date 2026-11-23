# Candy House Adventure - playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.7.0 updates the third-floor Frosting Attic. Land on the upper pressure plate to open the companion's rear cookie gate. The companion actually crosses and presses a second plate, extending a wafer landing ahead. Its solid width follows the animation; after full extension a latch holds it for at least 2.5 seconds and until the player is safely beyond it. The companion then rejoins on the lower route. Missing either cooperation step still leaves an ordinary lower route that completes within the original 60 seconds. The original second-floor knowledge chase, first-floor three rooms, badge/key flow and comics remain.

Keyboard: automatic rightward running; A/D or arrows move; Space/W/Up jump (tap low, hold high); Q uses a collected gummy. Standard mapped PS-style gamepad: D-pad/left stick move, cross jumps, square uses a gummy, Options pauses. On floor two, D-pad chooses an answer and cross confirms. First floor: E or cross interacts, arrows operate puzzles, circle cancels/releases, Q or the room exit returns. Controls and cooperation diagrams appear before play.

Source commit: 1a979ee369fa5b7cd12285706ffcfde51e073581

Validation: 107 core tests, 36 integrated Chrome cases and 4 legacy art/difficulty cases; TypeScript and production build. Third-floor complete routes cover both selections, normal and gummy upper cooperation, touch lower fallback, missed-wafer fallback and two simulated standard-PS routes. Three anonymous exact-build production keyboard replays complete third floor and enter the original comic/second-floor transition. Normal routes take about 37.02 seconds; the boosted upper route about 34.25 seconds. Controller hardware and vibration motors have not been physically tested.

This repository contains generated playable files only. release.json records SHA-256 for the 108 current build files. Older immutable bundles remain available for already-open tabs. The private source repository retains the project.
