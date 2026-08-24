# Beyond F1-Scores: Zero-Trust Brain Tumor AI

**"Can we trust an AI prediction—not just measure its accuracy?"**

## Architecture
```mermaid
graph TD
  A[MRI INPUT] --> B[PROVENANCE CHECK]
  B --> C[STATISTICAL DEFENSE]
  C --> D[MODEL INTEGRITY SHA-256]
  D --> E[RBAC / mTLS GATEWAY]
  E --> F[EfficientNetB0 Inference]
  F --> G[HASH-LINKED AUDIT]
```

## Performance & Security Matrix
| Metric | Value |
|---|---|
| Validation Accuracy | 0.9524 |
| Model Integrity | PASS |
| mTLS / RBAC | VALIDATED |
| Trust Score | 100/100 |

*Note: Model weights and raw data excluded for security.*
