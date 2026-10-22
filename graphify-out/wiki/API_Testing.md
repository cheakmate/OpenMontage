# API Testing

> 56 nodes · cohesion 0.09

## Key Concepts

- **KlingClient** (66 connections) — `tools/_kling/client.py`
- **KlingAPIError** (38 connections) — `tools/_kling/errors.py`
- **.execute()** (17 connections) — `tools/video/kling_official_video.py`
- **errors.py** (17 connections) — `tools/_kling/errors.py`
- **test_kling_submission_transport.py** (16 connections) — `tests/contracts/test_kling_submission_transport.py`
- **.create_classic_task()** (13 connections) — `tools/_kling/client.py`
- **Any** (11 connections)
- **FakeSession** (10 connections) — `tests/contracts/test_kling_official_core.py`
- **.poll_classic()** (10 connections) — `tools/_kling/client.py`
- **.post()** (10 connections) — `tools/_kling/client.py`
- **._request()** (10 connections) — `tools/_kling/client.py`
- **task_server()** (9 connections) — `tests/contracts/test_kling_submission_transport.py`
- **._create_and_collect_audios()** (9 connections) — `tools/audio/kling_tts.py`
- **is_retryable_kling_error()** (9 connections) — `tools/_kling/errors.py`
- **FakeResponse** (8 connections) — `tests/contracts/test_kling_official_core.py`
- **test_1303_retryable_message_mentions_concurrency()** (8 connections) — `tests/contracts/test_kling_official_core.py`
- **test_business_error_preserves_code_message_request_id()** (7 connections) — `tests/contracts/test_kling_official_core.py`
- **test_lost_creation_response_is_not_replayed()** (7 connections) — `tests/contracts/test_kling_submission_transport.py`
- **.create_turbo()** (7 connections) — `tools/_kling/client.py`
- **.headers()** (6 connections) — `tools/_kling/client.py`
- **test_classic_create_and_poll_parse_result_paths()** (6 connections) — `tests/contracts/test_kling_official_core.py`
- **test_missing_api_key_header_error()** (6 connections) — `tests/contracts/test_kling_official_core.py`
- **test_turbo_create_and_poll_parse_result_paths()** (6 connections) — `tests/contracts/test_kling_official_core.py`
- **.get()** (6 connections) — `tools/_kling/client.py`
- **.poll_turbo()** (6 connections) — `tools/_kling/client.py`
- *... and 31 more nodes in this community*

## Relationships

- [Kling Tools](Kling_Tools.md) (28 shared connections)
- [Kling Core Tests](Kling_Core_Tests.md) (18 shared connections)
- [Kling Video Tests](Kling_Video_Tests.md) (16 shared connections)
- [Kling Avatar Tests](Kling_Avatar_Tests.md) (10 shared connections)
- [Kling TTS Provider Tests](Kling_TTS_Provider_Tests.md) (9 shared connections)
- [Kling Avatar Tool](Kling_Avatar_Tool.md) (9 shared connections)
- [Kling Image Tests](Kling_Image_Tests.md) (7 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Project Init](Project_Init.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (1 shared connections)
- [Live API Tests](Live_API_Tests.md) (1 shared connections)

## Source Files

- `tests/contracts/test_kling_official_core.py`
- `tests/contracts/test_kling_submission_transport.py`
- `tools/_kling/__init__.py`
- `tools/_kling/client.py`
- `tools/_kling/errors.py`
- `tools/audio/kling_tts.py`
- `tools/video/kling_official_video.py`

## Audit Trail

- EXTRACTED: 204 (81%)
- INFERRED: 48 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*