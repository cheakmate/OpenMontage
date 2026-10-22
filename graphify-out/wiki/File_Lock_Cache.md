# File Lock Cache

> 26 nodes · cohesion 0.12

## Key Concepts

- **test_asset_cache.py** (36 connections) — `tests/lib/test_asset_cache.py`
- **asset_cache.py** (21 connections) — `lib/asset_cache.py`
- **asset_cache_enabled()** (8 connections) — `lib/asset_cache.py`
- **_copy_file()** (7 connections) — `lib/asset_cache.py`
- **default_asset_cache_dir()** (7 connections) — `lib/asset_cache.py`
- **reset_default_asset_cache()** (7 connections) — `lib/asset_cache.py`
- **default_max_total_bytes()** (5 connections) — `lib/asset_cache.py`
- **Path** (5 connections)
- **.__init__()** (4 connections) — `lib/asset_cache.py`
- **cache_on()** (3 connections) — `tests/tools/test_base_tool_cache.py`
- **test_copy_file_makes_independent_copy()** (3 connections) — `tests/lib/test_asset_cache.py`
- **test_get_default_asset_cache_honors_env_and_is_singleton()** (3 connections) — `tests/lib/test_asset_cache.py`
- **test_default_cache_dir_falls_back_to_home()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_default_cache_dir_uses_env_override()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_default_max_total_bytes_respects_and_guards_env()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_disabled_by_default()** (2 connections) — `tests/lib/test_asset_cache.py`
- **test_enabled_by_truthy_values()** (2 connections) — `tests/lib/test_asset_cache.py`
- **filelock** (2 connections)
- **fixture** (1 connections)
- **Content-addressed cache for reproducible tool outputs. Every paid generation…** (1 connections) — `lib/asset_cache.py`
- **Resolve the cache directory. Honors ``OPENMONTAGE_ASSET_CACHE_DIR`` if set,…** (1 connections) — `lib/asset_cache.py`
- **Resolve the max-cache-size budget. Honors ``OPENMONTAGE_ASSET_CACHE_MAX_GB``…** (1 connections) — `lib/asset_cache.py`
- **Copy ``src`` to ``dst`` as an independent file. True on success. Deliberately a…** (1 connections) — `lib/asset_cache.py`
- **Drop the cached singleton so the next accessor re-reads env vars. Useful for…** (1 connections) — `lib/asset_cache.py`
- **Whether the asset cache is active. Off by default. Honors…** (1 connections) — `lib/asset_cache.py`
- *... and 1 more nodes in this community*

## Relationships

- [Asset Cache System](Asset_Cache_System.md) (20 shared connections)
- [Core Utilities](Core_Utilities.md) (8 shared connections)
- [Asset Cache Tests](Asset_Cache_Tests.md) (5 shared connections)
- [Tool Cache Tests](Tool_Cache_Tests.md) (4 shared connections)
- [Asset Cache Wrapper](Asset_Cache_Wrapper.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Event Stream](Event_Stream.md) (1 shared connections)
- [Delivery Promise Classifier](Delivery_Promise_Classifier.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Clip Cache](Clip_Cache.md) (1 shared connections)

## Source Files

- `lib/asset_cache.py`
- `tests/lib/test_asset_cache.py`
- `tests/tools/test_base_tool_cache.py`

## Audit Trail

- EXTRACTED: 89 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*