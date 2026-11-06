# Repository consolidation and cleanup

The 6 November 2026 cleanup keeps one active source branch, `main`, in `unDead41/geoMathApp`. Each original head is recorded in [CLEANUP.json](CLEANUP.json) and retained as commit ancestry. Only reviewed, unchanged redundant branch refs may be retired, after the current main passes CI and the archive tag is verified.

- All six historical App branches are represented in main; endpoint comparisons retain current main fixes.
- The latest app head contributes a typed AI scroll key, adaptive navigation regressions, real SQLite upgrade/reopen/actor-isolation tests and continuation evidence.
- All eleven-model bundled offline assets, canonical source locks, dependency lock, Android identity and signing configuration are retained.
- Completed migration scripts/workflows are removed; source-split receipts and original mockups/evidence remain archived in context.

Original PDFs, printable resources, mockups and runtime offline assets keep their original Git blobs. Historical screenshots/logs remain associated with their original reports, even when two observations have equal bytes. Only obsolete migration executables, completed one-off workflows and explicitly inactive fixtures are removed. The repository-split provenance remains under `docs/archive/repository-split-20261106/`.

The archive tag is `archive/app-before-cleanup-20261106`. To recover a historical branch, fetch that tag and create a review branch from the recorded SHA. Port needed source onto current main; do not restore an old mixed-platform tree.

## Completed verification

The repository now has one active branch, `main`, at App version 0.3.1+5. Six historical feature branches and two preparation branches were retired after exact-head, ancestry and archive checks. [The archive tag](https://github.com/unDead41/geoMathApp/tree/archive/app-before-cleanup-20261106) directly retains all seven original heads as parents, plus the preparation history. Original file trees are recovered through the recorded original SHAs.

[Clean-checkout verification](https://github.com/unDead41/geoMathApp/actions/runs/42219852843) passed on source `c6c1f75bea429059e83f2ce421d3a0c963f8c364`: Flutter 3.47.9 / Dart 3.13.7, 237 Dart files formatted without changes, no analyzer issues, 676 Flutter tests passed, 18 opt-in visual profiles skipped, 60 Node checks passed and 36 Python tooling tests passed. No test failed. Two offline adapter rebuilds reproduced the shipped asset bytes exactly. The planning/mockup inventory passed.

`flutter build apk --debug` compiled the integrated Android application; the post-build Git diff remained clean. All 187 protected runtime/assets/Android/lock blobs match their reviewed source identities, including the latest typed AI scroll key from the app branch. All 59 original binary assets remain byte-identical. The eleven-model offline bundle, canonical source locks, dependency lock, package identity and signing configuration are preserved.

[Branch retirement](https://github.com/unDead41/geoMathApp/actions/runs/42221305579) completed successfully. No new emulator/phone execution, manual accessibility check, hosted Auth/classroom/two-client Duel acceptance or production signing is claimed. This completion update changes only the two cleanup records. Current clone/run/update commands are in [RUN_ANDROID.md](../../apps/geomath_flutter/docs/RUN_ANDROID.md) and the [AI handoff](../../apps/geomath_flutter/AI_HANDOFF.md).
