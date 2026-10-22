# Atlas Video Provider Tests

> 35 nodes · cohesion 0.12

## Key Concepts

- **AtlasVideo** (55 connections) — `tools/video/atlas_video.py`
- **FakeResponse** (18 connections) — `tests/tools/test_atlas_video.py`
- **test_atlas_video.py** (16 connections) — `tests/tools/test_atlas_video.py`
- **TestErrorHandling** (10 connections) — `tests/tools/test_atlas_video.py`
- **completed()** (9 connections) — `tests/tools/test_atlas_video.py`
- **TestReferenceToVideo** (7 connections) — `tests/tools/test_atlas_video.py`
- **TestAtlasVideoExecute** (6 connections) — `tests/tools/test_atlas_video.py`
- **.test_upload_accepts_bare_url_response_shape()** (5 connections) — `tests/tools/test_atlas_video.py`
- **TestAtlasImageExecute** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_auth_header_is_bearer()** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_text_to_image_round_trip()** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_image_to_video_uploads_local_file()** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_succeeded_status_is_treated_as_success()** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_text_to_video_round_trip()** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_non_200_envelope_code_is_an_error()** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_local_references_are_uploaded_and_remote_ones_pass_through()** (4 connections) — `tests/tools/test_atlas_video.py`
- **.test_reference_image_alone_satisfies_reference_to_video()** (4 connections) — `tests/tools/test_atlas_video.py`
- **test_exact_atlas_model_pins_video_selector_candidate()** (3 connections) — `tests/contracts/test_atlas_tools.py`
- **.test_completed_with_no_outputs_is_an_error()** (3 connections) — `tests/tools/test_atlas_video.py`
- **.test_failed_prediction_surfaces_error_message()** (3 connections) — `tests/tools/test_atlas_video.py`
- **.test_http_error_includes_body()** (3 connections) — `tests/tools/test_atlas_video.py`
- **.test_missing_prediction_id_is_an_error()** (3 connections) — `tests/tools/test_atlas_video.py`
- **.test_poll_timeout_reports_prediction_id()** (3 connections) — `tests/tools/test_atlas_video.py`
- **.test_missing_upload_file_is_an_error()** (2 connections) — `tests/tools/test_atlas_video.py`
- **.test_reference_to_video_without_any_asset_is_rejected()** (2 connections) — `tests/tools/test_atlas_video.py`
- *... and 10 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (15 shared connections)
- [Seedance Payload Builder](Seedance_Payload_Builder.md) (11 shared connections)
- [Atlas Image Routes](Atlas_Image_Routes.md) (8 shared connections)
- [Video Route Tests](Video_Route_Tests.md) (8 shared connections)
- [Network Guard Tests](Network_Guard_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Comfy Video Selector](Comfy_Video_Selector.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Atlas Cloud Client](Atlas_Cloud_Client.md) (1 shared connections)
- [Fake Requests Fixture](Fake_Requests_Fixture.md) (1 shared connections)

## Source Files

- `tests/contracts/test_atlas_tools.py`
- `tests/tools/test_atlas_video.py`
- `tools/video/atlas_video.py`

## Audit Trail

- EXTRACTED: 107 (87%)
- INFERRED: 16 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*