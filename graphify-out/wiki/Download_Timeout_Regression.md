# Download Timeout Regression

> 27 nodes · cohesion 0.09

## Key Concepts

- **.execute()** (14 connections) — `tools/video/direct_clip_search.py`
- **test_direct_clip_search_times_out_streaming_download()** (10 connections) — `tests/tools/test_documentary_governance.py`
- **_extract_mid_thumbnail()** (7 connections) — `tools/video/direct_clip_search.py`
- **remaining_seconds()** (7 connections) — `tools/video/direct_clip_search.py`
- **get_with_deadline()** (5 connections) — `tools/video/direct_clip_search.py`
- **_DeadlineExceeded** (4 connections) — `tools/video/direct_clip_search.py`
- **_requests_deadline()** (4 connections) — `tools/video/direct_clip_search.py`
- **Any** (4 connections)
- **_clamp_timeout()** (3 connections) — `tools/video/direct_clip_search.py`
- **_guess_ext()** (3 connections) — `tools/video/direct_clip_search.py`
- **iter_content()** (2 connections) — `tests/tools/test_documentary_governance.py`
- **search()** (2 connections) — `tests/tools/test_documentary_governance.py`
- **.estimate_cost()** (2 connections) — `tools/video/direct_clip_search.py`
- **timeout_result()** (2 connections) — `tools/video/direct_clip_search.py`
- **iter_content_with_deadline()** (2 connections) — `tools/video/direct_clip_search.py`
- **download()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **__enter__()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **__exit__()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **raise_for_status()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **timed_out()** (1 connections) — `tools/video/direct_clip_search.py`
- **TimeoutError** (1 connections)
- **Path** (1 connections)
- **F-13 regression: a streaming adapter download must not run past the tool-level…** (1 connections) — `tests/tools/test_documentary_governance.py`
- **Extract a sensible file extension from a candidate's URL.** (1 connections) — `tools/video/direct_clip_search.py`
- **Raised when the direct-clip-search wall-clock deadline is exhausted.** (1 connections) — `tools/video/direct_clip_search.py`
- *... and 2 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (11 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (4 shared connections)
- [Stock Media Search](Stock_Media_Search.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (1 shared connections)
- [Source Adapter Availability](Source_Adapter_Availability.md) (1 shared connections)
- [Environment Loader](Environment_Loader.md) (1 shared connections)

## Source Files

- `tests/tools/test_documentary_governance.py`
- `tools/video/direct_clip_search.py`

## Audit Trail

- EXTRACTED: 50 (94%)
- INFERRED: 3 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*