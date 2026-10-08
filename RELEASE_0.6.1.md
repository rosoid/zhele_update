# zhele 0.6.1

Published 9 October 2026; build version 0.6.1 (08.10.2026).

- Training continuation preserves RNG and rejects missing selected snapshots.
- JSONL teaching pools select new examples for persistent failures, with provenance, holdout and duplicate checks.
- Model checks have state filters, groups and a form for the next teaching portion.
- Real GGUF validation uses a bundled Windows x64 CPU llama.cpp runtime.
- Runtime updates wait safely while a verifier is using it.
- Automatic launch/version reporting was removed; licensing and machine binding remain.

The installer is not Authenticode-signed. Windows security warnings may appear. Clean-machine dependency installation and first launch have not been verified. The update package is signed by the author.
