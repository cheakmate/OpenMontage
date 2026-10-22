# Wan Video Engine

> 30 nodes · cohesion 0.10

## Key Concepts

- **_wan_engine.py** (34 connections) — `tools/video/_wan_engine.py`
- **_generate_chained()** (9 connections) — `tools/video/_wan_engine.py`
- **_generate_single()** (7 connections) — `tools/video/_wan_engine.py`
- **load_wan_pipeline()** (7 connections) — `tools/video/_wan_engine.py`
- **_run_pass()** (6 connections) — `tools/video/_wan_engine.py`
- **free_wan_pipelines()** (5 connections) — `tools/video/_wan_engine.py`
- **channel_stats()** (4 connections) — `tools/video/_wan_engine.py`
- **load_image()** (4 connections) — `tools/video/_wan_engine.py`
- **match_channel_stats()** (4 connections) — `tools/video/_wan_engine.py`
- **model_info()** (3 connections) — `lib/clip_embedder.py`
- **derive_pipeline()** (3 connections) — `tools/video/_wan_engine.py`
- **_has_subfolder()** (3 connections) — `tools/video/_wan_engine.py`
- **load_video_frames()** (3 connections) — `tools/video/_wan_engine.py`
- **_to_pil_list()** (3 connections) — `tools/video/_wan_engine.py`
- **Any** (3 connections)
- **_generator()** (2 connections) — `tools/video/_wan_engine.py`
- **_quant_config()** (2 connections) — `tools/video/_wan_engine.py`
- **gc** (2 connections)
- **Return metadata about the loaded model (for index provenance).** (1 connections) — `lib/clip_embedder.py`
- **Local Wan 2.x generation engine. Covers the full Wan operation matrix on a…** (1 connections) — `tools/video/_wan_engine.py`
- **Drop every cached pipeline and release GPU memory.** (1 connections) — `tools/video/_wan_engine.py`
- **Load (and cache) the Wan pipeline class matching ``operation``. Wan repos…** (1 connections) — `tools/video/_wan_engine.py`
- **Load a reference still from disk or URL, resized to the target geometry.** (1 connections) — `tools/video/_wan_engine.py`
- **Read up to ``max_frames`` frames from a video file as resized PIL images.** (1 connections) — `tools/video/_wan_engine.py`
- **Normalise a diffusers video output into a flat list of PIL images.** (1 connections) — `tools/video/_wan_engine.py`
- *... and 5 more nodes in this community*

## Relationships

- [Wan Pipeline Validation Tests](Wan_Pipeline_Validation_Tests.md) (7 shared connections)
- [Wan Video Tests](Wan_Video_Tests.md) (4 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (3 shared connections)
- [OOM Diagnostics](OOM_Diagnostics.md) (2 shared connections)
- [MPS Device Tests](MPS_Device_Tests.md) (2 shared connections)
- [Precision Selection](Precision_Selection.md) (2 shared connections)
- [CLIP Embedder](CLIP_Embedder.md) (1 shared connections)
- [Scene Pacing Verification](Scene_Pacing_Verification.md) (1 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (1 shared connections)
- [GPU Offload Selection](GPU_Offload_Selection.md) (1 shared connections)
- [Segment Planning Tests](Segment_Planning_Tests.md) (1 shared connections)

## Source Files

- `lib/clip_embedder.py`
- `tools/video/_wan_engine.py`

## Audit Trail

- EXTRACTED: 70 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*