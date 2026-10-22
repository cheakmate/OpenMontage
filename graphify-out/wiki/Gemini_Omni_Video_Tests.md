# Gemini Omni Video Tests

> 59 nodes · cohesion 0.07

## Key Concepts

- **GeminiOmniVideo** (34 connections) — `tools/video/gemini_omni_video.py`
- **SoraVideo** (27 connections) — `tools/video/sora_video.py`
- **test_gemini_omni_video.py** (27 connections) — `tests/tools/test_gemini_omni_video.py`
- **.execute()** (12 connections) — `tools/video/sora_video.py`
- **_install_fake_requests()** (11 connections) — `tests/tools/test_gemini_omni_video.py`
- **FakeResponse** (10 connections) — `tests/tools/test_gemini_omni_video.py`
- **.execute()** (9 connections) — `tools/video/gemini_omni_video.py`
- **Any** (9 connections)
- **Any** (8 connections)
- **test_gemini_omni_edit_turn_sends_previous_interaction_id()** (5 connections) — `tests/tools/test_gemini_omni_video.py`
- **test_gemini_omni_image_to_video_sends_typed_parts()** (5 connections) — `tests/tools/test_gemini_omni_video.py`
- **test_gemini_omni_inline_data_response_is_handled()** (5 connections) — `tests/tools/test_gemini_omni_video.py`
- **test_gemini_omni_store_false_marks_result_not_editable()** (5 connections) — `tests/tools/test_gemini_omni_video.py`
- **test_gemini_omni_uri_delivery_handles_full_download_url()** (5 connections) — `tests/tools/test_gemini_omni_video.py`
- **._download_via_uri()** (5 connections) — `tools/video/gemini_omni_video.py`
- **.estimate_cost()** (5 connections) — `tools/video/gemini_omni_video.py`
- **._normalize_seconds()** (5 connections) — `tools/video/sora_video.py`
- **test_gemini_omni_cost_estimate_clamps_duration_hint()** (4 connections) — `tests/tools/test_gemini_omni_video.py`
- **test_gemini_omni_file_id_extraction_covers_documented_uri_shapes()** (4 connections) — `tests/tools/test_gemini_omni_video.py`
- **test_gemini_omni_text_to_video_via_uri_delivery()** (4 connections) — `tests/tools/test_gemini_omni_video.py`
- **._extract_output_video()** (4 connections) — `tools/video/gemini_omni_video.py`
- **._file_id_from_uri()** (4 connections) — `tools/video/gemini_omni_video.py`
- **._upload_video_file()** (4 connections) — `tools/video/gemini_omni_video.py`
- **.estimate_cost()** (4 connections) — `tools/video/sora_video.py`
- **._openai_sdk_supports_videos()** (4 connections) — `tools/video/sora_video.py`
- *... and 34 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (27 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (5 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Cinematic Scene Types](Cinematic_Scene_Types.md) (2 shared connections)
- [Environment Loader](Environment_Loader.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (2 shared connections)
- [Comfy Video Selector](Comfy_Video_Selector.md) (2 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (1 shared connections)

## Source Files

- `tests/tools/test_gemini_omni_video.py`
- `tools/video/gemini_omni_video.py`
- `tools/video/sora_video.py`

## Audit Trail

- EXTRACTED: 144 (86%)
- INFERRED: 23 (14%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*