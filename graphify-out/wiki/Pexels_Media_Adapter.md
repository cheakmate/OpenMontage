# Pexels Media Adapter

> 14 nodes · cohesion 0.21

## Key Concepts

- **PexelsSource** (10 connections) — `tools/video/stock_sources/pexels.py`
- **pexels.py** (10 connections) — `tools/video/stock_sources/pexels.py`
- **._search_videos()** (7 connections) — `tools/video/stock_sources/pexels.py`
- **.search()** (6 connections) — `tools/video/stock_sources/pexels.py`
- **._search_images()** (5 connections) — `tools/video/stock_sources/pexels.py`
- **._headers()** (3 connections) — `tools/video/stock_sources/pexels.py`
- **_pick_video_rendition()** (3 connections) — `tools/video/stock_sources/pexels.py`
- **_slug_tags_from_url()** (3 connections) — `tools/video/stock_sources/pexels.py`
- **.is_available()** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Pexels stock media source adapter. Wraps the Pexels video and image search APIs…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Pick the largest mp4/mov rendition within [min_width, max_width]. Pexels…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Extract a readable tag string from a Pexels video landing URL. Pexels video…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Unified Pexels adapter for videos and images. Satisfies `StockSource`.…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Search Pexels, routing to video/image endpoints by `filters.kind`.…** (1 connections) — `tools/video/stock_sources/pexels.py`

## Relationships

- [Stock Media Search](Stock_Media_Search.md) (11 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (3 shared connections)
- [Clip Download](Clip_Download.md) (1 shared connections)

## Source Files

- `tools/video/stock_sources/pexels.py`

## Audit Trail

- EXTRACTED: 32 (94%)
- INFERRED: 2 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*