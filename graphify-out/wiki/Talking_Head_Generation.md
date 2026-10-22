# Talking Head Generation

> 12 nodes · cohesion 0.27

## Key Concepts

- **TalkingHead** (18 connections) — `tools/avatar/talking_head.py`
- **._run_sadtalker()** (7 connections) — `tools/avatar/talking_head.py`
- **._run_musetalk()** (6 connections) — `tools/avatar/talking_head.py`
- **.execute()** (5 connections) — `tools/avatar/talking_head.py`
- **Any** (5 connections)
- **.get_status()** (3 connections) — `tools/avatar/talking_head.py`
- **.estimate_cost()** (2 connections) — `tools/avatar/talking_head.py`
- **.estimate_runtime()** (2 connections) — `tools/avatar/talking_head.py`
- **Path** (2 connections)
- **Check for SadTalker availability via env var or Python import.** (1 connections) — `tools/avatar/talking_head.py`
- **Run SadTalker inference via subprocess.** (1 connections) — `tools/avatar/talking_head.py`
- **MuseTalk support — placeholder for future implementation.** (1 connections) — `tools/avatar/talking_head.py`

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (10 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (4 shared connections)
- [Kling Avatar LipSync Tests](Kling_Avatar_LipSync_Tests.md) (2 shared connections)
- [Video Review Tooling](Video_Review_Tooling.md) (1 shared connections)

## Source Files

- `tools/avatar/talking_head.py`

## Audit Trail

- EXTRACTED: 27 (77%)
- INFERRED: 8 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*