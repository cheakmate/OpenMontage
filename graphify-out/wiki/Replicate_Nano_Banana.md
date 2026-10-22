# Replicate Nano Banana

> 20 nodes · cohesion 0.14

## Key Concepts

- **SchemaMedia** (27 connections) — `tools/schema_media.py`
- **wan_atlas_video.py** (6 connections) — `tools/video/wan_atlas_video.py`
- **WanAtlasVideo** (5 connections) — `tools/video/wan_atlas_video.py`
- **WanReplicateVideo** (5 connections) — `tools/video/wan_replicate_video.py`
- **gemini_replicate_image.py** (5 connections) — `tools/graphics/gemini_replicate_image.py`
- **wan_replicate_video.py** (5 connections) — `tools/video/wan_replicate_video.py`
- **GeminiReplicateImage** (4 connections) — `tools/graphics/gemini_replicate_image.py`
- **test_wan_hosts_use_their_own_image_contract()** (4 connections) — `tests/tools/test_provider_refresh.py`
- **.build_request()** (4 connections) — `tools/schema_media.py`
- **.catalog_file()** (3 connections) — `tools/schema_media.py`
- **.__init__()** (3 connections) — `tools/schema_media.py`
- **.endpoints()** (2 connections) — `tools/schema_media.py`
- **test_replicate_nano_banana_disables_fallback()** (2 connections) — `tests/tools/test_provider_refresh.py`
- **.estimate_cost()** (2 connections) — `tools/schema_media.py`
- **.validate_ltx()** (2 connections) — `tools/schema_media.py`
- **.estimate_cost()** (1 connections) — `tools/video/wan_replicate_video.py`
- **Nano Banana Pro via Replicate with model fallback explicitly disabled.** (1 connections) — `tools/graphics/gemini_replicate_image.py`
- **Checked-in schema file name.** (1 connections) — `tools/schema_media.py`
- **Wan 3.0 through Atlas Cloud, using its native reference contract.** (1 connections) — `tools/video/wan_atlas_video.py`
- **Wan 3.0 through Replicate; no unsupported reference-video routing.** (1 connections) — `tools/video/wan_replicate_video.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (14 shared connections)
- [Provider Refresh](Provider_Refresh.md) (9 shared connections)
- [HTTP Server Tests](HTTP_Server_Tests.md) (6 shared connections)
- [Image Selector](Image_Selector.md) (1 shared connections)
- [Character Animation](Character_Animation.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)

## Source Files

- `tests/tools/test_provider_refresh.py`
- `tools/graphics/gemini_replicate_image.py`
- `tools/schema_media.py`
- `tools/video/wan_atlas_video.py`
- `tools/video/wan_replicate_video.py`

## Audit Trail

- EXTRACTED: 51 (88%)
- INFERRED: 7 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*