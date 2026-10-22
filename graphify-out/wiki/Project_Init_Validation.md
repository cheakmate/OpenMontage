# Project Init Validation

> 36 nodes · cohesion 0.11

## Key Concepts

- **pytest** (115 connections)
- **CheckpointValidationError** (27 connections) — `lib/checkpoint.py`
- **init_project()** (24 connections) — `lib/checkpoint.py`
- **test_checkpoint_prerequisites.py** (15 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_checkpoint_noncanonical_stage.py** (12 connections) — `tests/lib/test_checkpoint_noncanonical_stage.py`
- **test_checkpoint_decision_validation.py** (11 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_later_stage_rejects_unapproved_gated_predecessor()** (8 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **_validate_style_playbook()** (7 connections) — `lib/checkpoint.py`
- **test_rejected_checkpoint_keeps_prior_decisions()** (7 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_malformed_predecessor_cannot_forge_completion()** (7 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_later_stage_cannot_skip_a_missing_predecessor()** (6 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_rejected_first_write_does_not_create_a_decision_log()** (5 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_canonical_stage_still_requires_its_artifact()** (5 connections) — `tests/lib/test_checkpoint_noncanonical_stage.py`
- **test_marker_derived_unknown_playbook_blocks_later_writes()** (5 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **decision_log()** (4 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_accepted_write_merges_new_decisions_and_deduplicates_replay()** (4 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **_script_artifact()** (4 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_unknown_style_playbook_fails_before_project_creation()** (4 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_utf8_file_io.py** (4 connections) — `tests/contracts/test_utf8_file_io.py`
- **TestInitProject** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **test_pipeline_contract_files_use_explicit_utf8()** (3 connections) — `tests/contracts/test_utf8_file_io.py`
- **_checkpoint()** (3 connections) — `tests/lib/test_checkpoint_noncanonical_stage.py`
- **test_noncanonical_stage_does_not_raise_keyerror()** (3 connections) — `tests/lib/test_checkpoint_noncanonical_stage.py`
- **test_in_progress_heartbeat_is_not_blocked_by_prerequisites()** (3 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **ast** (3 connections)
- *... and 11 more nodes in this community*

## Relationships

- [Pipeline Checkpointing](Pipeline_Checkpointing.md) (38 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (20 shared connections)
- [Artifact Schema Validation](Artifact_Schema_Validation.md) (8 shared connections)
- [Kling Client Tests](Kling_Client_Tests.md) (6 shared connections)
- [Environment Loader](Environment_Loader.md) (6 shared connections)
- [Backlot Screenshot Capture](Backlot_Screenshot_Capture.md) (5 shared connections)
- [Playbook Loading Tests](Playbook_Loading_Tests.md) (5 shared connections)
- [Pipeline Gate Tests](Pipeline_Gate_Tests.md) (4 shared connections)
- [Remotion Theme Tests](Remotion_Theme_Tests.md) (4 shared connections)
- [HyperFrames Render Tests](HyperFrames_Render_Tests.md) (3 shared connections)
- [Stock Adapter Tests](Stock_Adapter_Tests.md) (3 shared connections)
- [Event Logging](Event_Logging.md) (2 shared connections)

## Source Files

- `lib/checkpoint.py`
- `tests/contracts/test_backlot_contract.py`
- `tests/contracts/test_utf8_file_io.py`
- `tests/lib/test_checkpoint_decision_validation.py`
- `tests/lib/test_checkpoint_noncanonical_stage.py`
- `tests/lib/test_checkpoint_prerequisites.py`

## Audit Trail

- EXTRACTED: 225 (95%)
- INFERRED: 12 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*