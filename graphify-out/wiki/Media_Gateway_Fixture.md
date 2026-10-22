# Media Gateway Fixture

> 8 nodes · cohesion 0.32

## Key Concepts

- **gateway()** (7 connections) — `tests/tools/test_schema_media_native_references.py`
- **media()** (3 connections) — `backlot/server.py`
- **do_GET()** (3 connections) — `tests/tools/test_schema_media_native_references.py`
- **respond()** (3 connections) — `tests/tools/test_schema_media_native_references.py`
- **do_POST()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **local_request()** (2 connections) — `tests/tools/test_schema_media_native_references.py`
- **log_message()** (1 connections) — `tests/tools/test_schema_media_native_references.py`
- **fixture** (1 connections)

## Relationships

- [Board Server Pages](Board_Server_Pages.md) (2 shared connections)
- [Atlas Image Routing Tests](Atlas_Image_Routing_Tests.md) (1 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (1 shared connections)

## Source Files

- `backlot/server.py`
- `tests/tools/test_schema_media_native_references.py`

## Audit Trail

- EXTRACTED: 11 (85%)
- INFERRED: 2 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*