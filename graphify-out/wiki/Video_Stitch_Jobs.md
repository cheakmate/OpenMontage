# Video Stitch Jobs

> 9 nodes · cohesion 0.36

## Key Concepts

- **test_video_stitch_workspaces.py** (10 connections) — `tests/contracts/test_video_stitch_workspaces.py`
- **test_failed_encoding_removes_partial_intermediates()** (6 connections) — `tests/contracts/test_video_stitch_workspaces.py`
- **test_overlapping_jobs_keep_their_own_intermediates()** (6 connections) — `tests/contracts/test_video_stitch_workspaces.py`
- **stub_probe()** (4 connections) — `tests/contracts/test_video_stitch_workspaces.py`
- **prepare_job()** (3 connections) — `tests/contracts/test_video_stitch_workspaces.py`
- **run_command()** (2 connections) — `tests/contracts/test_video_stitch_workspaces.py`
- **parametrize** (2 connections)
- **fail_encoding()** (1 connections) — `tests/contracts/test_video_stitch_workspaces.py`
- **Stitch jobs sharing an output folder must not share intermediate files.** (1 connections) — `tests/contracts/test_video_stitch_workspaces.py`

## Relationships

- [Clip Preflight](Clip_Preflight.md) (5 shared connections)
- [Core Utilities](Core_Utilities.md) (2 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Audio Mixing](Audio_Mixing.md) (1 shared connections)

## Source Files

- `tests/contracts/test_video_stitch_workspaces.py`

## Audit Trail

- EXTRACTED: 17 (77%)
- INFERRED: 5 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*