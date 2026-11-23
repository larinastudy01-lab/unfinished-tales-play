# Candy House Adventure — playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.5.0 restores the original eight knowledge questions in the second-floor witch chase. The runner continues on safe flat tracks while all text options are visible. A short reading lead precedes the original three-second answer window. Correct answers widen the gap and trigger a companion kick; three wrong or timed-out answers retain the original failure rule. Hazards, the biscuit shield and upper bypass sit between questions. The selected sibling remains under the same player's control and the original first-floor/ending flow is retained.

Keyboard: A/D move, W/Up/Space variable jump, Q gummy; 1/2/3 answer directly or arrows and Enter. Touch: scene controls and text answer buttons. Standard PS-style gamepad on floors two and one: D-pad selection, × confirm, ○ cancel, Options pause; second-floor × jump and □ gummy. Hardware and vibration motors have not been physically tested.

Source commit: f72353668251196206f7d7be4c06cc02de50f396

This public repository contains generated playable files only. Private source retains the existing game project. release.json records SHA-256 for the 108 current build files. Older immutable bundles are retained for open tabs.

Validation: 78 core tests; 25 integrated Chrome cases plus 2 legacy second-floor artwork checks; 24 question/viewport layouts; TypeScript and Vite build. The integrated suite includes both selected-character full adventures, four eight-question keyboard/touch chase routes, wrong/timeout/retry, and two eight-question simulated gamepad routes. Exact production-build checks cover the first question with correct/wrong/timeout across desktop, phone and landscape from a valid checkpoint. This does not claim a complete live-site playthrough or physical controller testing.
