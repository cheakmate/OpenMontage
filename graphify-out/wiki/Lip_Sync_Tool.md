# Lip Sync Tool

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

- [Tool Base Runtime](Tool_Base_Runtime.md) (10 shared connections)
- [Kling Avatar LipSync Tests](Kling_Avatar_LipSync_Tests.md) (2 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (2 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (1 shared connections)

## Source Files

- `tools/avatar/lip_sync.py`

## Audit Trail

- EXTRACTED: 18 (69%)
- INFERRED: 8 (31%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*