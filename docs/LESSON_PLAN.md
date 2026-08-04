# 📖 Lesson Plan — Blue-Team-Capstone

> **Chain L — Cybersecurity (Simulation Only)** | The defender's capstone: logging, detection rules, alert triage, and a written incident-response runbook.

## What This Project Is

The defender's capstone: decide what to log, write detection rules that signal rather than spam, triage alerts, and produce an incident-response runbook worth having at 3am.

> **Scope:** this lesson is **defensive and simulation-only**. It builds no offensive tooling and targets no real system. Everything is practised in an isolated environment against systems I own.

## Learning Objectives

By the end I can:

1. Decide what to log and how long to retain it.
2. Write detection rules that fire on meaningful signal.
3. Triage alerts by priority and reduce false-positive noise.
4. Execute contain → eradicate → recover in the correct order.
5. Write a **runbook** usable under pressure.
6. Run a blameless post-incident review.

## Software You Will Use

- An ELK stack, Wazuh, or Security Onion in a lab.
- Sample log data.
- A document for the runbook — the real deliverable.

## Build Order

1. Decide the logging strategy for a system you built.
2. Ingest logs into a searchable store.
3. Write detection rules for the stages from the attack lab.
4. Tune them against normal activity until noise is manageable.
5. Simulate an incident and work it end to end.
6. Write the runbook and the post-incident review.

## Common Mistakes to Avoid

- Alerting on everything until the team mutes the channel.
- Logs with no retention policy, or retained with no index.
- Eradicating before containing, and losing the evidence.
- A runbook nobody has rehearsed.
- Post-incident reviews that assign blame instead of fixing the system.

## Check Your Understanding

The quiz covers logging strategy, rule tuning, incident-response order, and runbook contents.

## Why This Matters (Industry Application)

Blue-team work — SOC analysis, detection engineering, incident response — is where most security hiring
is, and it's chronically understaffed. Alert fatigue from noisy, poorly-tuned rules is the field's defining
practical problem, so learning to write rules that signal rather than spam is directly valuable.

## Reflection Questions

- Could someone else run your runbook without you? Test it and find out.
- Which alert would you actually want waking you at 3am, and which absolutely not?
