# Face Tracking AutoReframe

> 34 nodes · cohesion 0.11

## Key Concepts

- **AutoReframe** (22 connections) — `tools/video/auto_reframe.py`
- **FaceTracker** (18 connections) — `tools/analysis/face_tracker.py`
- **.execute()** (10 connections) — `tools/video/auto_reframe.py`
- **.execute()** (8 connections) — `tools/analysis/face_tracker.py`
- **._get_face_data()** (8 connections) — `tools/video/auto_reframe.py`
- **._render_dynamic_crop()** (7 connections) — `tools/video/auto_reframe.py`
- **._render_static_crop()** (7 connections) — `tools/video/auto_reframe.py`
- **.get_status()** (5 connections) — `tools/analysis/face_tracker.py`
- **._get_video_info()** (5 connections) — `tools/video/auto_reframe.py`
- **Any** (5 connections)
- **._track_opencv()** (4 connections) — `tools/analysis/face_tracker.py`
- **._compute_crop_size()** (4 connections) — `tools/video/auto_reframe.py`
- **._compute_face_tracked_crop()** (4 connections) — `tools/video/auto_reframe.py`
- **._compute_output_resolution()** (4 connections) — `tools/video/auto_reframe.py`
- **Path** (4 connections)
- **._has_mediapipe()** (3 connections) — `tools/analysis/face_tracker.py`
- **._has_opencv()** (3 connections) — `tools/analysis/face_tracker.py`
- **._track_mediapipe()** (3 connections) — `tools/analysis/face_tracker.py`
- **.estimate_runtime()** (3 connections) — `tools/video/auto_reframe.py`
- **._smooth_positions()** (3 connections) — `tools/video/auto_reframe.py`
- **.list_presets()** (2 connections) — `tools/video/auto_reframe.py`
- **Path** (2 connections)
- **Any** (1 connections)
- **Fallback: OpenCV Haar cascade face detection.** (1 connections) — `tools/analysis/face_tracker.py`
- **Get video width, height, fps via ffprobe.** (1 connections) — `tools/video/auto_reframe.py`
- *... and 9 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (19 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (6 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (3 shared connections)

## Source Files

- `tools/analysis/face_tracker.py`
- `tools/video/auto_reframe.py`

## Audit Trail

- EXTRACTED: 69 (79%)
- INFERRED: 18 (21%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*