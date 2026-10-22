# LipSync Processing

> 9 nodes · cohesion 0.31

## Key Concepts

- **LipSync** (16 connections) — `tools/avatar/lip_sync.py`
- **.execute()** (6 connections) — `tools/avatar/lip_sync.py`
- **.get_status()** (4 connections) — `tools/avatar/lip_sync.py`
- **._resolve_wav2lip_dir()** (4 connections) — `tools/avatar/lip_sync.py`
- **.estimate_cost()** (2 connections) — `tools/avatar/lip_sync.py`
- **Any** (2 connections)
- **Path** (1 connections)
- **Check Wav2Lip availability via env var or Python import.** (1 connections) — `tools/avatar/lip_sync.py`
- **Locate the Wav2Lip installation directory.** (1 connections) — `tools/avatar/lip_sync.py`

## Relationships

- [Core Utilities](Core_Utilities.md) (5 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Kling Avatar Tests](Kling_Avatar_Tests.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Character Animation](Character_Animation.md) (2 shared connections)
- [FFmpeg Tests](FFmpeg_Tests.md) (1 shared connections)

## Source Files

- `tools/avatar/lip_sync.py`

## Audit Trail

- EXTRACTED: 18 (69%)
- INFERRED: 8 (31%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*