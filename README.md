# Unfinished Tales - Candy House Adventure: playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.19.1 replaces both upper-floor temporary exits with the supplied room_door_closed/open artwork. Doors align with the unchanged finish line and cookie floor, behind the characters. The attic door opens on approach; the witch-chase door opens after the original clear condition succeeds. Both reuse the existing 0.24-second crossfade. The first-floor final exit keeps its separate exit_door artwork.

Version 0.19.0 introduced offline image trimming, character alignment, seven lossless animation atlases, staged loading and released image/raster caches. These optimizations are preserved.

All 47 formal artwork categories, original physics, collisions, puzzles, stories, controls, layout and audio events remain active. Original supplied images and audio are preserved in the source repository. Runtime artwork uses lossless derivatives or smaller unchanged originals; display artwork retains full resolution. Nine BGM files use genuine MP3 derivatives with exact playable sample lengths; the three short sound effects remain unchanged.

Source commit: c4fd457cb74f71650c2f37581047d308a5d07836

Validation for 0.19.1: 306 model tests, exact-source TypeScript/Vite build, and two complete desktop/keyboard and iPad-viewport/touch upper-floor routes passed. Both original comic transitions, all eight physical answer lanes, door states/size/alignment/layering and first-floor room/exit distinction are verified. No images, audio or CSS changed; all 322 other dist files match 0.19.0. Canvas warnings and asset failures are zero in both routes.

The previous 0.19.0 full regression (40 Chrome cases, WebKit touch checks and anonymous production flows) remains documented in the source performance report. Its performance figures are labeled with their measured source commit in release.json, rather than presented as new 0.19.1 measurements.

See release.json for exact build hashes and PERFORMANCE_REPORT.md in the source repository for before/after measurements, waterfall analysis, the 20 slowest baseline resources and verification scope. Chrome touch emulation and Windows WebKit do not constitute physical iPad testing. Old published immutable assets remain available for open tabs.
