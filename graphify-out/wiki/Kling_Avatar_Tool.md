# Kling Avatar Tool

> 24 nodes · cohesion 0.16

## Key Concepts

- **KlingAvatar** (32 connections) — `tools/avatar/kling_avatar.py`
- **.execute()** (14 connections) — `tools/avatar/kling_avatar.py`
- **.dry_run()** (11 connections) — `tools/base_tool.py`
- **Any** (11 connections)
- **._download_videos()** (10 connections) — `tools/avatar/kling_avatar.py`
- **.download()** (8 connections) — `tools/_kling/client.py`
- **._build_request()** (7 connections) — `tools/avatar/kling_avatar.py`
- **test_execute_downloads_avatar_video()** (5 connections) — `tests/contracts/test_kling_official_avatar.py`
- **._account_usage_result()** (5 connections) — `tools/avatar/kling_avatar.py`
- **test_avatar_cost_estimate_is_not_zero()** (4 connections) — `tests/contracts/test_kling_official_avatar.py`
- **._copy_audio_input()** (4 connections) — `tools/avatar/kling_avatar.py`
- **._copy_common_task_fields()** (4 connections) — `tools/avatar/kling_avatar.py`
- **.dry_run()** (4 connections) — `tools/avatar/kling_avatar.py`
- **.estimate_cost()** (4 connections) — `tools/avatar/kling_avatar.py`
- **test_avatar_requires_image_and_audio()** (3 connections) — `tests/contracts/test_kling_official_avatar.py`
- **._callback_result_data()** (3 connections) — `tools/avatar/kling_avatar.py`
- **._output_url()** (3 connections) — `tools/avatar/kling_avatar.py`
- **.estimate_runtime()** (2 connections) — `tools/avatar/kling_avatar.py`
- **create_classic_task()** (1 connections) — `tests/contracts/test_kling_official_avatar.py`
- **download()** (1 connections) — `tests/contracts/test_kling_official_avatar.py`
- **poll_classic()** (1 connections) — `tests/contracts/test_kling_official_avatar.py`
- **Path** (1 connections)
- **Path** (1 connections)
- **Preflight check without side effects. Override for paid/publishing tools.** (1 connections) — `tools/base_tool.py`

## Relationships

- [Kling Tools](Kling_Tools.md) (10 shared connections)
- [API Testing](API_Testing.md) (9 shared connections)
- [Kling Avatar Tests](Kling_Avatar_Tests.md) (8 shared connections)
- [Core Utilities](Core_Utilities.md) (5 shared connections)
- [Tool Testing](Tool_Testing.md) (5 shared connections)
- [Kling TTS Provider Tests](Kling_TTS_Provider_Tests.md) (4 shared connections)
- [Asset Cache Wrapper](Asset_Cache_Wrapper.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [Kling Image Tests](Kling_Image_Tests.md) (2 shared connections)
- [Kling Video Tests](Kling_Video_Tests.md) (2 shared connections)
- [Kling Core Tests](Kling_Core_Tests.md) (1 shared connections)
- [Image Selector](Image_Selector.md) (1 shared connections)

## Source Files

- `tests/contracts/test_kling_official_avatar.py`
- `tools/_kling/client.py`
- `tools/avatar/kling_avatar.py`
- `tools/base_tool.py`

## Audit Trail

- EXTRACTED: 75 (78%)
- INFERRED: 21 (22%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*