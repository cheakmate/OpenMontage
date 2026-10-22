# Asset Cache

> 18 nodes · cohesion 0.17

## Key Concepts

- **test_asset_cache.py** (36 connections) — `tests/lib/test_asset_cache.py`
- **asset_cache_enabled()** (8 connections) — `lib/asset_cache.py`
- **_copy_file()** (7 connections) — `lib/asset_cache.py`
- **default_asset_cache_dir()** (7 connections) — `lib/asset_cache.py`
- **default_max_total_bytes()** (5 connections) — `lib/asset_cache.py`
- **Path** (5 connections)
- **.__init__()** (4 connections) — `lib/asset_cache.py`
- **test_copy_file_makes_independent_copy()** (3 connections) — `tests/lib/test_asset_cache.py`
- **test_default_cache_dir_falls_back_to_home()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_default_cache_dir_uses_env_override()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_default_max_total_bytes_respects_and_guards_env()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_disabled_by_default()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_enabled_by_truthy_values()** (2 connections) — `tests/lib/test_asset_cache.py`
- **Resolve the cache directory. Honors ``OPENMONTAGE_ASSET_CACHE_DIR`` if set,…** (1 connections) — `lib/asset_cache.py`
- **Resolve the max-cache-size budget. Honors ``OPENMONTAGE_ASSET_CACHE_MAX_GB``…** (1 connections) — `lib/asset_cache.py`
- **Copy ``src`` to ``dst`` as an independent file. True on success. Deliberately a…** (1 connections) — `lib/asset_cache.py`
- **Whether the asset cache is active. Off by default. Honors…** (1 connections) — `lib/asset_cache.py`
- **Tests for the content-addressed asset cache (lib/asset_cache.py). These do not…** (1 connections) — `tests/lib/test_asset_cache.py`

## Relationships

- [Asset Cache](Asset_Cache.md) (19 shared connections)
- [Asset Cache Modules](Asset_Cache_Modules.md) (5 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (4 shared connections)
- [Asset Cache Entries](Asset_Cache_Entries.md) (4 shared connections)
- [Default Asset Cache](Default_Asset_Cache.md) (3 shared connections)
- [Event Logging](Event_Logging.md) (1 shared connections)
- [Idempotency Cache Wrapper](Idempotency_Cache_Wrapper.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)

## Source Files

- `lib/asset_cache.py`
- `tests/lib/test_asset_cache.py`

## Audit Trail

- EXTRACTED: 64 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*