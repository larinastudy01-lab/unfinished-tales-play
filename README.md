# Candy House Adventure — playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.6.0 makes first-floor cooperation a required part of each puzzle. The player keeps the selected sibling throughout the adventure. In the living room the first cake extends stairs so the companion can hold the high latch and unlock the chocolate board. In the kitchen the first recipe enables the companion to replace the board before the second recipe. In storage a short candy extends the companion's route to the inside; the red candy raises the shutter, which the companion must actually hold before the player enters. The player solves each board and takes every gift. The original badge sockets, key, door and forest ending remain.

Controls: keyboard WASD/arrows and E interact; arrows operate boards; Q returns. Standard PS-style gamepad on floors one and two: D-pad/left stick move and select, × confirm/grab/interact, ○ cancel/release and return from a puzzle, Options pause. The room doorway also returns to the hallway. On floor two × jumps and □ uses a gummy; original knowledge questions use D-pad/× or keyboard 1/2/3. Controller hardware and vibration motors have not been physically tested.

Source commit: 32a563fb1efa4435a5871192fed939c21d6fabdd

This repository contains generated playable files only. release.json records SHA-256 for the 108 current build files; old immutable bundles remain for open tabs. Private source retains the existing project.

Validation: 91 core tests, 27 integrated Chrome cases plus 2 retained second-floor artwork checks, 33 scene/viewport checks, TypeScript and Vite build. Two simulated PS routes take all 15 first-floor gifts and complete the exit; separate normal-selection keyboard/touch adventures cover all floors. After the contained partial-door reset correction the 91 core tests and both full PS routes were rerun. Exact production-build checks cover six complete fresh-room checkpoint → puzzles/support → gift → hallway/reentry routes in desktop/phone/landscape. This does not claim physical controller testing or a complete live-site adventure playthrough.
