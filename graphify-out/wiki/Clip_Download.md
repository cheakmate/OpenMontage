# Clip Download

> 12 nodes · cohesion 0.17

## Key Concepts

- **.clip_id()** (8 connections) — `tools/video/stock_sources/base.py`
- **.download()** (5 connections) — `tools/video/stock_sources/archive_org.py`
- **.download()** (5 connections) — `tools/video/stock_sources/pexels.py`
- **.download()** (4 connections) — `tools/video/stock_sources/unsplash.py`
- **.download()** (4 connections) — `tools/video/stock_sources/wikimedia.py`
- **Path** (1 connections)
- **Path** (1 connections)
- **Path** (1 connections)
- **Path** (1 connections)
- **Stream the candidate's file to `out_path`. Same pattern as the Pexels adapter —…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Stable ID used as the corpus row key. Format is ``"<source>_<source_id>"``.…** (1 connections) — `tools/video/stock_sources/base.py`
- **Stream the candidate's file to `out_path`. Creates parent directories as…** (1 connections) — `tools/video/stock_sources/pexels.py`

## Relationships

- [Stock Media Search](Stock_Media_Search.md) (5 shared connections)
- [Clip Corpus](Clip_Corpus.md) (1 shared connections)
- [NASA Media Adapter](NASA_Media_Adapter.md) (1 shared connections)
- [Archive.org Stock Adapter](Archive.org_Stock_Adapter.md) (1 shared connections)
- [Pexels Media Adapter](Pexels_Media_Adapter.md) (1 shared connections)
- [Unsplash Photo Adapter](Unsplash_Photo_Adapter.md) (1 shared connections)
- [Stock Adapter Tests](Stock_Adapter_Tests.md) (1 shared connections)

## Source Files

- `tools/video/stock_sources/archive_org.py`
- `tools/video/stock_sources/base.py`
- `tools/video/stock_sources/pexels.py`
- `tools/video/stock_sources/unsplash.py`
- `tools/video/stock_sources/wikimedia.py`

## Audit Trail

- EXTRACTED: 16 (73%)
- INFERRED: 6 (27%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*