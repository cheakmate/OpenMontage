# Eye Enhancement

> 24 nodes · cohesion 0.14

## Key Concepts

- **EyeEnhance** (21 connections) — `tools/enhancement/eye_enhance.py`
- **._enhance_mediapipe()** (8 connections) — `tools/enhancement/eye_enhance.py`
- **.execute()** (8 connections) — `tools/enhancement/eye_enhance.py`
- **._apply_eye_enhancements()** (7 connections) — `tools/enhancement/eye_enhance.py`
- **._enhance_ffmpeg_fallback()** (7 connections) — `tools/enhancement/eye_enhance.py`
- **._enhance_opencv_only()** (7 connections) — `tools/enhancement/eye_enhance.py`
- **Any** (5 connections)
- **.get_status()** (4 connections) — `tools/enhancement/eye_enhance.py`
- **._brighten_eyes()** (3 connections) — `tools/enhancement/eye_enhance.py`
- **.estimate_runtime()** (3 connections) — `tools/enhancement/eye_enhance.py`
- **._has_mediapipe()** (3 connections) — `tools/enhancement/eye_enhance.py`
- **._has_opencv()** (3 connections) — `tools/enhancement/eye_enhance.py`
- **._remove_dark_circles()** (3 connections) — `tools/enhancement/eye_enhance.py`
- **._sharpen_eyes()** (3 connections) — `tools/enhancement/eye_enhance.py`
- **Path** (3 connections)
- **lm_to_px()** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Full MediaPipe Face Mesh + OpenCV pipeline for precise eye enhancement.** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Apply eye enhancements to a single frame using detected landmarks.** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Brighten the under-eye area to reduce dark circles.** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Subtly brighten the eye/sclera area.** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Sharpen the eye region for more detail.** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Fallback: OpenCV Haar cascade for face detection + generic eye region…** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Last resort: FFmpeg-only. Applies general face-area enhancement (not eye-…** (1 connections) — `tools/enhancement/eye_enhance.py`
- **Eye enhancement is roughly 0.5x-1x realtime depending on resolution.** (1 connections) — `tools/enhancement/eye_enhance.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (9 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (5 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (3 shared connections)

## Source Files

- `tools/enhancement/eye_enhance.py`

## Audit Trail

- EXTRACTED: 50 (88%)
- INFERRED: 7 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*