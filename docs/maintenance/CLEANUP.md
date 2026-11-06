# Repository consolidation and cleanup

The 6 November 2026 cleanup keeps one active source branch, `main`, in `unDead41/geoMathApp`. Each original head is recorded in [CLEANUP.json](CLEANUP.json) and retained as commit ancestry. Only reviewed, unchanged redundant branch refs may be retired, after the current main passes CI and the archive tag is verified.

- All six historical App branches are represented in main; endpoint comparisons retain current main fixes.
- The latest app head contributes a typed AI scroll key, adaptive navigation regressions, real SQLite upgrade/reopen/actor-isolation tests and continuation evidence.
- All eleven-model bundled offline assets, canonical source locks, dependency lock, Android identity and signing configuration are retained.
- Completed migration scripts/workflows are removed; source-split receipts and original mockups/evidence remain archived in context.

Original PDFs, printable resources, mockups and runtime offline assets keep their original Git blobs. Historical screenshots/logs remain associated with their original reports, even when two observations have equal bytes. Only obsolete migration executables, completed one-off workflows and explicitly inactive fixtures are removed. The repository-split provenance remains under `docs/archive/repository-split-20261106/`.

The archive tag is `archive/app-before-cleanup-20261106`. To recover a historical branch, fetch that tag and create a review branch from the recorded SHA. Port needed source onto current main; do not restore an old mixed-platform tree.
