# zhele 0.6.3 · 11.10.2026

Malformed ZA1/ZA2 keys, ZI1 issuer certificates and invalid activation request bodies now produce controlled refusals instead of internal errors. Rejected input leaves an existing valid key unchanged, including its modification time. Valid ZA1/ZA2 and legacy activation remain compatible. Both activation and About show the new errors in Russian and English.

The packaged change is limited to access/server_app native modules, three web translation/UI files and the version. All other 2805 payload files match 0.6.2, preserving its startup, recovery and runtime fixes. Checked: 25 compiled activation cases; six malformed-key and real HTTP validation matrices with ephemeral signatures; RU/EN messages for both forms; native About 0.6.3; installer CPython3.12 x64/dependency/25-module health; author-signed ZHU, all 2811 hashes and source exclusions. Prior 0.6.2 installer/update retained for rollback.

The installer has no Authenticode publisher signature. Windows warnings may remain. Author signing of the ZHU is separate. Tests used the author's Windows with existing dependencies, temporary activation identities and CPU-only settings; a clean foreign Windows was not tested. Payments, entitlements and issued-key formats are unchanged.
