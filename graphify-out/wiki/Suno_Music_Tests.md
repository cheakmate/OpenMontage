# Suno Music Tests

> 13 nodes · cohesion 0.27

## Key Concepts

- **SunoMusic** (18 connections) — `tools/audio/suno_music.py`
- **.execute()** (8 connections) — `tools/audio/suno_music.py`
- **._download()** (5 connections) — `tools/audio/suno_music.py`
- **._submit()** (4 connections) — `tools/audio/suno_music.py`
- **Any** (4 connections)
- **.estimate_cost()** (3 connections) — `tools/audio/suno_music.py`
- **._get_api_key()** (3 connections) — `tools/audio/suno_music.py`
- **.get_status()** (3 connections) — `tools/audio/suno_music.py`
- **._poll()** (3 connections) — `tools/audio/suno_music.py`
- **Path** (1 connections)
- **Submit a generation request and return the taskId.** (1 connections) — `tools/audio/suno_music.py`
- **Poll for task completion and return the result data.** (1 connections) — `tools/audio/suno_music.py`
- **Download the audio file to the output path.** (1 connections) — `tools/audio/suno_music.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (5 shared connections)
- [Core Utilities](Core_Utilities.md) (4 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)

## Source Files

- `tools/audio/suno_music.py`

## Audit Trail

- EXTRACTED: 25 (74%)
- INFERRED: 9 (26%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*