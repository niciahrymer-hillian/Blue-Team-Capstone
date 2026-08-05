# Blue-Team-Capstone

### The defender's capstone: logging, detection rules, alert triage, and a written incident-response runbook.

![Chain L](https://img.shields.io/badge/Chain%20L-DC2626?style=for-the-badge) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](LICENSE-GPL) [![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue?style=for-the-badge)](LICENSE-AGPL)

[📖 Lesson Plan](docs/LESSON_PLAN.md)

<!-- SCREENSHOT PLACEHOLDER: docs/screenshots/overview.png -->

> ⬜ **Scaffold pending.** Directory created to portfolio standard; full content (README, lesson plan, tour + quiz, skeleton code) still to be built. Part of **Chain L — Cybersecurity (Simulation Only)**.

## Why This Was Built

This is where Chain L comes together on the side I care about — defending. Detection begins with logging
the right things, turns into rules that fire on meaningful patterns, and ends with a human deciding whether
an alert matters.

The part I most want to get right is the **runbook**. During an incident nobody is thinking clearly, so the
value is in having written down beforehand what to check, who to contact, how to contain, and what to
preserve for later analysis. That document is the actual deliverable.

## Why This Matters (Industry Application)

Blue-team work — SOC analysis, detection engineering, incident response — is where most security hiring
is, and it's chronically understaffed. Alert fatigue from noisy, poorly-tuned rules is the field's defining
practical problem, so learning to write rules that signal rather than spam is directly valuable.

## Topics Covered

| Area | What this project covers |
|------|--------------------------|
| Logging | Deciding what to log, and retaining it usefully |
| Detection rules | Writing rules that fire on real signal |
| Triage | Prioritizing alerts and cutting false-positive noise |
| Incident response | Contain, eradicate, recover — in that order |
| Runbooks | Written procedures for when nobody is thinking clearly |
| Post-incident | Blameless review and closing the gap that allowed it |

## How This Connects

Chain L (Cybersecurity — Simulation Only). The capstone for Chain L; consumes **Anatomy-Of-An-Attack-Lab** and **Web-App-Security-Defensive**.

---
Dual licensed — [GPL v3](LICENSE-GPL) and [AGPL v3](LICENSE-AGPL).
