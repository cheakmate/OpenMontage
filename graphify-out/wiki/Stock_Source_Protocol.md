# Stock Source Protocol

> 26 nodes · cohesion 0.12

## Key Concepts

- **stock_sources/__init__.py** (19 connections) — `tools/video/stock_sources/__init__.py`
- **all_sources()** (15 connections) — `tools/video/stock_sources/__init__.py`
- **get_source()** (11 connections) — `tools/video/stock_sources/__init__.py`
- **StockSource** (10 connections) — `tools/video/stock_sources/base.py`
- **source_summary()** (9 connections) — `tools/video/stock_sources/__init__.py`
- **source_catalog()** (8 connections) — `tools/video/stock_sources/__init__.py`
- **_is_source_adapter_class()** (7 connections) — `tools/video/stock_sources/__init__.py`
- **_source_classes()** (7 connections) — `tools/video/stock_sources/__init__.py`
- **.get_info()** (5 connections) — `tools/video/direct_clip_search.py`
- **inspect** (5 connections)
- **.download()** (4 connections) — `tools/video/stock_sources/base.py`
- **.search()** (4 connections) — `tools/video/stock_sources/base.py`
- **importlib** (4 connections)
- **pkgutil** (3 connections)
- **test_stock_source_autodiscovery_includes_new_sources()** (2 connections) — `tests/tools/test_stock_source_adapters.py`
- **.is_available()** (2 connections) — `tools/video/stock_sources/base.py`
- **Protocol** (1 connections)
- **Path** (1 connections)
- **Protocol every stock source adapter must satisfy. Attributes ---------- name:…** (1 connections) — `tools/video/stock_sources/base.py`
- **Stock media source adapters. Unified-protocol wrappers around free stock APIs…** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Summarize source availability for preflight and tool contracts.** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Look up a single adapter by its `name` attribute. Raises `KeyError` if no…** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Return True for concrete source adapters in this package.** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Auto-discover stock source classes under this package.** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Instantiate every registered adapter, whether available or not. Returned…** (1 connections) — `tools/video/stock_sources/__init__.py`
- *... and 1 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (13 shared connections)
- [Stock Media Search](Stock_Media_Search.md) (7 shared connections)
- [Stock Adapter Tests](Stock_Adapter_Tests.md) (7 shared connections)
- [Download Timeout Regression](Download_Timeout_Regression.md) (4 shared connections)
- [Documentary Governance Tests](Documentary_Governance_Tests.md) (4 shared connections)
- [Source Adapter Availability](Source_Adapter_Availability.md) (3 shared connections)
- [Clip Corpus](Clip_Corpus.md) (3 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (1 shared connections)
- [Corpus Path Safety](Corpus_Path_Safety.md) (1 shared connections)
- [Corpus Builder Failure Tests](Corpus_Builder_Failure_Tests.md) (1 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (1 shared connections)

## Source Files

- `tests/tools/test_stock_source_adapters.py`
- `tools/video/direct_clip_search.py`
- `tools/video/stock_sources/__init__.py`
- `tools/video/stock_sources/base.py`

## Audit Trail

- EXTRACTED: 79 (93%)
- INFERRED: 6 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*