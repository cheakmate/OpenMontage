# Asset Cache Tests

> 10 nodes · cohesion 0.31

## Key Concepts

- **AssetCacheEntry** (12 connections) — `lib/asset_cache.py`
- **test_manifest_tolerates_corrupt_lines()** (7 connections) — `tests/lib/test_asset_cache.py`
- **.from_dict()** (5 connections) — `lib/asset_cache.py`
- **Any** (5 connections)
- **._evict_to_fit_locked()** (4 connections) — `lib/asset_cache.py`
- **.to_dict()** (4 connections) — `lib/asset_cache.py`
- **test_entry_round_trip_through_dict()** (4 connections) — `tests/lib/test_asset_cache.py`
- **test_entry_from_dict_tolerates_missing_and_bad_fields()** (3 connections) — `tests/lib/test_asset_cache.py`
- **One row in the cache manifest. ``key`` is the content hash the tool computed.…** (1 connections) — `lib/asset_cache.py`
- **Evict least-recently-accessed entries until ``needed_bytes`` fits. Mutates…** (1 connections) — `lib/asset_cache.py`

## Relationships

- [Asset Cache System](Asset_Cache_System.md) (12 shared connections)
- [File Lock Cache](File_Lock_Cache.md) (5 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)

## Source Files

- `lib/asset_cache.py`
- `tests/lib/test_asset_cache.py`

## Audit Trail

- EXTRACTED: 28 (88%)
- INFERRED: 4 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*