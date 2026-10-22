# Default Asset Cache

> 8 nodes · cohesion 0.25

## Key Concepts

- **get_default_asset_cache()** (10 connections) — `lib/asset_cache.py`
- **reset_default_asset_cache()** (7 connections) — `lib/asset_cache.py`
- **cache_on()** (3 connections) — `tests/tools/test_base_tool_cache.py`
- **test_get_default_asset_cache_honors_env_and_is_singleton()** (3 connections) — `tests/lib/test_asset_cache.py`
- **test_disabled_by_default_does_not_cache()** (3 connections) — `tests/tools/test_base_tool_cache.py`
- **fixture** (1 connections)
- **Return a process-level default ``AssetCache`` at the resolved path. Lazily…** (1 connections) — `lib/asset_cache.py`
- **Drop the cached singleton so the next accessor re-reads env vars. Useful for…** (1 connections) — `lib/asset_cache.py`

## Relationships

- [Base Tool Cache Tests](Base_Tool_Cache_Tests.md) (6 shared connections)
- [Asset Cache](Asset_Cache.md) (4 shared connections)
- [Asset Cache Modules](Asset_Cache_Modules.md) (2 shared connections)
- [Event Logging](Event_Logging.md) (1 shared connections)
- [Idempotency Cache Wrapper](Idempotency_Cache_Wrapper.md) (1 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (1 shared connections)

## Source Files

- `lib/asset_cache.py`
- `tests/lib/test_asset_cache.py`
- `tests/tools/test_base_tool_cache.py`

## Audit Trail

- EXTRACTED: 22 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*