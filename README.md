# Unfinished Tales - Candy House Adventure: playable build

Play: https://larinastudy01-lab.github.io/unfinished-tales-play/

Version 0.19.0 prepares image trimming, character alignment and seven lossless animation atlases offline. Only title art loads initially; existing player interactions prefetch the opening and attic, runners prefetch their next floor, and rooms load independently. Destination loading freezes original game clocks until ready.

All 47 formal artwork categories, original physics, collisions, puzzles, stories, controls, layout and audio events remain active. Original supplied images and audio are preserved in the source repository. Runtime artwork uses lossless derivatives or smaller unchanged originals; display artwork retains full resolution. Nine BGM files use genuine MP3 derivatives with exact playable sample lengths; the three short sound effects remain unchanged.

Source commit: f28f44442d4b917e518d4da646bf722247461d3e

Before publication: 306 model tests, 40 Chrome browser cases, WebKit iPad viewport/touch checks, 2 anonymous exact-production cases and 12 runtime-audio byte checks passed. Canvas startup readbacks fell from 315 to the five framework initialization calls; application readbacks and Canvas warnings are zero. A shared prioritized queue deduplicates loads, caches prepared Canvas rasters, and releases obsolete decoded images/backing stores. No global Canvas readback flag or unverified renderer switch is applied.

See release.json for exact build hashes and PERFORMANCE_REPORT.md in the source repository for before/after measurements, waterfall analysis, the 20 slowest baseline resources and verification scope. Chrome touch emulation and Windows WebKit do not constitute physical iPad testing. Old published immutable assets remain available for open tabs.
