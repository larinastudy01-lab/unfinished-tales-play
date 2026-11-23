# Candy House Adventure - playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.11.0 adds nearby interaction icons and one gift per first-floor room. Approach an unlocked task station, cabinet handle or gift and use E, PS cross or the touch hand. The icon follows your most recently used input device. Automatic plates and companion support remain automatic.

Completing the puzzles prepares the room's gift. Personally collect that single gift to complete the room and earn its badge together. Returning to a completed room preserves open mechanisms and shortcuts without creating another gift. Three badges reveal the existing key and ending. Choose Hansel or Gretel once; the other sibling supports automatically.

Keyboard: A/D or arrows move, Space/W/Up jumps (tap low, hold high), E interacts, Q returns from a room. Z undoes a puzzle move; R resets the current board while preserving earned milestones. Standard PS mapping: D-pad/left stick moves, cross jumps or interacts by context, circle cancels, L1 undoes, R1 resets, Options pauses. Touch uses icon controls and puzzle gestures. Instructions appear before play. The third-floor runner and second-floor knowledge chase keep their existing controls.

Source commit: 6f565256e607a1b0e4e4b20ee6941fc2ada95406

Validation: 178 core tests passed. The focused first-floor Chrome acceptance batch passed all 22 cases (exit 0), including new keyboard Hansel and simulated standard PS Gretel journeys through three unique gift pickups, completed reentry, three badges, key and original ending; phone icon-device switching and touch confirmation; existing room exploration, causal support, puzzle gestures, controller controls, wordless screens and two full adventures. Only the first-floor boundary is a fixture in the new complete journeys: actor movement, cooperation, puzzle inputs, pickup and exit use live controls. Four no-development-hook exact-build production checks cover fresh living/kitchen/storage task routes and icons, keyboard/PS API switching, and advanced kitchen touchscreen delivery through unique pickup, shortcut and completed reentry. They do not claim a full public playthrough. Physical PS controllers and vibration motors were not tested. Exact scope and SHA-256 hashes for 108 current build files are recorded in release.json. Older immutable bundles remain for already-open tabs.
