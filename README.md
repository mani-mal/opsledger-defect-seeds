# OpsLedger defect seeds (synthetic, deliberately broken)

This repository is part of a controlled defect-repair experiment on OpsLedger, a synthetic
benchmark application with no users and no deployment.

- `main` is OpsLedger at its accepted commit `1df8ac4`.
- Each `seed/Rnn` branch adds one commit that introduces one deliberate defect (R01-R12):
  missing authorization checks, races, idempotency and rounding errors, and unsafe HTML rendering.

Do not run, deploy or reuse this code. The repository will be deleted when the experiment ends.
