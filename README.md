# Candy House Adventure - playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.8.0 adds a second continuous cooperation relay to the third floor. First, land on the upper plate to open the companion's cookie gate; the companion extends the player's wafer shortcut. Later, the companion takes the upper route and raises a lollipop gate for the player below. Jump onto the side plate to extend a wafer across the companion's gap. Timely help lets the companion cross and rejoin sooner; missed or late help sends the companion along a visible downhill detour. The normal player route always remains playable within the original 60-second limit. The selected sibling remains the only controlled character. The original knowledge chase, first-floor puzzles and ending remain.

Keyboard: A/D or arrows move; Space/W/Up jump (tap low, hold high); Q uses a collected gummy. Standard mapped PS-style gamepad: D-pad/left stick move, cross jumps, square uses a gummy, Options pauses. No new interaction key is needed for either relay. First-floor and knowledge-answer controls remain as explained before play.

Source commit: 7d3fac56adc822b1497a235d8e29c350f0f7cbb0

Validation: 126 core tests and 50 distinct Chrome cases; both characters, normal/gummy cooperation, successful/missed/late plate routes, touch and simulated standard-PS input, reset/transition and retained full-adventure regressions. Production-build replays verify the complete third floor and original second-floor transition. Physical PS hardware and vibration motors have not been tested. release.json records exact validation scope and hashes for 108 current build files. Older immutable bundles remain available for already-open tabs.
