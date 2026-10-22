# Stock Adapter Tests

> 46 nodes · cohesion 0.06

## Key Concepts

- **test_stock_source_adapters.py** (27 connections) — `tests/tools/test_stock_source_adapters.py`
- **wikimedia.py** (16 connections) — `tools/video/stock_sources/wikimedia.py`
- **_build_search_queries()** (9 connections) — `tools/video/stock_sources/wikimedia.py`
- **_page_to_candidate()** (8 connections) — `tools/video/stock_sources/wikimedia.py`
- **_EmptyOkResponse** (7 connections) — `tests/tools/test_stock_source_adapters.py`
- **_EmptySoup** (7 connections) — `tests/tools/test_stock_source_adapters.py`
- **WikimediaSource** (7 connections) — `tools/video/stock_sources/wikimedia.py`
- **test_search_propagates_transport_errors()** (7 connections) — `tests/tools/test_stock_source_adapters.py`
- **_meta_value()** (7 connections) — `tools/video/stock_sources/wikimedia.py`
- **test_search_returns_empty_when_the_source_has_no_results()** (6 connections) — `tests/tools/test_stock_source_adapters.py`
- **.search()** (6 connections) — `tools/video/stock_sources/wikimedia.py`
- **_install_fake_transport()** (5 connections) — `tests/tools/test_stock_source_adapters.py`
- **TransportError** (4 connections) — `tests/tools/test_stock_source_adapters.py`
- **_kind_from_mime()** (4 connections) — `tools/video/stock_sources/wikimedia.py`
- **_adapter_names()** (3 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_wikimedia_kind_and_metadata_helpers()** (3 connections) — `tests/tools/test_stock_source_adapters.py`
- **_transport_error_params()** (3 connections) — `tests/tools/test_stock_source_adapters.py`
- **html** (3 connections)
- **boom()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_wikimedia_cascade_falls_back_on_multi_word()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_wikimedia_cascade_strips_source_hints_and_years()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **test_wikimedia_search_query_respects_kind()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **_looks_like_year()** (2 connections) — `tools/video/stock_sources/wikimedia.py`
- **_matches_orientation()** (2 connections) — `tools/video/stock_sources/wikimedia.py`
- **parametrize** (2 connections)
- *... and 21 more nodes in this community*

## Relationships

- [Stock Media Search](Stock_Media_Search.md) (12 shared connections)
- [Stock Source Protocol](Stock_Source_Protocol.md) (7 shared connections)
- [Unsplash Photo Adapter](Unsplash_Photo_Adapter.md) (4 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (3 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (3 shared connections)
- [Atelier Project Scaffolding](Atelier_Project_Scaffolding.md) (2 shared connections)
- [Clip Download](Clip_Download.md) (1 shared connections)
- [Cinematic Scene Types](Cinematic_Scene_Types.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)

## Source Files

- `tests/tools/test_stock_source_adapters.py`
- `tools/video/stock_sources/wikimedia.py`

## Audit Trail

- EXTRACTED: 97 (96%)
- INFERRED: 4 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*