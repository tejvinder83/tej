# ServiceNow Code Review Prompt

Review the supplied ServiceNow implementation as a senior architect.

Prioritize findings by Critical, High, Medium and Low.

Review for:
- correctness and maintainability
- GlideRecord query selectivity and unnecessary database calls
- queries inside loops
- Business Rule recursion
- synchronous work that could create transaction latency
- Script Include boundaries and reuse
- hard-coded configuration or sys_ids
- scope and ACL assumptions
- REST timeout, error and retry behavior
- idempotency and duplicate processing
- logging quality and sensitive-data exposure
- bulk data handling and reconciliation

For every significant finding provide the location, why it matters, a safer pattern and how to test the correction.
