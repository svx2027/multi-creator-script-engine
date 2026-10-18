# multi-creator-script-engine

A production system for running short-form and long-form video scripts across 15+
education creators at once, without quality drifting from creator to creator.

## What it does
- Builds one analyzed voice profile per creator from their own past scripts, so every
  brief sounds like them, not like a template.
- Turns a single line ("three shorts for creator X, here are the titles") into finished,
  ready-to-shoot briefs.
- Locks a house format: scroll-stopping SEO titles, a hook that guides without scripting
  the creator word for word, and two standing calls to action (subscribe early, promote
  the current offer).
- Assigns a production code to every script and logs it to a ledger that tracks each
  piece from drafted to published, ready to join with performance data.

## Why it matters
One operator can brief a whole roster in an afternoon, the creators keep full creative
control, and the system compounds: each delivered script sharpens the voice profile, so
next month's briefs land faster and perform better.

## Honest scope

- **This repository is a write-up, not a runnable tool.** No code is published
  here — the "15+ education creators" system runs against a private
  repository holding the real creator scripts and ledger, and this page
  describes the design, not a package you can clone and run.
- **"Full creative control" is a process claim, not a measured one.** No
  retention, engagement, or performance numbers are published here to back
  the "land faster and perform better" claim — the ledger exists to make
  that measurable over time, but this write-up doesn't cite a number.
- **The voice profile is built from past scripts only.** It has no signal on
  how a creator actually delivers a brief on camera, so a brief can still
  read right on paper and land differently once performed.
- **"Full creative control" means creators can still change or reject a
  brief before it airs.** The system compresses the drafting step, not the
  judgment call on whether a specific brief is right for that creator this
  month.
