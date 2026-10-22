# Sora Video Provider

> 25 nodes · cohesion 0.16

## Key Concepts

- **SoraVideo** (27 connections) — `tools/video/sora_video.py`
- **test_sora_video.py** (14 connections) — `tests/tools/test_sora_video.py`
- **.execute()** (12 connections) — `tools/video/sora_video.py`
- **Any** (9 connections)
- **test_sora_video_executes_with_current_create_and_poll_sdk_surface()** (7 connections) — `tests/tools/test_sora_video.py`
- **._normalize_seconds()** (5 connections) — `tools/video/sora_video.py`
- **test_sora_video_reports_unavailable_when_openai_sdk_lacks_video_api()** (4 connections) — `tests/tools/test_sora_video.py`
- **.estimate_cost()** (4 connections) — `tools/video/sora_video.py`
- **._openai_sdk_supports_videos()** (4 connections) — `tools/video/sora_video.py`
- **._write_download()** (4 connections) — `tools/video/sora_video.py`
- **test_sora_video_loads_openai_key_from_repo_dotenv_when_process_env_is_empty()** (3 connections) — `tests/tools/test_sora_video.py`
- **.estimate_runtime()** (3 connections) — `tools/video/sora_video.py`
- **._file_to_data_uri()** (3 connections) — `tools/video/sora_video.py`
- **.get_status()** (3 connections) — `tools/video/sora_video.py`
- **._get_status_value()** (3 connections) — `tools/video/sora_video.py`
- **._get_video_id()** (3 connections) — `tools/video/sora_video.py`
- **._normalize_model()** (3 connections) — `tools/video/sora_video.py`
- **._normalize_size()** (3 connections) — `tools/video/sora_video.py`
- **._version_tuple()** (2 connections) — `tools/video/sora_video.py`
- **Path** (2 connections)
- **create_and_poll()** (1 connections) — `tests/tools/test_sora_video.py`
- **download_content()** (1 connections) — `tests/tools/test_sora_video.py`
- **__init__()** (1 connections) — `tests/tools/test_sora_video.py`
- **write_to_file()** (1 connections) — `tests/tools/test_sora_video.py`
- **Regression coverage for first-class Sora provider discovery.** (1 connections) — `tests/tools/test_sora_video.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (6 shared connections)
- [Core Utilities](Core_Utilities.md) (6 shared connections)
- [Tool Execution](Tool_Execution.md) (4 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Cinematic Scene Types](Cinematic_Scene_Types.md) (2 shared connections)
- [Project Init](Project_Init.md) (2 shared connections)
- [Audio Mixing](Audio_Mixing.md) (2 shared connections)
- [Tool Registry](Tool_Registry.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Atlas Tool Tests](Atlas_Tool_Tests.md) (1 shared connections)

## Source Files

- `tests/tools/test_sora_video.py`
- `tools/video/sora_video.py`

## Audit Trail

- EXTRACTED: 65 (87%)
- INFERRED: 10 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*