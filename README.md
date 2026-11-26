# Unfinished Tales - Candy House Adventure: playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.19.2 clears temporary mechanism connectors, translucent platform underlays, collision/trigger outlines, reference marks, placeholder shapes and shadow blocks from all three floors and rooms. Mechanism state is shown through the supplied plates, rising gates, extending bridges, doors and original animations. Actual playable ramps retain existing cookie-floor artwork; model paths and collisions are unchanged. Puzzle selection and bridge sockets no longer display colored rectangle backgrounds. Supplied artwork replaces geometric tutorial diagrams.

Both upper-floor exits retain the paired room_door_closed/open artwork from 0.19.1; only the first-floor final exit uses exit_door artwork. Their positions, sizes, fade and original completion conditions are preserved.

All original physics, puzzles, stories, controls, difficulty, audio events and supplied media remain unchanged. The staged loading and runtime raster cache from 0.19.0 remain active. Every image, audio and Phaser build file matches 0.19.1: 321 of 324 build files are identical; only HTML, application JavaScript and CSS differ. Older immutable assets remain available for open tabs.

Source commit: 7d395ce365cf6c88881a3bf721d22088b97303e2

Validation: 306 model tests, 454 artwork/source hash checks, TypeScript/Vite build and five Chrome cases pass. Real-input desktop and phone routes complete both runners, eight physical-lane answers, all three rooms, both cakes, badges, key and original ending. Desktop and iPad-viewport touch routes verify both room doors and comic transitions. An additional 1,682-frame audit with debug enabled finds no helper rectangles, lines, circles, dashed paths, collision outlines or inter-mechanism connectors; formal scene artwork remains loaded. Actual pendulum support uses its existing rope image. No physical iPad verification is claimed.

The exact build also passes two anonymous local upper-floor entries with eight HTTP asset hashes. Published integrity and deployment results are recorded in the source repository's VISUAL_CLEANUP.md and artifacts. Complete natural routes are verified locally, not claimed as a second anonymous production playthrough.

See release.json for source/build hashes. Earlier performance figures retain their measured 0.19.0 source commit; they are not new 0.19.2 benchmarks.
