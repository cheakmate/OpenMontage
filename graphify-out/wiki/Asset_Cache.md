# Asset Cache

> 30 nodes · cohesion 0.15

## Key Concepts

- **AssetCache** (24 connections) — `lib/asset_cache.py`
- **.store()** (19 connections) — `lib/asset_cache.py`
- **.try_restore()** (15 connections) — `lib/asset_cache.py`
- **_fake_asset()** (13 connections) — `tests/lib/test_asset_cache.py`
- **._read_manifest()** (11 connections) — `lib/asset_cache.py`
- **.stats()** (6 connections) — `lib/asset_cache.py`
- **test_lru_eviction_evicts_oldest_first()** (6 connections) — `tests/lib/test_asset_cache.py`
- **test_manifest_drift_prunes_and_misses()** (6 connections) — `tests/lib/test_asset_cache.py`
- **test_same_key_restores_to_any_output_path()** (6 connections) — `tests/lib/test_asset_cache.py`
- **test_stats_reports_state_and_counters()** (6 connections) — `tests/lib/test_asset_cache.py`
- **._locked()** (5 connections) — `lib/asset_cache.py`
- **._write_manifest()** (5 connections) — `lib/asset_cache.py`
- **test_restored_blob_is_immutable_when_destination_overwritten()** (5 connections) — `tests/lib/test_asset_cache.py`
- **test_store_same_key_twice_keeps_single_entry()** (5 connections) — `tests/lib/test_asset_cache.py`
- **test_store_then_restore_round_trip()** (5 connections) — `tests/lib/test_asset_cache.py`
- **._evict_to_fit_locked()** (4 connections) — `lib/asset_cache.py`
- **test_store_source_rewrite_does_not_mutate_blob()** (4 connections) — `tests/lib/test_asset_cache.py`
- **test_manifest_survives_process_boundary()** (3 connections) — `tests/lib/test_asset_cache.py`
- **test_miss_on_empty_cache()** (3 connections) — `tests/lib/test_asset_cache.py`
- **test_store_rejects_missing_source()** (3 connections) — `tests/lib/test_asset_cache.py`
- **Path** (1 connections)
- **Process-safe, LRU-evicted, content-addressed cache of tool outputs. Not a…** (1 connections) — `lib/asset_cache.py`
- **Acquire an exclusive lock for the duration of the block. Prefers…** (1 connections) — `lib/asset_cache.py`
- **Read the manifest into a dict keyed by content key. Malformed lines are skipped…** (1 connections) — `lib/asset_cache.py`
- **Rewrite the manifest atomically via a sibling tmpfile + os.replace.** (1 connections) — `lib/asset_cache.py`
- *... and 5 more nodes in this community*

## Relationships

- [Asset Cache](Asset_Cache.md) (19 shared connections)
- [Asset Cache Entries](Asset_Cache_Entries.md) (11 shared connections)
- [Default Asset Cache](Default_Asset_Cache.md) (1 shared connections)
- [Asset Cache Modules](Asset_Cache_Modules.md) (1 shared connections)

## Source Files

- `lib/asset_cache.py`
- `tests/lib/test_asset_cache.py`

## Audit Trail

- EXTRACTED: 77 (79%)
- INFERRED: 21 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*