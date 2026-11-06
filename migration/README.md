# GeoMath repository separation

Requested on 6 November 2026: independent Physical, Digital and Flutter App repositories.

This repository owns the Flutter app. Source migration will preserve the existing app paths and filtered app branch history, combine the UI/UX and adaptive AI updates, and verify contracts before publication. The ESP32 firmware and the Digital portal/backend source belong in their own repositories.

Canonical source snapshots:
- UI/UX: unDead41/geoMathPhysical@67c1e1bf76064d5df2787bef90ec789d1a21a975
- AI: unDead41/geoMathPhysical@288dc703d61479cb89a22d4f2416d71d9b8294ac

No production backend or Pages deployment is part of the source separation.
