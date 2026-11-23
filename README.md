# Candy House Adventure

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Public playable build with keyboard and touch controls. This repository contains only the generated game and the artwork required to play it.

Latest update: removed the second-floor witch-distance panel and support lines above floating hazards. Ten ground obstacles now sit flush with the floor by cropping bottom white padding at runtime, preserving the original image files and collision geometry. Previous floating tutorials, RPG dialogue and SKIP are retained.

Release source: f8d262dc848e7d109b2e3148de2a2f4917668857.

Validated before publishing: 38 core tests, two desktop/touch browser checks covering all sixteen obstacles, floor alignment, lethal contact, retry and eight safe quizzes, TypeScript checks, and a production build. Build provenance and file hashes are recorded in release.json.
