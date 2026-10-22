# Pipeline Checkpoints

> 76 nodes · cohesion 0.06

## Key Concepts

- **write_checkpoint()** (63 connections) — `lib/checkpoint.py`
- **checkpoint.py** (49 connections) — `lib/checkpoint.py`
- **test_08_end_to_end.py** (30 connections) — `tests/qa/test_08_end_to_end.py`
- **sample_artifact()** (26 connections) — `tests/contracts/test_phase0_contracts.py`
- **read_checkpoint()** (16 connections) — `lib/checkpoint.py`
- **validate_checkpoint()** (15 connections) — `lib/checkpoint.py`
- **get_pipeline_stages()** (13 connections) — `lib/checkpoint.py`
- **get_next_stage()** (12 connections) — `lib/checkpoint.py`
- **test_checkpoint_noncanonical_stage.py** (12 connections) — `tests/lib/test_checkpoint_noncanonical_stage.py`
- **get_completed_stages()** (11 connections) — `lib/checkpoint.py`
- **Path** (11 connections)
- **_enforce_stage_prerequisites()** (10 connections) — `lib/checkpoint.py`
- **test_checkpoint_resume_identity.py** (10 connections) — `tests/lib/test_checkpoint_resume_identity.py`
- **TestCheckpoint** (9 connections) — `tests/contracts/test_phase0_contracts.py`
- **_stage_requires_approval()** (9 connections) — `lib/checkpoint.py`
- **TestGateEnforcement** (8 connections) — `tests/contracts/test_backlot_contract.py`
- **load_pipeline_readonly()** (8 connections) — `lib/pipeline_loader.py`
- **_merge_decision_log()** (7 connections) — `lib/checkpoint.py`
- **_validate_style_playbook()** (7 connections) — `lib/checkpoint.py`
- **Any** (7 connections)
- **get_latest_checkpoint()** (6 connections) — `lib/checkpoint.py`
- **_approve_predecessors()** (6 connections) — `tests/contracts/test_backlot_contract.py`
- **_archive_superseded_checkpoint()** (5 connections) — `lib/checkpoint.py`
- **_checkpoint_path()** (5 connections) — `lib/checkpoint.py`
- **_validate_artifacts_for_stage()** (5 connections) — `lib/checkpoint.py`
- *... and 51 more nodes in this community*

## Relationships

- [Project Init](Project_Init.md) (44 shared connections)
- [Event Stream](Event_Stream.md) (16 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (14 shared connections)
- [Core Utilities](Core_Utilities.md) (14 shared connections)
- [Media Review](Media_Review.md) (9 shared connections)
- [Gate Scenario Tests](Gate_Scenario_Tests.md) (8 shared connections)
- [Playbook Generator](Playbook_Generator.md) (7 shared connections)
- [UI Bug Bash Tests](UI_Bug_Bash_Tests.md) (7 shared connections)
- [Playbook Validation](Playbook_Validation.md) (5 shared connections)
- [Tool Testing](Tool_Testing.md) (2 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (2 shared connections)
- [Audio Mixing](Audio_Mixing.md) (2 shared connections)

## Source Files

- `lib/checkpoint.py`
- `lib/pipeline_loader.py`
- `tests/contracts/test_backlot_contract.py`
- `tests/contracts/test_phase0_contracts.py`
- `tests/lib/test_checkpoint_noncanonical_stage.py`
- `tests/lib/test_checkpoint_resume_identity.py`
- `tests/qa/test_08_end_to_end.py`

## Audit Trail

- EXTRACTED: 306 (99%)
- INFERRED: 3 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*