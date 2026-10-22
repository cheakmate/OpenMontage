# Kling TTS Provider Tests

> 28 nodes · cohesion 0.13

## Key Concepts

- **KlingTTS** (32 connections) — `tools/audio/kling_tts.py`
- **.execute()** (13 connections) — `tools/audio/kling_tts.py`
- **test_kling_tts.py** (12 connections) — `tests/contracts/test_kling_tts.py`
- **Any** (11 connections)
- **._download_audios()** (10 connections) — `tools/audio/kling_tts.py`
- **.check_dependencies()** (10 connections) — `tools/base_tool.py`
- **test_provider_agent_skills_reference_kling_official()** (6 connections) — `tests/contracts/test_kling_official_core.py`
- **test_execute_accepts_synchronous_create_response()** (5 connections) — `tests/contracts/test_kling_tts.py`
- **test_execute_downloads_all_audio_results()** (5 connections) — `tests/contracts/test_kling_tts.py`
- **._account_usage_result()** (5 connections) — `tools/audio/kling_tts.py`
- **._build_request()** (5 connections) — `tools/audio/kling_tts.py`
- **test_tts_schema_and_skill_metadata()** (4 connections) — `tests/contracts/test_kling_tts.py`
- **._copy_common_task_fields()** (4 connections) — `tools/audio/kling_tts.py`
- **.dry_run()** (4 connections) — `tools/audio/kling_tts.py`
- **.estimate_cost()** (4 connections) — `tools/audio/kling_tts.py`
- **test_tts_payload_and_validation()** (3 connections) — `tests/contracts/test_kling_tts.py`
- **._callback_result_data()** (3 connections) — `tools/audio/kling_tts.py`
- **._output_url()** (3 connections) — `tools/audio/kling_tts.py`
- **.estimate_runtime()** (2 connections) — `tools/audio/kling_tts.py`
- **download()** (1 connections) — `tests/contracts/test_kling_tts.py`
- **poll_classic()** (1 connections) — `tests/contracts/test_kling_tts.py`
- **post()** (1 connections) — `tests/contracts/test_kling_tts.py`
- **create_classic_task()** (1 connections) — `tests/contracts/test_kling_tts.py`
- **download()** (1 connections) — `tests/contracts/test_kling_tts.py`
- **poll_classic()** (1 connections) — `tests/contracts/test_kling_tts.py`
- *... and 3 more nodes in this community*

## Relationships

- [Kling Tools](Kling_Tools.md) (11 shared connections)
- [API Testing](API_Testing.md) (9 shared connections)
- [Core Utilities](Core_Utilities.md) (6 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Kling Avatar Tool](Kling_Avatar_Tool.md) (4 shared connections)
- [Atlas Tool Tests](Atlas_Tool_Tests.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Kling Core Tests](Kling_Core_Tests.md) (2 shared connections)
- [Kling Image Tests](Kling_Image_Tests.md) (2 shared connections)
- [Kling Avatar Tests](Kling_Avatar_Tests.md) (2 shared connections)
- [Kling Video Tests](Kling_Video_Tests.md) (1 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_kling_official_core.py`
- `tests/contracts/test_kling_tts.py`
- `tools/audio/kling_tts.py`
- `tools/base_tool.py`

## Audit Trail

- EXTRACTED: 84 (84%)
- INFERRED: 16 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*