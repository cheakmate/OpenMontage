# Audio Task Client

> 10 nodes · cohesion 0.27

## Key Concepts

- **.execute()** (8 connections) — `tools/audio/suno_music.py`
- **._download()** (5 connections) — `tools/audio/suno_music.py`
- **._submit()** (4 connections) — `tools/audio/suno_music.py`
- **Any** (4 connections)
- **.estimate_cost()** (3 connections) — `tools/audio/suno_music.py`
- **._poll()** (3 connections) — `tools/audio/suno_music.py`
- **Path** (1 connections)
- **Submit a generation request and return the taskId.** (1 connections) — `tools/audio/suno_music.py`
- **Poll for task completion and return the result data.** (1 connections) — `tools/audio/suno_music.py`
- **Download the audio file to the output path.** (1 connections) — `tools/audio/suno_music.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (6 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)

## Source Files

- `tools/audio/suno_music.py`

## Audit Trail

- EXTRACTED: 19 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*