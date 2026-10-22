# Video Thumbnail Extraction

> 5 nodes · cohesion 0.40

## Key Concepts

- **_extract_video_thumbs()** (4 connections) — `tools/video/corpus_builder.py`
- **_save_as_jpeg()** (4 connections) — `tools/video/corpus_builder.py`
- **Path** (3 connections)
- **Extract `n` evenly-spaced JPEG thumbnails from a video. Returns ``(thumb_paths,…** (1 connections) — `tools/video/corpus_builder.py`
- **Load an arbitrary image file and re-save as JPEG. Handles PNG/JPEG/TIFF/WebP…** (1 connections) — `tools/video/corpus_builder.py`

## Relationships

- [CLIP Embedder](CLIP_Embedder.md) (2 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [Corpus Path Safety](Corpus_Path_Safety.md) (1 shared connections)

## Source Files

- `tools/video/corpus_builder.py`

## Audit Trail

- EXTRACTED: 9 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*