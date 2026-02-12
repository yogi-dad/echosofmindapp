# Architecture (High-Level)

Events (journal / check-in)
        ↓
Stats Aggregation Layer
        ↓
Deterministic Detectors
        ↓
Cooldown + Dedup Layer
        ↓
Signal Output
        ↓
Insight Layer (optional AI interpretation)

Core principles:

- Deterministic-first modeling
- Idempotent scheduled execution
- Framework-agnostic signal core
- AI layered above signal engine (never inside it)
