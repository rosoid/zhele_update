# zhele 0.6.5 · 12.10.2026

Automatic interface translation now leaves project/block names, paths, code and model/helper replies unchanged. UI titles and accessibility labels remain translated. Installation docs clarify CPython3.12 x64, installer/payload sizes, source-core versus closed modules, and configured external helper services.

Exactly 11 payload files changed: six frontend files, four documents and version.py. All 25 native modules and 2800 other files remain byte-identical to accepted 0.6.4; no native recompile. Accepted 18 frontend regressions and actual source CUA are inherited through exact SHA matching. Targeted packaged checks: served JS hashes, HTML key/language injection, remote header guard, compiled server About version0.6.5; author-signed ZHU/all2811hashes/source exclusions. Torch metadata was stubbed for the narrow About test; no compute/training or repeated baseline runtime tests.

Previous 0.6.4 installer/update retained. EXE has no Authenticode signature; Windows warnings may remain. A clean foreign Windows remains untested.
