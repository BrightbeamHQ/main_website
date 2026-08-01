# Hotfix v2.0.1: disable analytics init call causing onboarding crash

_Priya, Tom · 2026-06-25_

Emergency mitigation for the crash spike since yesterday's launch. Root cause is a race condition between the analytics SDK init call (added post-freeze on 6/23) and a background permissions check, both firing during onboarding. This disables the analytics call via a remote flag rather than fixing the race properly — full fix tracked separately.

Merged and shipped as v2.0.1, 2026-06-25.
