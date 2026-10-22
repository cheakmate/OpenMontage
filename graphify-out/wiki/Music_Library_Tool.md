# Music Library Tool

> 22 nodes · cohesion 0.18

## Key Concepts

- **MusicLibrary** (25 connections) — `tools/audio/music_library.py`
- **test_music_library.py** (21 connections) — `tests/tools/test_music_library.py`
- **_make_track()** (6 connections) — `tests/tools/test_music_library.py`
- **.execute()** (6 connections) — `tools/audio/music_library.py`
- **._library_dir()** (5 connections) — `tools/audio/music_library.py`
- **test_status_available_with_tracks()** (4 connections) — `tests/tools/test_music_library.py`
- **test_status_ignores_non_audio_files()** (4 connections) — `tests/tools/test_music_library.py`
- **.get_status()** (4 connections) — `tools/audio/music_library.py`
- **._list_tracks()** (4 connections) — `tools/audio/music_library.py`
- **._probe_duration()** (4 connections) — `tools/audio/music_library.py`
- **test_contract_metadata()** (3 connections) — `tests/tools/test_music_library.py`
- **test_execute_input_dir_overrides_env()** (3 connections) — `tests/tools/test_music_library.py`
- **test_execute_lists_tracks_sorted()** (3 connections) — `tests/tools/test_music_library.py`
- **test_status_unavailable_when_dir_empty()** (3 connections) — `tests/tools/test_music_library.py`
- **test_status_unavailable_when_dir_missing()** (3 connections) — `tests/tools/test_music_library.py`
- **Any** (3 connections)
- **Path** (3 connections)
- **test_execute_empty_library()** (2 connections) — `tests/tools/test_music_library.py`
- **.estimate_runtime()** (2 connections) — `tools/audio/music_library.py`
- **Path** (1 connections)
- **Tests for the music_library tool. Covers the tool contract, registry discovery,…** (1 connections) — `tests/tools/test_music_library.py`
- **Best-effort track duration via ffprobe; None if unavailable.** (1 connections) — `tools/audio/music_library.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (21 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)
- [Tool Registry Discovery](Tool_Registry_Discovery.md) (1 shared connections)

## Source Files

- `tests/tools/test_music_library.py`
- `tools/audio/music_library.py`

## Audit Trail

- EXTRACTED: 56 (81%)
- INFERRED: 13 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*