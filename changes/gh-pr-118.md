# Fix Stripe webhook idempotency handling

_Tom · 2026-07-10_

Adds idempotency key tracking so retried Stripe webhook deliveries don't get processed twice. Fixes duplicate/missing confirmation emails from #117.

Closes #117. Merged 2026-07-11.
