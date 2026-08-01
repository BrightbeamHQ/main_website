# Fix cancellation flow race condition

_Tom · 2026-07-11_

Ensures the cancellation flag is checked synchronously before any billing cycle proceeds, closing the race described in #120.

Closes #120. Merged 2026-07-11.
