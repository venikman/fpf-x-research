## Search Parameter Analysis (Real Test Run - June 2026)

I ran all the recommended improved queries over the summer 2025+ window. Here's what actually worked:

### Best Performing Queries (by far)

1. `url:"ailev/FPF"` → **Extremely high precision**. Caught almost every real mention with almost zero noise.
2. `from:ailev (FPF OR "First Principles")` → Excellent for catching the author himself promoting/using his own tool.

### Good Supporting Queries
- `FPF (CharacteristicSpace OR CHRMechanismSuite OR "CN-Spec")` → Low volume but high relevance when it hits.
- `"First Principles Framework" (github OR spec OR ailev)` → Decent, surfaces some good context.

### Noisy / Lower Value
- `url:github.com FPF` → Catches many unrelated FPF repos (e.g. security tools, fuzzy search tools). Requires heavy filtering.

### Key Lesson
The single most effective daily query is:
**`url:"ailev/FPF" since:2025-06-01`**

It is dramatically cleaner than broad "FPF" searches while still capturing the real signal (people linking and recommending the actual implementation).

Recommendation: Make `url:"ailev/FPF"` the primary daily query, supplemented by the others.