# Asset Cache Wrapper

> 22 nodes · cohesion 0.10

## Key Concepts

- **Any** (11 connections)
- **get_default_asset_cache()** (10 connections) — `lib/asset_cache.py`
- **_fingerprint_value()** (7 connections) — `tools/base_tool.py`
- **wrapper()** (6 connections) — `tools/base_tool.py`
- **.cache_key()** (5 connections) — `tools/base_tool.py`
- **.estimate_cost()** (5 connections) — `tools/base_tool.py`
- **.estimate_runtime()** (5 connections) — `tools/base_tool.py`
- **_hash_file()** (5 connections) — `tools/base_tool.py`
- **.execute()** (4 connections) — `tools/base_tool.py`
- **.idempotency_key()** (4 connections) — `tools/base_tool.py`
- **_is_cacheable()** (4 connections) — `tools/base_tool.py`
- **test_identical_call_is_served_from_cache()** (3 connections) — `tests/tools/test_base_tool_cache.py`
- **Path** (2 connections)
- **Return a process-level default ``AssetCache`` at the resolved path. Lazily…** (1 connections) — `lib/asset_cache.py`
- **SHA-256 of a file's bytes, read in chunks. None if it can't be read.** (1 connections) — `tools/base_tool.py`
- **Make one cache-key value content-addressed. A value that points at an existing…** (1 connections) — `tools/base_tool.py`
- **Whether a call may be served from / written to the asset cache. Cache only…** (1 connections) — `tools/base_tool.py`
- **Estimate cost in USD for the given inputs. Override for paid tools.** (1 connections) — `tools/base_tool.py`
- **Estimate runtime in seconds. Override for long-running tools.** (1 connections) — `tools/base_tool.py`
- **Compute a cache key from idempotency fields.** (1 connections) — `tools/base_tool.py`
- **Content-addressed key for this call, used by the asset cache. Combines tool…** (1 connections) — `tools/base_tool.py`
- **Run the tool. Subclasses must implement this.** (1 connections) — `tools/base_tool.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (9 shared connections)
- [File Lock Cache](File_Lock_Cache.md) (4 shared connections)
- [Event Stream](Event_Stream.md) (3 shared connections)
- [Tool Cache Tests](Tool_Cache_Tests.md) (3 shared connections)
- [Kling Avatar Tool](Kling_Avatar_Tool.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Clip Preflight](Clip_Preflight.md) (2 shared connections)
- [Asset Cache System](Asset_Cache_System.md) (1 shared connections)
- [Fish Audio TTS](Fish_Audio_TTS.md) (1 shared connections)
- [Three.js Asset Catalog](Three.js_Asset_Catalog.md) (1 shared connections)
- [Image Selector](Image_Selector.md) (1 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (1 shared connections)

## Source Files

- `lib/asset_cache.py`
- `tests/tools/test_base_tool_cache.py`
- `tools/base_tool.py`

## Audit Trail

- EXTRACTED: 56 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*