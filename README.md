# Unfinished Tales - Candy House Adventure: playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.18.0 adds the unified game audio system using the 12 supplied original MP3 files: nine scene/story tracks and three event-driven effects. It includes crossfades, continuous comic/room music, parked hallway progress, independent quiz/completion ducking, pause/resume, hidden-tab cleanup, explicit retry restart and one-shot ending playback. Playback unlocks through existing player gestures; no controls or layout were added.

All 47 formal artwork categories and previous gameplay remain active. 156 image, animation and CSS build files retain their 0.17.0 paths and SHA-256. Source MP3 bytes are unchanged (13,497,089 bytes).

Source commit: a078cfcb2ea68ee52a278af7667e62e22d660489

Before publication: 291 model tests, 39 browser cases, 2 anonymous exact-production cases and 12 original-audio byte checks passed. Real Web Audio PCM output, silent mute and resumed output were measured in Chrome. See release.json for scope and build hashes. Public post-deployment verification is recorded in AUDIO_SYSTEM.md in the source repository. Old immutable assets remain available for open tabs.

Final audio-only correction waits for actual incoming playback before starting synchronized fades, including first gesture. Master/BGM/SFX volume and mute preferences persist through reload. One real delayed-HTTP case, three complete audio cases and one actual PCM/reload case were rerun after this correction; previous gameplay/art regressions remain unchanged.
