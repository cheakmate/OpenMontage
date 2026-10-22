# HTTP Server Tests

> 17 nodes · cohesion 0.17

## Key Concepts

- **test_schema_media_native_references.py** (21 connections) — `tests/tools/test_schema_media_native_references.py`
- **AtlasRefreshImage** (6 connections) — `tools/graphics/atlas_refresh_image.py`
- **LTXAPIVideo** (6 connections) — `tools/video/ltx_api_video.py`
- **atlas_refresh_image.py** (6 connections) — `tools/graphics/atlas_refresh_image.py`
- **ltx_api_video.py** (6 connections) — `tools/video/ltx_api_video.py`
- **parametrize** (5 connections)
- **test_text_only_request_keeps_text_route()** (3 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_atlas_nano_aspect_ratio_and_local_mask()** (2 connections) — `tests/tools/test_provider_refresh.py`
- **test_ltx_matrix_and_last_frame()** (2 connections) — `tests/tools/test_provider_refresh.py`
- **test_canonical_reference_alias_keeps_existing_route()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_explicit_reference_route_preserves_native_reference()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_explicit_text_route_cannot_silently_drop_native_reference()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_native_reference_selects_reference_route()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **http_server** (2 connections)
- **Native reference inputs must reach the selected generation request.** (1 connections) — `tests/tools/test_schema_media_native_references.py`
- **GPT Image 2.5 and Nano Banana Pro on Atlas Cloud.** (1 connections) — `tools/graphics/atlas_refresh_image.py`
- **LTX-2.5 Fast and Pro direct asynchronous API.** (1 connections) — `tools/video/ltx_api_video.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (7 shared connections)
- [Provider Refresh](Provider_Refresh.md) (6 shared connections)
- [Replicate Nano Banana](Replicate_Nano_Banana.md) (6 shared connections)
- [Tool Schema Tests](Tool_Schema_Tests.md) (1 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Event Stream](Event_Stream.md) (1 shared connections)
- [Media Gateway Handler](Media_Gateway_Handler.md) (1 shared connections)
- [API Testing](API_Testing.md) (1 shared connections)

## Source Files

- `tests/tools/test_provider_refresh.py`
- `tests/tools/test_schema_media_native_references.py`
- `tools/graphics/atlas_refresh_image.py`
- `tools/video/ltx_api_video.py`

## Audit Trail

- EXTRACTED: 45 (96%)
- INFERRED: 2 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*