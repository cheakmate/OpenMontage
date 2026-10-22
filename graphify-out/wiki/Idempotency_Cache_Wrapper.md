# Idempotency Cache Wrapper

> 21 nodes · cohesion 0.11

## Key Concepts

- **.dry_run()** (11 connections) — `tools/base_tool.py`
- **Any** (11 connections)
- **_fingerprint_value()** (7 connections) — `tools/base_tool.py`
- **wrapper()** (6 connections) — `tools/base_tool.py`
- **.cache_key()** (5 connections) — `tools/base_tool.py`
- **.estimate_cost()** (5 connections) — `tools/base_tool.py`
- **.estimate_runtime()** (5 connections) — `tools/base_tool.py`
- **_hash_file()** (5 connections) — `tools/base_tool.py`
- **.execute()** (4 connections) — `tools/base_tool.py`
- **.idempotency_key()** (4 connections) — `tools/base_tool.py`
- **_is_cacheable()** (4 connections) — `tools/base_tool.py`
- **Path** (2 connections)
- **SHA-256 of a file's bytes, read in chunks. None if it can't be read.** (1 connections) — `tools/base_tool.py`
- **Make one cache-key value content-addressed. A value that points at an existing…** (1 connections) — `tools/base_tool.py`
- **Whether a call may be served from / written to the asset cache. Cache only…** (1 connections) — `tools/base_tool.py`
- **Estimate cost in USD for the given inputs. Override for paid tools.** (1 connections) — `tools/base_tool.py`
- **Estimate runtime in seconds. Override for long-running tools.** (1 connections) — `tools/base_tool.py`
- **Compute a cache key from idempotency fields.** (1 connections) — `tools/base_tool.py`
- **Content-addressed key for this call, used by the asset cache. Combines tool…** (1 connections) — `tools/base_tool.py`
- **Run the tool. Subclasses must implement this.** (1 connections) — `tools/base_tool.py`
- **Preflight check without side effects. Override for paid/publishing tools.** (1 connections) — `tools/base_tool.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (9 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (2 shared connections)
- [Clip Concatenation](Clip_Concatenation.md) (2 shared connections)
- [Event Logging](Event_Logging.md) (2 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (1 shared connections)
- [Kling Avatar LipSync Tests](Kling_Avatar_LipSync_Tests.md) (1 shared connections)
- [Kling LipSync Implementation](Kling_LipSync_Implementation.md) (1 shared connections)
- [Kling Image Provider Tests](Kling_Image_Provider_Tests.md) (1 shared connections)
- [Kling Video Tests](Kling_Video_Tests.md) (1 shared connections)
- [Fish Audio TTS Tests](Fish_Audio_TTS_Tests.md) (1 shared connections)
- [Asset Cache](Asset_Cache.md) (1 shared connections)

## Source Files

- `tools/base_tool.py`

## Audit Trail

- EXTRACTED: 53 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*