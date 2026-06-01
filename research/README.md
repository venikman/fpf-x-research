## Search Strategy (Full Set - Run on Every Trigger)

**Important**: On every trigger (daily scheduled run **or** manual "Run daily FPF X research update"), the agent must run **all** of the following queries:

### High-Precision Queries (Primary)
- `url:"ailev/FPF" since:2025-06-01`
- `from:ailev (FPF OR "First Principles") since:2025-06-01`
- `FPF (CharacteristicSpace OR CHRMechanismSuite OR "CN-Spec") since:2025-06-01`

### Supporting Queries
- `"First Principles Framework" (github OR spec OR ailev) since:2025-06-01`
- `url:github.com FPF since:2025-06-01`

### Process After Running Queries
1. Collect all results from the above queries.
2. For every post, fetch the full thread.
3. **Manually verify** whether it is genuinely about the real FPF spec / https://github.com/ailev/FPF (filter out noise, unrelated FPF repos, general first-principles thinking, etc.).
4. Only record verified relevant posts in the research artifacts.
5. Update:
   - `research/daily/YYYY-MM-DD.md`
   - `research/timeline.md`
   - `research/key-posts.json`
   - `research/patterns.md` (if new patterns emerge)
6. Push all changes to the repo.

This "run all queries + strict manual verification" approach is the current standard operating procedure for this research.