# Development Guidelines

## Error Handling

Never use hedging try/except blocks except for clearly expected errors. Prefer letting errors surface in the log rather than silently falling
back to mock data or hiding failures.

Hedging try/catch patterns to avoid:
- Catching API failures and falling back to mock data
- Catching errors just to log warnings and continue with fallback behavior
- Generic catch-all blocks that hide the real cause of issues

When errors are expected (like network timeouts), handle them explicitly and ensure they're properly logged for debugging.
