# Pixabay Source Testing

> 22 nodes · cohesion 0.13

## Key Concepts

- **test_pixabay_per_page_clamp.py** (15 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **stock_sources/pixabay_video.py** (10 connections) — `tools/video/stock_sources/pixabay_video.py`
- **PixabayVideoSource** (9 connections) — `tools/video/stock_sources/pixabay_video.py`
- **_patch_requests_get()** (5 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **test_pixabay_stock_source_clamps_per_page()** (5 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **.search()** (5 connections) — `tools/video/stock_sources/pixabay_video.py`
- **_FakeResponse** (4 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **_pick_rendition()** (4 connections) — `tools/video/stock_sources/pixabay_video.py`
- **_capture_get()** (3 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **test_pixabay_image_tool_clamps_per_page()** (3 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **test_pixabay_video_tool_clamps_per_page()** (3 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **.download()** (3 connections) — `tools/video/stock_sources/pixabay_video.py`
- **fake_get()** (2 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **.json()** (1 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **.raise_for_status()** (1 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **.is_available()** (1 connections) — `tools/video/stock_sources/pixabay_video.py`
- **Any** (1 connections)
- **Path** (1 connections)
- **Pixabay rejects per_page outside 3-200 with HTTP 400, so every Pixabay caller…** (1 connections) — `tests/tools/test_pixabay_per_page_clamp.py`
- **Pixabay Video stock source adapter. Wraps the Pixabay Video API…** (1 connections) — `tools/video/stock_sources/pixabay_video.py`
- **Pick the best rendition from Pixabay's nested video dict. Pixabay returns…** (1 connections) — `tools/video/stock_sources/pixabay_video.py`
- **Pixabay Video adapter. Satisfies `StockSource`.** (1 connections) — `tools/video/stock_sources/pixabay_video.py`

## Relationships

- [Media Source Adapters](Media_Source_Adapters.md) (11 shared connections)
- [Tool Execution](Tool_Execution.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)

## Source Files

- `tests/tools/test_pixabay_per_page_clamp.py`
- `tools/video/stock_sources/pixabay_video.py`

## Audit Trail

- EXTRACTED: 46 (92%)
- INFERRED: 4 (8%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*