# zhele 0.6.2 · 11.10.2026

Fixes blank desktop loading during simultaneous module requests, authenticated startup with an occupied port, and cleanup of owned processes after close, hard termination or startup failure. The installer offers RU/EN, one readable agreement, and checks CPython 3.12 x64, required dependencies and packaged native modules before reporting success.

Interrupted updates recover through a stable stdlib bootstrap before importing replaceable modules. The journal commits before replacement; rollback retains originals until completion. In-place updates cannot change an existing bootstrap. These protections apply to the new updater; the old updater performing the initial upgrade is not retroactively protected.

Validation: actual RU/EN cold launch and reload with full scene and empty error console; occupied foreign HTTP service preserved; normal close, launcher hard termination and missing WebView library cleanup; signed production package through the compiled updater, all 2811 hashes verified, user-data sentinels preserved, bootstrap recovery repeated safely. Worker cleanup uses a harmless test worker in private installed copies; the distributed bootstrap is unchanged.

This Windows already has dependencies. A clean foreign Windows and the tester's PC remain untested. CPU checks use CUDA disabled and two-core affinity. The EXE has no Authenticode signature; Windows warnings may remain. The ZHU uses the existing author signature. Previous public 0.6.1 artifacts are retained for rollback.
