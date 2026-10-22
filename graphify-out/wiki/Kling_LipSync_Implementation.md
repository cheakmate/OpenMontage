# Kling LipSync Implementation

> 32 nodes · cohesion 0.18

## Key Concepts

- **KlingLipSync** (53 connections) — `tools/avatar/kling_lip_sync.py`
- **Any** (25 connections)
- **.execute()** (15 connections) — `tools/avatar/kling_lip_sync.py`
- **._run_advanced_lip_sync()** (13 connections) — `tools/avatar/kling_lip_sync.py`
- **._download_videos()** (10 connections) — `tools/avatar/kling_lip_sync.py`
- **._build_advanced_request()** (8 connections) — `tools/avatar/kling_lip_sync.py`
- **._apply_face_timing_defaults()** (6 connections) — `tools/avatar/kling_lip_sync.py`
- **.estimate_cost()** (6 connections) — `tools/avatar/kling_lip_sync.py`
- **._identify_faces()** (6 connections) — `tools/avatar/kling_lip_sync.py`
- **._identify_result()** (6 connections) — `tools/avatar/kling_lip_sync.py`
- **._account_usage_result()** (5 connections) — `tools/avatar/kling_lip_sync.py`
- **._face_selection()** (5 connections) — `tools/avatar/kling_lip_sync.py`
- **._normalize_face_choose()** (5 connections) — `tools/avatar/kling_lip_sync.py`
- **._write_faces_artifact()** (5 connections) — `tools/avatar/kling_lip_sync.py`
- **test_full_lip_sync_preserves_nested_face_timing_defaults()** (4 connections) — `tests/contracts/test_kling_official_avatar.py`
- **test_lip_sync_cost_estimate_is_not_zero()** (4 connections) — `tests/contracts/test_kling_official_avatar.py`
- **._build_identify_request()** (4 connections) — `tools/avatar/kling_lip_sync.py`
- **._copy_audio_input()** (4 connections) — `tools/avatar/kling_lip_sync.py`
- **._copy_common_task_fields()** (4 connections) — `tools/avatar/kling_lip_sync.py`
- **.dry_run()** (4 connections) — `tools/avatar/kling_lip_sync.py`
- **._local_audio_duration_ms()** (4 connections) — `tools/avatar/kling_lip_sync.py`
- **test_auto_select_face_area_avoids_position_inflation()** (3 connections) — `tests/contracts/test_kling_official_avatar.py`
- **test_identify_face_payload_and_local_video_rejection()** (3 connections) — `tests/contracts/test_kling_official_avatar.py`
- **._callback_result_data()** (3 connections) — `tools/avatar/kling_lip_sync.py`
- **._copy_timing_fields()** (3 connections) — `tools/avatar/kling_lip_sync.py`
- *... and 7 more nodes in this community*

## Relationships

- [Kling Client Tests](Kling_Client_Tests.md) (20 shared connections)
- [Kling Avatar LipSync Tests](Kling_Avatar_LipSync_Tests.md) (11 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (8 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Lip Sync Download Tests](Lip_Sync_Download_Tests.md) (2 shared connections)
- [BMTS Lite Tests](BMTS_Lite_Tests.md) (2 shared connections)
- [CogVideo Variant Tests](CogVideo_Variant_Tests.md) (2 shared connections)
- [Kling Image Provider Tests](Kling_Image_Provider_Tests.md) (1 shared connections)
- [Idempotency Cache Wrapper](Idempotency_Cache_Wrapper.md) (1 shared connections)

## Source Files

- `tests/contracts/test_kling_official_avatar.py`
- `tools/avatar/kling_lip_sync.py`

## Audit Trail

- EXTRACTED: 117 (84%)
- INFERRED: 22 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*