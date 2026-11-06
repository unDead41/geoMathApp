# geoMathApp contributor guidance

- This repository owns Flutter Android app, native UI, learning modules, classroom, Duel, adaptive AI and bundled offline assets. Its `main` branch is this platform.
- Firmware, GPIO, RFID, LCD, UID/NVS, wiring and printable hardware resources belong only to `unDead41/geoMathPhysical`.
- Editable browser portal and deployed Supabase backend source belong only to `unDead41/geoMathDigital`. App offline HTML/JS and contract reference files are intentional versioned App assets.
- App source stays at `apps/geomath_flutter/`; app design contracts stay at `docs/geomath-app/`. Read pubspec/lock, source locks and feature contracts before modifying runtime code. Preserve 11 models, server-authoritative Duel, actor-isolated storage and bounded AI.
- Canonical regeneration may consume an explicitly supplied read-only pinned Digital snapshot outside this repository. Normal build, tests and offline use require only this repository.
- Keep package identity, callback scheme and signing setup. Do not commit keystores, local SDK configuration or credentials.
- For Dart changes run formatter, analyzer and relevant Flutter tests; for bundle changes run existing Node contract tests. Distinguish host checks, Android compilation, emulator and phone.
- Check working tree and remote branch before editing. Preserve unrelated work; use explicit refs and do not force-push.
- Run `python3 tools/check_repository_scope.py` before publication. Never import the mixed repository tree or merge another platform.
- These instructions supersede historical monorepo branch/path assumptions in archived planning/handoff documents. New work must use the repository named above and its current `main`.
