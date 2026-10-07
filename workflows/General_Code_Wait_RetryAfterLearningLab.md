# Retry-After learning lab

Import `General_Code_Wait_RetryAfterLearningLab.json` into a blank n8n workflow and select Execute workflow. No credentials are needed. Keep it inactive: the trigger is manual.

This is an educational simulation of a 429 response followed by a 200 response. The Wait node runs for real. The final Check loop outcome node should report PASS, two attempts, statuses 429 then 200, a gap of at least two seconds, and the original job ID `offline-demo-001`.

The retry policy handles integer seconds and HTTP-date Retry-After values, bounds total attempts and marks waits above the inline budget for deferral. The demo does not persist deferred jobs or coordinate shared API quotas. Transport errors and safe retries for write operations need separate handling. No live API calls were tested.

Original execution nodes tested in n8n Cloud 2.43.0. In-canvas instructions have been added without changing those nodes or their connections.

Guide, screenshots and companion 18-case policy suite: [OperantSolo Retry-After guide](https://operantsolo.com/n8n-rate-limit-retry-after/).

MIT licensed. Copyright (c) 2026 OperantSolo. See `General_Code_Wait_RetryAfterLearningLab.LICENSE.txt`.
