# Candy House Adventure - playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.13.0: failure now uses a four-part frosting ring. Press Space, PS cross or tap the ring four distinct times; holding counts once. The completed ring flashes and retries the stage automatically.

The existing eight second-floor questions use physical upper A / middle B / lower C entrances. Choose Hansel or Gretel once; the sibling follows and supports automatically. Keyboard A/D moves, Space/W/Up jumps, Q uses gummy. Standard PS left stick/D-pad moves, cross jumps, square uses gummy. Touch uses the existing movement and jump icons. First-floor puzzles, three unique gifts, badges, key and original ending remain.

The six-entry developer menu is available only on a loopback Vite development build with ?dev=1 and Ctrl+Shift+L. It is unavailable on this production site.

Source commit: c02c26acf5794909328f0763680a1674bd541017

Validation: 194 core, 34 complete focused browser cases and 4 exact-production ring checks passed. Four distinct Space / PS cross / touch presses fill a frosting retry ring, with held-death and long-press suppression, preserved progress and automatic stage-local retry after flash. A loopback development-only ?dev=1 Ctrl+Shift+L menu offers six fresh stage/room entries, preserves character and isolates formal saves. The production build has neither development menu nor model hook even with ?dev=1. The existing eight physical answer lanes, both siblings, shield/gate/bypass, wrong/timeout/third-error reset and first-floor transition remain. The complete 34-case local browser batch includes two full adventures through first-floor gifts, key and ending. Four exact-production ring checks use keyboard, touch and simulated standard Gamepad polling from a valid saved entrance and actual hazard. Physical PS hardware and vibration motors were not tested. Public full cold asset loading has not completed in the latest 300-second check; deployment and file integrity are distinct from public gameplay verification. SHA-256 for 108 files is in release.json. Older immutable bundles remain for already-open tabs.
