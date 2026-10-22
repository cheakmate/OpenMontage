# Clip Cache

> 77 nodes · cohesion 0.07

## Key Concepts

- **test_clip_cache.py** (41 connections) — `tests/tools/test_clip_cache.py`
- **ClipCache** (28 connections) — `tools/video/clip_cache.py`
- **.ingest()** (25 connections) — `tools/video/clip_cache.py`
- **clip_cache.py** (21 connections) — `tools/video/clip_cache.py`
- **_fake_clip()** (19 connections) — `tests/tools/test_clip_cache.py`
- **.try_link()** (19 connections) — `tools/video/clip_cache.py`
- **._read_manifest()** (16 connections) — `tools/video/clip_cache.py`
- **CacheEntry** (13 connections) — `tools/video/clip_cache.py`
- **_default_metadata()** (12 connections) — `tests/tools/test_clip_cache.py`
- **test_manifest_prunes_traversal_entries()** (9 connections) — `tests/tools/test_clip_cache.py`
- **test_manifest_drift_falls_back_to_miss()** (8 connections) — `tests/tools/test_clip_cache.py`
- **test_try_link_falls_back_to_copy_and_still_bumps_access()** (8 connections) — `tests/tools/test_clip_cache.py`
- **get_default_cache()** (8 connections) — `tools/video/clip_cache.py`
- **_link_or_copy()** (8 connections) — `tools/video/clip_cache.py`
- **test_lru_eviction_evicts_oldest_first()** (7 connections) — `tests/tools/test_clip_cache.py`
- **test_manifest_survives_process_boundary()** (7 connections) — `tests/tools/test_clip_cache.py`
- **test_stats_reports_cache_state_and_session_counters()** (7 connections) — `tests/tools/test_clip_cache.py`
- **default_cache_dir()** (7 connections) — `tools/video/clip_cache.py`
- **_safe_blob_path()** (7 connections) — `tools/video/clip_cache.py`
- **test_cache_hit_is_a_hard_link_not_a_copy_when_possible()** (6 connections) — `tests/tools/test_clip_cache.py`
- **test_eviction_multiple_victims_when_single_clip_is_large()** (6 connections) — `tests/tools/test_clip_cache.py`
- **test_ingest_rejects_path_traversal_clip_id()** (6 connections) — `tests/tools/test_clip_cache.py`
- **test_ingest_same_clip_twice_bumps_last_access()** (6 connections) — `tests/tools/test_clip_cache.py`
- **test_ingest_then_hit_round_trip()** (6 connections) — `tests/tools/test_clip_cache.py`
- **test_link_or_copy_returns_false_when_both_fail()** (6 connections) — `tests/tools/test_clip_cache.py`
- *... and 52 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Corpus Indexing System](Corpus_Indexing_System.md) (1 shared connections)
- [Tool Execution](Tool_Execution.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [File Lock Cache](File_Lock_Cache.md) (1 shared connections)
- [Delivery Promise Classifier](Delivery_Promise_Classifier.md) (1 shared connections)

## Source Files

- `tests/tools/test_clip_cache.py`
- `tools/video/clip_cache.py`

## Audit Trail

- EXTRACTED: 189 (83%)
- INFERRED: 39 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*