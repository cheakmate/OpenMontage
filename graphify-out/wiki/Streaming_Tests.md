# Streaming Tests

> 35 nodes · cohesion 0.07

## Key Concepts

- **.execute()** (14 connections) — `tools/video/direct_clip_search.py`
- **test_direct_clip_search_times_out_streaming_download()** (10 connections) — `tests/tools/test_documentary_governance.py`
- **source_summary()** (9 connections) — `tools/video/stock_sources/__init__.py`
- **source_catalog()** (8 connections) — `tools/video/stock_sources/__init__.py`
- **_extract_mid_thumbnail()** (7 connections) — `tools/video/direct_clip_search.py`
- **remaining_seconds()** (7 connections) — `tools/video/direct_clip_search.py`
- **.get_info()** (6 connections) — `tools/video/corpus_builder.py`
- **.get_info()** (5 connections) — `tools/video/direct_clip_search.py`
- **get_with_deadline()** (5 connections) — `tools/video/direct_clip_search.py`
- **_DeadlineExceeded** (4 connections) — `tools/video/direct_clip_search.py`
- **_requests_deadline()** (4 connections) — `tools/video/direct_clip_search.py`
- **Any** (4 connections)
- **_clamp_timeout()** (3 connections) — `tools/video/direct_clip_search.py`
- **_guess_ext()** (3 connections) — `tools/video/direct_clip_search.py`
- **Any** (3 connections)
- **iter_content()** (2 connections) — `tests/tools/test_documentary_governance.py`
- **search()** (2 connections) — `tests/tools/test_documentary_governance.py`
- **.estimate_cost()** (2 connections) — `tools/video/corpus_builder.py`
- **.estimate_cost()** (2 connections) — `tools/video/direct_clip_search.py`
- **timeout_result()** (2 connections) — `tools/video/direct_clip_search.py`
- **iter_content_with_deadline()** (2 connections) — `tools/video/direct_clip_search.py`
- **download()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **__enter__()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **__exit__()** (1 connections) — `tests/tools/test_documentary_governance.py`
- **raise_for_status()** (1 connections) — `tests/tools/test_documentary_governance.py`
- *... and 10 more nodes in this community*

## Relationships

- [Tool Execution](Tool_Execution.md) (19 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (5 shared connections)
- [Media Source Adapters](Media_Source_Adapters.md) (3 shared connections)
- [Image Selector](Image_Selector.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Corpus Indexing System](Corpus_Indexing_System.md) (2 shared connections)
- [Audio Mixing](Audio_Mixing.md) (1 shared connections)

## Source Files

- `tests/tools/test_documentary_governance.py`
- `tools/video/corpus_builder.py`
- `tools/video/direct_clip_search.py`
- `tools/video/stock_sources/__init__.py`

## Audit Trail

- EXTRACTED: 73 (95%)
- INFERRED: 4 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*