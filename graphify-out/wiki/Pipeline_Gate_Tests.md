# Pipeline Gate Tests

> 11 nodes · cohesion 0.29

## Key Concepts

- **test_gate_scenarios.py** (19 connections) — `tests/backlot/test_gate_scenarios.py`
- **test_awaiting_then_approved_archives_history_without_gate_skip()** (5 connections) — `tests/backlot/test_gate_scenarios.py`
- **_approve_predecessors()** (4 connections) — `tests/backlot/test_gate_scenarios.py`
- **_script_artifact()** (4 connections) — `tests/backlot/test_gate_scenarios.py`
- **test_completed_gated_stage_without_approval_is_rejected()** (4 connections) — `tests/backlot/test_gate_scenarios.py`
- **test_handwritten_completed_checkpoint_surfaces_gate_skip()** (4 connections) — `tests/backlot/test_gate_scenarios.py`
- **test_typo_pipeline_type_fails_closed()** (4 connections) — `tests/backlot/test_gate_scenarios.py`
- **_write()** (3 connections) — `tests/backlot/test_gate_scenarios.py`
- **_manifest_artifact()** (2 connections) — `tests/backlot/test_gate_scenarios.py`
- **Path** (1 connections)
- **Gate-integrity scenarios for Backlot and checkpoint hardening.** (1 connections) — `tests/backlot/test_gate_scenarios.py`

## Relationships

- [Pipeline Checkpointing](Pipeline_Checkpointing.md) (8 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (4 shared connections)
- [Backlot Board State](Backlot_Board_State.md) (3 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (2 shared connections)
- [Backlot Storyboard Server](Backlot_Storyboard_Server.md) (1 shared connections)
- [Storyboard State Management](Storyboard_State_Management.md) (1 shared connections)

## Source Files

- `tests/backlot/test_gate_scenarios.py`

## Audit Trail

- EXTRACTED: 33 (94%)
- INFERRED: 2 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*