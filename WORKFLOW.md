# Workflow

## High-level functional workflow
1. Upload or select document context
2. Choose guided or open analysis
3. Run retrieval-backed processing
4. Review grounded output
5. Refine or export next step

```mermaid
    flowchart TD
        S1["Upload or select document context"]
    S2["Choose guided or open analysis"]
    S3["Run retrieval-backed processing"]
    S4["Review grounded output"]
    S5["Refine or export next step"]
    S1 --> S2
    S2 --> S3
    S3 --> S4
    S4 --> S5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
