# Candy House Adventure - playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.12.0: run and jump into the three actual second-floor answer entrances. Read the question, high-jump to A, short-jump to B, or drop to C. You can change lanes before crossing an entrance while grounded. The companion shields correct answers and rejoins after the midpoint gate or bypass.

Choose Hansel or Gretel once. Keyboard A/D moves, Space/W/Up jumps (tap low, hold high), Q uses gummy. Standard PS left stick/D-pad moves, cross jumps, square uses gummy. Touch uses existing movement and jump icons. The answer labels are passive, not buttons. First-floor interaction, puzzles, three unique gifts, badges, key and original ending remain.

Source commit: f18e77eb78022c1bed2f229e232fdb1e8ab88634

Validation: 185 core and 27 focused browser cases passed. Eight original knowledge questions now use actual upper/middle/lower platform entrances. Only a grounded rightward crossing commits an answer, with safe reading, three-second decisions, single settlement, shield/no-shield waves and a midpoint companion gate/bypass. Complete local keyboard/touch playthroughs and real Gamepad polling with a simulated standard PS pad cover both siblings, all three routes, wrong answers, timeout, third-error retry, corrective jumps, late gummy support timing and the original first-floor transition. Two full adventures retain third-floor and first-floor puzzle/gift/key/ending flow. Four anonymous exact-build production checks use ordinary keyboard events from a saved level boundary for A/B/C/timeout and responsive full text. Physical PS controllers and vibration motors were not tested. Public cold asset downloads may be slow on the tested connection. Exact scope and SHA-256 for 108 build files are in release.json. Older immutable bundles remain for already-open tabs.
