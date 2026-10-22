# Stock Source Protocol

> 21 nodes · cohesion 0.15

## Key Concepts

- **stock_sources/__init__.py** (19 connections) — `tools/video/stock_sources/__init__.py`
- **all_sources()** (15 connections) — `tools/video/stock_sources/__init__.py`
- **get_source()** (11 connections) — `tools/video/stock_sources/__init__.py`
- **StockSource** (10 connections) — `tools/video/stock_sources/base.py`
- **_is_source_adapter_class()** (7 connections) — `tools/video/stock_sources/__init__.py`
- **_source_classes()** (7 connections) — `tools/video/stock_sources/__init__.py`
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
- **Look up a single adapter by its `name` attribute. Raises `KeyError` if no…** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Return True for concrete source adapters in this package.** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Auto-discover stock source classes under this package.** (1 connections) — `tools/video/stock_sources/__init__.py`
- **Instantiate every registered adapter, whether available or not. Returned…** (1 connections) — `tools/video/stock_sources/__init__.py`

## Relationships

- [Tool Execution](Tool_Execution.md) (12 shared connections)
- [Media Source Adapters](Media_Source_Adapters.md) (7 shared connections)
- [Stock Source Tests](Stock_Source_Tests.md) (7 shared connections)
- [Streaming Tests](Streaming_Tests.md) (5 shared connections)
- [Corpus Indexing System](Corpus_Indexing_System.md) (2 shared connections)
- [Corpus Builder Testing](Corpus_Builder_Testing.md) (1 shared connections)
- [Corpus Builder Tests](Corpus_Builder_Tests.md) (1 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)

## Source Files

- `tests/tools/test_stock_source_adapters.py`
- `tools/video/stock_sources/__init__.py`
- `tools/video/stock_sources/base.py`

## Audit Trail

- EXTRACTED: 63 (91%)
- INFERRED: 6 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*