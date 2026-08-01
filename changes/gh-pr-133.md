# Perf fix for mobile checkout under load

_Tom · 2026-07-09_

Adds caching for the pricing calculation step that was blocking checkout page render under load. Resolves the slowdown from #132.

Closes #132. Merged 2026-07-09.
