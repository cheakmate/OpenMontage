# Atlas Image Routing Tests

> 13 nodes · cohesion 0.23

## Key Concepts

- **test_schema_media_native_references.py** (21 connections) — `tests/tools/test_schema_media_native_references.py`
- **AtlasRefreshImage** (6 connections) — `tools/graphics/atlas_refresh_image.py`
- **atlas_refresh_image.py** (6 connections) — `tools/graphics/atlas_refresh_image.py`
- **parametrize** (5 connections)
- **test_text_only_request_keeps_text_route()** (3 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_atlas_nano_aspect_ratio_and_local_mask()** (2 connections) — `tests/tools/test_provider_refresh.py`
- **test_canonical_reference_alias_keeps_existing_route()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_explicit_reference_route_preserves_native_reference()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_explicit_text_route_cannot_silently_drop_native_reference()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **test_native_reference_selects_reference_route()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **http_server** (2 connections)
- **Native reference inputs must reach the selected generation request.** (1 connections) — `tests/tools/test_schema_media_native_references.py`
- **GPT Image 2.5 and Nano Banana Pro on Atlas Cloud.** (1 connections) — `tools/graphics/atlas_refresh_image.py`

## Relationships

- [Provider Contract Tests](Provider_Contract_Tests.md) (7 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (6 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Event Logging](Event_Logging.md) (1 shared connections)
- [Media Gateway Fixture](Media_Gateway_Fixture.md) (1 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_provider_refresh.py`
- `tests/tools/test_schema_media_native_references.py`
- `tools/graphics/atlas_refresh_image.py`

## Audit Trail

- EXTRACTED: 36 (97%)
- INFERRED: 1 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*