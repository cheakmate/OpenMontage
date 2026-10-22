# NASA Media Adapter

> 20 nodes · cohesion 0.13

## Key Concepts

- **nasa.py** (14 connections) — `tools/video/stock_sources/nasa.py`
- **._hydrate_candidate()** (9 connections) — `tools/video/stock_sources/nasa.py`
- **NasaSource** (8 connections) — `tools/video/stock_sources/nasa.py`
- **.download()** (5 connections) — `tools/video/stock_sources/nasa.py`
- **.search()** (5 connections) — `tools/video/stock_sources/nasa.py`
- **_sanitize_source_id()** (4 connections) — `tools/video/stock_sources/nasa.py`
- **_encode_url_path()** (3 connections) — `tools/video/stock_sources/nasa.py`
- **_pick_image_url()** (3 connections) — `tools/video/stock_sources/nasa.py`
- **_pick_video_url()** (3 connections) — `tools/video/stock_sources/nasa.py`
- **.is_available()** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Path** (1 connections)
- **NASA Image and Video Library adapter. Wraps ``images-api.nasa.gov`` behind the…** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Stream the candidate's file to `out_path`. Same pattern as the other adapters.** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Turn a search-result item into a Candidate with a download URL. Fetches the…** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Pick the best video rendition from a NASA asset manifest. NASA file URLs follow…** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Pick the best image rendition from a NASA asset manifest. Same pattern as…** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Collapse arbitrary NASA nasa_ids into a filesystem-safe token. Some older items…** (1 connections) — `tools/video/stock_sources/nasa.py`
- **URL-encode the path component of a URL, leaving the host alone. NASA…** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Adapter for images.nasa.gov. Satisfies `StockSource`. Stateless, no required…** (1 connections) — `tools/video/stock_sources/nasa.py`
- **Search NASA's media library for images and/or videos. Routes by `filters.kind`:…** (1 connections) — `tools/video/stock_sources/nasa.py`

## Relationships

- [Stock Media Search](Stock_Media_Search.md) (10 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (3 shared connections)
- [Atelier Project Scaffolding](Atelier_Project_Scaffolding.md) (2 shared connections)
- [Clip Download](Clip_Download.md) (1 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (1 shared connections)

## Source Files

- `tools/video/stock_sources/nasa.py`

## Audit Trail

- EXTRACTED: 38 (93%)
- INFERRED: 3 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*