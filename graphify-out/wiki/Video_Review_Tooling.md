# Video Review Tooling

> 16 nodes · cohesion 0.18

## Key Concepts

- **.run_command()** (77 connections) — `tools/base_tool.py`
- **._audio_levels()** (7 connections) — `tools/analysis/visual_qa.py`
- **._review()** (7 connections) — `tools/analysis/visual_qa.py`
- **.execute()** (6 connections) — `tools/analysis/visual_qa.py`
- **._probe()** (6 connections) — `tools/analysis/visual_qa.py`
- **ToolCommandError** (5 connections) — `tools/base_tool.py`
- **._get_duration()** (4 connections) — `tools/analysis/visual_qa.py`
- **Any** (4 connections)
- **.__init__()** (1 connections) — `tools/base_tool.py`
- **.__str__()** (1 connections) — `tools/base_tool.py`
- **CompletedProcess** (1 connections)
- **Extract frames at specified timestamps for visual review.** (1 connections) — `tools/analysis/visual_qa.py`
- **Probe video metadata and optionally validate against expectations.** (1 connections) — `tools/analysis/visual_qa.py`
- **Check audio levels at specified timestamps.** (1 connections) — `tools/analysis/visual_qa.py`
- **Run a subprocess command with standard error handling. On Windows, resolves…** (1 connections) — `tools/base_tool.py`
- **CalledProcessError with stderr/stdout surfaced in str(error).** (1 connections) — `tools/base_tool.py`

## Relationships

- [Clip Concatenation](Clip_Concatenation.md) (11 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (7 shared connections)
- [Chromakey Green Screen](Chromakey_Green_Screen.md) (7 shared connections)
- [Cinematic Remotion Adapter](Cinematic_Remotion_Adapter.md) (7 shared connections)
- [Audio Mixer Tests](Audio_Mixer_Tests.md) (6 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (5 shared connections)
- [Frame Sampler Tests](Frame_Sampler_Tests.md) (4 shared connections)
- [Frame Compositing](Frame_Compositing.md) (4 shared connections)
- [Silence Cutter](Silence_Cutter.md) (4 shared connections)
- [Enhancement Error Tests](Enhancement_Error_Tests.md) (3 shared connections)
- [Eye Enhancement](Eye_Enhancement.md) (3 shared connections)
- [Face Tracking AutoReframe](Face_Tracking_AutoReframe.md) (3 shared connections)

## Source Files

- `tools/analysis/visual_qa.py`
- `tools/base_tool.py`

## Audit Trail

- EXTRACTED: 102 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*