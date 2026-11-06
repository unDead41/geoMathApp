# geoMathApp

GeoMath **0.3.1+5**: Flutter Android app, native UI, learning modules, classroom, Duel, adaptive AI and bundled offline assets.

| Repository | Scope |
| --- | --- |
| [geoMathPhysical](https://github.com/unDead41/geoMathPhysical) | ESP32, RFID, LCD, wiring, printable resources |
| [geoMathDigital](https://github.com/unDead41/geoMathDigital) | Web portal, browser game, learning and backend |
| [geoMathApp](https://github.com/unDead41/geoMathApp) | Flutter app, Android, AI and offline assets |

## Run locally

```powershell
git clone https://github.com/unDead41/geoMathApp.git
Set-Location geoMathApp/apps/geomath_flutter
flutter pub get
flutter analyze
flutter test
```

Use the SDK version recorded in `apps/geomath_flutter/docs/TOOLCHAIN.md`. Android package identity remains `com.geomath.dev`. The App includes both the latest UI/UX refinement and bounded Easy/Medium/Hard AI battles.

## Source ownership

`main` is the only maintained source branch of **geoMathApp**. Every feature branch in this repository must contain only this platform. Read `AGENTS.md` and `docs/REPOSITORY_SPLIT.md` before editing. The original source layout is retained so existing build/test paths work.

Historical documents and canonical SHA locks describe their original snapshots; they do not authorize development in another repository. Filtered feature history and exact original-to-new branch mappings are recorded in `docs/archive/repository-split-20261106/receipt.json`.

All six historical App feature branches are consolidated into main, including their unique handoff, AI navigation/scroll regression and SQLite upgrade/reopen tests. Use [AI_HANDOFF.md](apps/geomath_flutter/AI_HANDOFF.md) for current source and PowerShell continuation commands. [Cleanup evidence and original head mapping](docs/maintenance/CLEANUP.md) retain the audit trail. The offline bundle remains versioned for standalone Flutter builds; original mockups and evidence are preserved.
