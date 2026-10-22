# Video Stitching Tests

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

- [Clip Concatenation](Clip_Concatenation.md) (5 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Environment Loader](Environment_Loader.md) (1 shared connections)

## Source Files

- `tests/contracts/test_video_stitch_workspaces.py`

## Audit Trail

- EXTRACTED: 17 (77%)
- INFERRED: 5 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*