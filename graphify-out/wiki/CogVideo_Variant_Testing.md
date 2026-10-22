# CogVideo Variant Testing

> 20 nodes · cohesion 0.13

## Key Concepts

- **CogVideoVideo** (21 connections) — `tools/video/cogvideo_video.py`
- **test_cogvideo_i2v_variant.py** (13 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **test_execute_allows_i2v_for_5b_variant()** (6 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **.execute()** (5 connections) — `tools/video/cogvideo_video.py`
- **test_execute_rejects_i2v_for_2b_variant()** (4 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **.get_status()** (4 connections) — `tools/video/cogvideo_video.py`
- **test_is_operation_available_reflects_default_variant()** (3 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **.is_operation_available()** (3 connections) — `tools/video/cogvideo_video.py`
- **._variant_for()** (3 connections) — `tools/video/cogvideo_video.py`
- **test_2b_variant_is_t2v_only()** (2 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **.estimate_runtime()** (2 connections) — `tools/video/cogvideo_video.py`
- **test_5b_variant_supports_i2v()** (1 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **fake_generate()** (1 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **.estimate_cost()** (1 connections) — `tools/video/cogvideo_video.py`
- **Regression for cogvideo-2b i2v mismatch (REVIEW §8 #4). COGVIDEO_VARIANTS…** (1 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **The premise: the 2B variant really does declare i2v=False.** (1 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **Selecting the 2B variant for image_to_video fails fast, not at the pipeline.** (1 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **The default 5B variant still routes to generation for image_to_video.** (1 connections) — `tests/tools/test_cogvideo_i2v_variant.py`
- **Resolve the active variant dict, falling back to the default.** (1 connections) — `tools/video/cogvideo_video.py`
- **Capability is variant-driven, not unconditional. cogvideo_video advertised…** (1 connections) — `tools/video/cogvideo_video.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (10 shared connections)
- [Core Utilities](Core_Utilities.md) (5 shared connections)
- [Tool Execution](Tool_Execution.md) (5 shared connections)
- [Character Animation](Character_Animation.md) (4 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)

## Source Files

- `tests/tools/test_cogvideo_i2v_variant.py`
- `tools/video/cogvideo_video.py`

## Audit Trail

- EXTRACTED: 37 (74%)
- INFERRED: 13 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*