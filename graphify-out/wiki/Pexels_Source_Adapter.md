# Pexels Source Adapter

> 22 nodes · cohesion 0.12

## Key Concepts

- **PexelsSource** (10 connections) — `tools/video/stock_sources/pexels.py`
- **pexels.py** (10 connections) — `tools/video/stock_sources/pexels.py`
- **.clip_id()** (8 connections) — `tools/video/stock_sources/base.py`
- **._search_videos()** (7 connections) — `tools/video/stock_sources/pexels.py`
- **.search()** (6 connections) — `tools/video/stock_sources/pexels.py`
- **.download()** (5 connections) — `tools/video/stock_sources/archive_org.py`
- **.download()** (5 connections) — `tools/video/stock_sources/pexels.py`
- **._search_images()** (5 connections) — `tools/video/stock_sources/pexels.py`
- **._headers()** (3 connections) — `tools/video/stock_sources/pexels.py`
- **_pick_video_rendition()** (3 connections) — `tools/video/stock_sources/pexels.py`
- **_slug_tags_from_url()** (3 connections) — `tools/video/stock_sources/pexels.py`
- **.is_available()** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Path** (1 connections)
- **Path** (1 connections)
- **Stream the candidate's file to `out_path`. Same pattern as the Pexels adapter —…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Stable ID used as the corpus row key. Format is ``"<source>_<source_id>"``.…** (1 connections) — `tools/video/stock_sources/base.py`
- **Pexels stock media source adapter. Wraps the Pexels video and image search APIs…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Pick the largest mp4/mov rendition within [min_width, max_width]. Pexels…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Extract a readable tag string from a Pexels video landing URL. Pexels video…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Unified Pexels adapter for videos and images. Satisfies `StockSource`.…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Search Pexels, routing to video/image endpoints by `filters.kind`.…** (1 connections) — `tools/video/stock_sources/pexels.py`
- **Stream the candidate's file to `out_path`. Creates parent directories as…** (1 connections) — `tools/video/stock_sources/pexels.py`

## Relationships

- [Media Source Adapters](Media_Source_Adapters.md) (14 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Corpus Indexing System](Corpus_Indexing_System.md) (1 shared connections)
- [NASA Image Source](NASA_Image_Source.md) (1 shared connections)
- [Stock Source Tests](Stock_Source_Tests.md) (1 shared connections)
- [Wikimedia Media Adapter](Wikimedia_Media_Adapter.md) (1 shared connections)
- [Archive.org Source](Archive.org_Source.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)

## Source Files

- `tools/video/stock_sources/archive_org.py`
- `tools/video/stock_sources/base.py`
- `tools/video/stock_sources/pexels.py`

## Audit Trail

- EXTRACTED: 41 (84%)
- INFERRED: 8 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*