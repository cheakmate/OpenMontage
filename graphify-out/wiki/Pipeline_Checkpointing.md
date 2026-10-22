# Pipeline Checkpointing

> 63 nodes · cohesion 0.08

## Key Concepts

- **write_checkpoint()** (63 connections) — `lib/checkpoint.py`
- **checkpoint.py** (49 connections) — `lib/checkpoint.py`
- **sample_artifact()** (26 connections) — `tests/contracts/test_phase0_contracts.py`
- **test_backlot_contract.py** (22 connections) — `tests/contracts/test_backlot_contract.py`
- **read_checkpoint()** (16 connections) — `lib/checkpoint.py`
- **validate_checkpoint()** (15 connections) — `lib/checkpoint.py`
- **get_pipeline_stages()** (13 connections) — `lib/checkpoint.py`
- **get_next_stage()** (12 connections) — `lib/checkpoint.py`
- **get_completed_stages()** (11 connections) — `lib/checkpoint.py`
- **Path** (11 connections)
- **_enforce_stage_prerequisites()** (10 connections) — `lib/checkpoint.py`
- **test_checkpoint_resume_identity.py** (10 connections) — `tests/lib/test_checkpoint_resume_identity.py`
- **TestCheckpoint** (9 connections) — `tests/contracts/test_phase0_contracts.py`
- **_stage_requires_approval()** (9 connections) — `lib/checkpoint.py`
- **TestGateEnforcement** (8 connections) — `tests/contracts/test_backlot_contract.py`
- **_merge_decision_log()** (7 connections) — `lib/checkpoint.py`
- **Any** (7 connections)
- **get_latest_checkpoint()** (6 connections) — `lib/checkpoint.py`
- **_approve_predecessors()** (6 connections) — `tests/contracts/test_backlot_contract.py`
- **_archive_superseded_checkpoint()** (5 connections) — `lib/checkpoint.py`
- **_checkpoint_path()** (5 connections) — `lib/checkpoint.py`
- **_validate_artifacts_for_stage()** (5 connections) — `lib/checkpoint.py`
- **_minimal_script()** (5 connections) — `tests/contracts/test_backlot_contract.py`
- **.test_overwrite_archives_previous()** (5 connections) — `tests/contracts/test_backlot_contract.py`
- **test_matching_pipeline_completion_is_retained()** (5 connections) — `tests/lib/test_checkpoint_resume_identity.py`
- *... and 38 more nodes in this community*

## Relationships

- [Project Init Validation](Project_Init_Validation.md) (38 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (21 shared connections)
- [Event Logging](Event_Logging.md) (15 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (13 shared connections)
- [Backlot Screenshot Capture](Backlot_Screenshot_Capture.md) (13 shared connections)
- [Pipeline Gate Tests](Pipeline_Gate_Tests.md) (8 shared connections)
- [Playbook Generation](Playbook_Generation.md) (7 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (6 shared connections)
- [Playbook Loading Tests](Playbook_Loading_Tests.md) (3 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (1 shared connections)

## Source Files

- `lib/checkpoint.py`
- `lib/pipeline_loader.py`
- `tests/contracts/test_backlot_contract.py`
- `tests/contracts/test_phase0_contracts.py`
- `tests/lib/test_checkpoint_resume_identity.py`

## Audit Trail

- EXTRACTED: 273 (99%)
- INFERRED: 2 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*