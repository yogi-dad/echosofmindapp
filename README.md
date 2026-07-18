# Echos of Mind

Echos of Mind starts as structured capture and turns into something closer to a behavioral mirror: a system that notices what repeats in someone's signals over time, instead of just logging them.

No streaks. No engagement mechanics. No ads.

## What's in this repository

This repo covers the product direction, architecture, and modeling philosophy behind Echos of Mind. The deterministic signal core is public. The adaptive calibration layer that personalizes per user stays proprietary and evolves separately.

## What exists today

- Deterministic behavioral signal engine
- Rolling window pattern detection (24h / 7d / 30d)
- Cooldown and dedup enforcement so the same signal doesn't get flagged twice
- Production-ready backend architecture blueprint

Related repositories: `behavioral-signal-engine`, `production-backend-blueprint`

## Where this is going

Echos of Mind begins as structured journaling. Over time it becomes a system where baselines adapt per user, signal fatigue gets reduced, detection sensitivity refines the longer someone uses it, and insight gets deeper without asking for more input.

Long term: behavioral infrastructure built on deterministic foundations, not black-box inference.

See `VISION.md`, `ARCHITECTURE.md`, `ROADMAP.md`, `METRICS.md`, `SECURITY.md`, `PRIVACY.md` for the detail behind each of these.

## Revenue

Revenue has to track with depth of insight, not emotional exploitation. Future models may include premium adaptive calibration, longitudinal behavioral reports, and institutional behavioral infrastructure further out. No ads, no engagement manipulation, ever.

## Early-stage target

1,000 real active users within 18 months. Active is defined as three or more meaningful entries a month, sustained for three months or longer. Full definition in `METRICS.md`.

## Core philosophy

Clarity compounds when behavior gets structured over time. That means deterministic modeling before any AI layering, privacy-first data handling by default, an architecture people can actually audit, and long-term signal stability over short-term novelty.

