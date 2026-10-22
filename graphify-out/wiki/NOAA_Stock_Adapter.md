# NOAA Stock Adapter

> 8 nodes · cohesion 0.32

## Key Concepts

- **NOAASource** (8 connections) — `tools/video/stock_sources/noaa.py`
- **.download()** (5 connections) — `tools/video/stock_sources/noaa.py`
- **.search()** (3 connections) — `tools/video/stock_sources/noaa.py`
- **._stream_download()** (3 connections) — `tools/video/stock_sources/noaa.py`
- **Path** (2 connections)
- **.is_available()** (1 connections) — `tools/video/stock_sources/noaa.py`
- **Download by resolving the detail page for the actual file URL.** (1 connections) — `tools/video/stock_sources/noaa.py`
- **NOAA ocean and atmospheric multimedia adapter. Satisfies `StockSource`.** (1 connections) — `tools/video/stock_sources/noaa.py`

## Relationships

- [Stock Media Search](Stock_Media_Search.md) (6 shared connections)

## Source Files

- `tools/video/stock_sources/noaa.py`

## Audit Trail

- EXTRACTED: 13 (87%)
- INFERRED: 2 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*