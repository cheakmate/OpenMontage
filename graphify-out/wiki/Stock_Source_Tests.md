# Stock Source Tests

> 46 nodes · cohesion 0.06

## Key Concepts

- **test_stock_source_adapters.py** (27 connections) — `tests/tools/test_stock_source_adapters.py`
- **unsplash.py** (14 connections) — `tools/video/stock_sources/unsplash.py`
- **_build_search_queries()** (9 connections) — `tools/video/stock_sources/wikimedia.py`
- **UnsplashSource** (8 connections) — `tools/video/stock_sources/unsplash.py`
- **_EmptyOkResponse** (7 connections) — `tests/tools/test_stock_source_adapters.py`
- **_EmptySoup** (7 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_search_propagates_transport_errors()** (7 connections) — `tests/tools/test_stock_source_adapters.py`
- **_photo_to_candidate()** (7 connections) — `tools/video/stock_sources/unsplash.py`
- **test_search_returns_empty_when_the_source_has_no_results()** (6 connections) — `tests/tools/test_stock_source_adapters.py`
- **.search()** (6 connections) — `tools/video/stock_sources/unsplash.py`
- **_install_fake_transport()** (5 connections) — `tests/tools/test_stock_source_adapters.py`
- **TransportError** (4 connections) — `tests/tools/test_stock_source_adapters.py`
- **_build_download_url()** (4 connections) — `tools/video/stock_sources/unsplash.py`
- **_orientation_for_unsplash()** (4 connections) — `tools/video/stock_sources/unsplash.py`
- **.download()** (4 connections) — `tools/video/stock_sources/unsplash.py`
- **_adapter_names()** (3 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_unsplash_helpers_preserve_query_params()** (3 connections) — `tests/tools/test_stock_source_adapters.py`
- **_transport_error_params()** (3 connections) — `tests/tools/test_stock_source_adapters.py`
- **boom()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_wikimedia_cascade_falls_back_on_multi_word()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_wikimedia_cascade_strips_source_hints_and_years()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_wikimedia_search_query_respects_kind()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **_matches_orientation()** (2 connections) — `tools/video/stock_sources/unsplash.py`
- **._headers()** (2 connections) — `tools/video/stock_sources/unsplash.py`
- **parametrize** (2 connections)
- *... and 21 more nodes in this community*

## Relationships

- [Media Source Adapters](Media_Source_Adapters.md) (13 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (7 shared connections)
- [Wikimedia Media Adapter](Wikimedia_Media_Adapter.md) (7 shared connections)
- [Project Init](Project_Init.md) (3 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Core Utilities](Core_Utilities.md) (2 shared connections)
- [Cinematic Scene Types](Cinematic_Scene_Types.md) (1 shared connections)
- [Pexels Source Adapter](Pexels_Source_Adapter.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)

## Source Files

- `tests/tools/test_stock_source_adapters.py`
- `tools/video/stock_sources/unsplash.py`
- `tools/video/stock_sources/wikimedia.py`

## Audit Trail

- EXTRACTED: 95 (95%)
- INFERRED: 5 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*