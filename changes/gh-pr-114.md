# v2.0.2: full fix for onboarding analytics race condition

_Priya, Tom · 2026-06-27_

Properly fixes the race condition from #112 by sequencing analytics init after the permissions check completes, rather than disabling analytics entirely. Crash rate in internal testing back to baseline (~0.5%).

Merged and shipped as v2.0.2, 2026-06-29.
