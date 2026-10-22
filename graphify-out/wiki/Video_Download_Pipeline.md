# Video Download Pipeline

> 14 nodes · cohesion 0.20

## Key Concepts

- **.execute()** (9 connections) — `tools/analysis/video_downloader.py`
- **._download_video()** (6 connections) — `tools/analysis/video_downloader.py`
- **._find_downloaded()** (6 connections) — `tools/analysis/video_downloader.py`
- **._download_subtitles()** (5 connections) — `tools/analysis/video_downloader.py`
- **._download_audio()** (4 connections) — `tools/analysis/video_downloader.py`
- **Path** (4 connections)
- **._detect_platform()** (3 connections) — `tools/analysis/video_downloader.py`
- **._extract_metadata()** (3 connections) — `tools/analysis/video_downloader.py`
- **Any** (1 connections)
- **Detect platform from URL.** (1 connections) — `tools/analysis/video_downloader.py`
- **Extract metadata without downloading.** (1 connections) — `tools/analysis/video_downloader.py`
- **Download video + extract audio track.** (1 connections) — `tools/analysis/video_downloader.py`
- **Download subtitles only.** (1 connections) — `tools/analysis/video_downloader.py`
- **Find a downloaded file by prefix and possible extensions.** (1 connections) — `tools/analysis/video_downloader.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (7 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (1 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)
- [Tool Status Reporting](Tool_Status_Reporting.md) (1 shared connections)

## Source Files

- `tools/analysis/video_downloader.py`

## Audit Trail

- EXTRACTED: 27 (96%)
- INFERRED: 1 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*