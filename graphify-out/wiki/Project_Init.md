# Project Init

> 43 nodes · cohesion 0.09

## Key Concepts

- **pytest** (115 connections)
- **CheckpointValidationError** (27 connections) — `lib/checkpoint.py`
- **init_project()** (24 connections) — `lib/checkpoint.py`
- **test_backlot_contract.py** (22 connections) — `tests/contracts/test_backlot_contract.py`
- **test_checkpoint_prerequisites.py** (15 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_decision_log_approval_policy.py** (14 connections) — `tests/lib/test_decision_log_approval_policy.py`
- **test_checkpoint_decision_validation.py** (11 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_playbook_catalog.py** (11 connections) — `tests/styles/test_playbook_catalog.py`
- **test_later_stage_rejects_unapproved_gated_predecessor()** (8 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_rejected_checkpoint_keeps_prior_decisions()** (7 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_malformed_predecessor_cannot_forge_completion()** (7 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_later_stage_cannot_skip_a_missing_predecessor()** (6 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_rejected_first_write_does_not_create_a_decision_log()** (5 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_marker_derived_unknown_playbook_blocks_later_writes()** (5 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **decision_log()** (4 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **test_accepted_write_merges_new_decisions_and_deduplicates_replay()** (4 connections) — `tests/lib/test_checkpoint_decision_validation.py`
- **_script_artifact()** (4 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **test_unknown_style_playbook_fails_before_project_creation()** (4 connections) — `tests/lib/test_checkpoint_prerequisites.py`
- **_decision_log()** (4 connections) — `tests/lib/test_decision_log_approval_policy.py`
- **test_checkpoint_accepts_approval_policy_decision_log()** (4 connections) — `tests/lib/test_decision_log_approval_policy.py`
- **test_unknown_category_still_rejected()** (4 connections) — `tests/lib/test_decision_log_approval_policy.py`
- **test_listed_playbook_is_accepted_by_init_project()** (4 connections) — `tests/styles/test_playbook_catalog.py`
- **test_listed_playbook_loads_and_validates()** (4 connections) — `tests/styles/test_playbook_catalog.py`
- **TestInitProject** (3 connections) — `tests/contracts/test_backlot_contract.py`
- **test_optional_live_doc_snapshot_check()** (3 connections) — `tests/contracts/test_kling_official_core.py`
- *... and 18 more nodes in this community*

## Relationships

- [Pipeline Checkpoints](Pipeline_Checkpoints.md) (44 shared connections)
- [Core Utilities](Core_Utilities.md) (16 shared connections)
- [Event Stream](Event_Stream.md) (10 shared connections)
- [Media Review](Media_Review.md) (7 shared connections)
- [Playbook Generator](Playbook_Generator.md) (6 shared connections)
- [Gate Scenario Tests](Gate_Scenario_Tests.md) (4 shared connections)
- [API Testing](API_Testing.md) (4 shared connections)
- [Audio Mixing](Audio_Mixing.md) (4 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (3 shared connections)
- [UI Bug Bash Tests](UI_Bug_Bash_Tests.md) (3 shared connections)
- [Playbook Validation](Playbook_Validation.md) (3 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)

## Source Files

- `lib/checkpoint.py`
- `tests/contracts/test_backlot_contract.py`
- `tests/contracts/test_kling_official_core.py`
- `tests/lib/test_checkpoint_decision_validation.py`
- `tests/lib/test_checkpoint_prerequisites.py`
- `tests/lib/test_decision_log_approval_policy.py`
- `tests/styles/test_playbook_catalog.py`

## Audit Trail

- EXTRACTED: 253 (95%)
- INFERRED: 12 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*