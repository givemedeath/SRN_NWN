# ShadowRunnerNights

ShadowRunnerNights is a source-available, non-commercial tactical RPG
module project for Neverwinter Nights: Enhanced Edition.

It explores cyberpunk-fantasy themed RP and lethal, tactical combat designed for both
facilitator-led events and small-party play.

> **Current state: Design and engine experimentation.**
> This repository does not yet contain a playable module.

## Roadmap

| Phase | Status | Outcome |
|---|---|---|
| P-0A | Complete | Resolve no-code decisions and define bounded, measurable experiments |
| P-0B | Ongoing | Prove reproducible bootstrap, native compatibility, resolver integration, cadence, cover, explosives, and the NUI window foundation |
| P-1 | | Implement Human Mundane reference schema |
| P-2 | | Tactical-combat implementation |
| P-3 | | Implement the persistent run/recovery loop and GM operations |
| P-4 | | Expand progression and harden for a rights-cleared closed alpha |
| P-5 | | Imlement Races, Magic, Cyberspace, Drones, Astral |
| P-6+ | | Alpha Testing |

## Project direction

- **Tactical combat first.** Ranged combat, close combat, and explosives are
  distinct and deliberately balanced play modes.
- **Position and movement matter.** Cover, mobility, and readable counterplay
  offset high lethality.
- **Independently authored rules.** All mechanics, terminology, text, test
  cases, and implementation are written for this project.
- **Deterministic resolution.** Rules logic remains independent of engine
  objects, persistence, clocks, configuration, and production randomness.
- **Recoverable ordinary defeat.** Permanent character death is limited to
  explicitly prepared facilitator-run events with documented consent and review.
- **Evidence before breadth.** Unproven assumptions advance only through
  timeboxed go/adapt/stop experiments.
- **Reusable custom UI.** Typed interface components and prototype evidence
  precede production custom windows.

## Rights and provenance

This repository contains original project materials only. It does not include
third-party rulebooks, copied text, proprietary art, trademarks, or unlicensed
game assets.

No third-party code or asset may be imported without affirmative rights review.
A clean checkout must build, package, and run without access to quarantined
materials or external reference repositories.

Neverwinter Nights and Neverwinter Nights: Enhanced Edition are trademarks of
their respective owners. Their use here is solely to identify platform
compatibility. No affiliation, endorsement, or license is implied.

## License

Original software in this repository is licensed under the
[PolyForm Noncommercial License 1.0.0](LICENSE).
Copyright and attribution notices are in [NOTICE](NOTICE).
