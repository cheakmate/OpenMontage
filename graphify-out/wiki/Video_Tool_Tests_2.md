# Video Tool Tests

> 13 nodes · cohesion 0.23

## Key Concepts

- **.execute()** (12 connections) — `tools/video/atlas_video.py`
- **Any** (7 connections)
- **._build_payload()** (6 connections) — `tools/video/atlas_video.py`
- **._resolve_media()** (5 connections) — `tools/video/atlas_video.py`
- **.test_invalid_route_and_enum_fail_loudly()** (4 connections) — `tests/contracts/test_atlas_tools.py`
- **.estimate_cost()** (4 connections) — `tools/video/atlas_video.py`
- **._resolve_model()** (4 connections) — `tools/video/atlas_video.py`
- **._upload_value()** (4 connections) — `tools/video/atlas_video.py`
- **.test_seedance_25_accepts_audio_only_and_30_images()** (3 connections) — `tests/contracts/test_atlas_tools.py`
- **.get_info()** (3 connections) — `tools/video/atlas_video.py`
- **._validate_choice()** (3 connections) — `tools/video/atlas_video.py`
- **.estimate_runtime()** (2 connections) — `tools/video/atlas_video.py`
- **_is_remote()** (2 connections) — `tools/video/atlas_video.py`

## Relationships

- [Atlas Video Tests](Atlas_Video_Tests.md) (11 shared connections)
- [Atlas Cloud Client](Atlas_Cloud_Client.md) (4 shared connections)
- [Video Route Tests](Video_Route_Tests.md) (2 shared connections)
- [Atlas Provider Tests](Atlas_Provider_Tests.md) (2 shared connections)
- [Atlas Image Provider](Atlas_Image_Provider.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)
- [Character Animation](Character_Animation.md) (1 shared connections)
- [Image Selector](Image_Selector.md) (1 shared connections)

## Source Files

- `tests/contracts/test_atlas_tools.py`
- `tools/video/atlas_video.py`

## Audit Trail

- EXTRACTED: 38 (93%)
- INFERRED: 3 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*