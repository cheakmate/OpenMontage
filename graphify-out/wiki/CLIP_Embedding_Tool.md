# CLIP Embedding Tool

> 25 nodes · cohesion 0.13

## Key Concepts

- **._process_candidate()** (13 connections) — `tools/video/corpus_builder.py`
- **clip_embedder.py** (11 connections) — `lib/clip_embedder.py`
- **embed_texts()** (9 connections) — `lib/clip_embedder.py`
- **_as_feature_tensor()** (8 connections) — `lib/clip_embedder.py`
- **embed_images()** (8 connections) — `lib/clip_embedder.py`
- **test_clip_embedder_compat.py** (7 connections) — `tests/lib/test_clip_embedder_compat.py`
- **pool_frames()** (5 connections) — `lib/clip_embedder.py`
- **_ModelOutput** (4 connections) — `tests/lib/test_clip_embedder_compat.py`
- **_load()** (4 connections) — `lib/clip_embedder.py`
- **test_transformers_5_output_unwraps_projected_pooler_output()** (4 connections) — `tests/lib/test_clip_embedder_compat.py`
- **_Tensor** (3 connections) — `tests/lib/test_clip_embedder_compat.py`
- **test_missing_pooler_output_does_not_replace_features_with_none()** (3 connections) — `tests/lib/test_clip_embedder_compat.py`
- **test_transformers_4_tensor_passes_through()** (3 connections) — `tests/lib/test_clip_embedder_compat.py`
- **_guess_ext()** (3 connections) — `tools/video/corpus_builder.py`
- **ndarray** (3 connections)
- **.__init__()** (1 connections) — `tests/lib/test_clip_embedder_compat.py`
- **Path** (1 connections)
- **CLIP embedder: thin wrapper around openai/clip-vit-base-patch32 for corpus…** (1 connections) — `lib/clip_embedder.py`
- **Embed a list of text strings into a (N, 512) float32 matrix. Each row is…** (1 connections) — `lib/clip_embedder.py`
- **Average a (K, 512) stack of frame embeddings into a (512,) clip vector. Re-…** (1 connections) — `lib/clip_embedder.py`
- **Load CLIP model and processor exactly once per process.** (1 connections) — `lib/clip_embedder.py`
- **Normalize CLIP feature return values across transformers versions. Transformers…** (1 connections) — `lib/clip_embedder.py`
- **Embed a list of image files into a (N, 512) float32 matrix. Each row is…** (1 connections) — `lib/clip_embedder.py`
- **Download → thumb → embed → add one Candidate to the corpus. Returns the created…** (1 connections) — `tools/video/corpus_builder.py`
- **Extract a sensible file extension from a candidate's URL.** (1 connections) — `tools/video/corpus_builder.py`

## Relationships

- [Tool Execution](Tool_Execution.md) (5 shared connections)
- [Corpus Builder Testing](Corpus_Builder_Testing.md) (3 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Video Thumbnail Extractor](Video_Thumbnail_Extractor.md) (2 shared connections)
- [Clip Similarity Operations](Clip_Similarity_Operations.md) (1 shared connections)
- [Corpus Indexing System](Corpus_Indexing_System.md) (1 shared connections)
- [Video Clip Similarity Search](Video_Clip_Similarity_Search.md) (1 shared connections)
- [Audio Analysis](Audio_Analysis.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [WAN Engine](WAN_Engine.md) (1 shared connections)

## Source Files

- `lib/clip_embedder.py`
- `tests/lib/test_clip_embedder_compat.py`
- `tools/video/corpus_builder.py`

## Audit Trail

- EXTRACTED: 57 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*