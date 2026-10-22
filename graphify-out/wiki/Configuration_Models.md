# Configuration Models

> 77 nodes · cohesion 0.06

## Key Concepts

- **CostTracker** (36 connections) — `tools/cost_tracker.py`
- **config_model.py** (17 connections) — `lib/config_model.py`
- **.reserve()** (16 connections) — `tools/cost_tracker.py`
- **cost_tracker.py** (16 connections) — `tools/cost_tracker.py`
- **.estimate()** (12 connections) — `tools/cost_tracker.py`
- **.reconcile()** (10 connections) — `tools/cost_tracker.py`
- **test_cost_tracker_governance.py** (9 connections) — `tests/tools/test_cost_tracker_governance.py`
- **BudgetMode** (8 connections) — `lib/config_model.py`
- **OpenMontageConfig** (8 connections) — `lib/config_model.py`
- **._save()** (8 connections) — `tools/cost_tracker.py`
- **TestCostTracker** (7 connections) — `tests/contracts/test_phase0_contracts.py`
- **CostTrackerGovernanceTests** (7 connections) — `tests/tools/test_cost_tracker_governance.py`
- **.budget_spent_usd()** (7 connections) — `tools/cost_tracker.py`
- **.test_estimate_reserve_reconcile()** (7 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_completed_entry_cannot_be_refunded()** (7 connections) — `tests/tools/test_cost_tracker_governance.py`
- **.refund()** (7 connections) — `tools/cost_tracker.py`
- **BudgetExceededError** (6 connections) — `tools/cost_tracker.py`
- **.test_persistence()** (6 connections) — `tests/contracts/test_phase0_contracts.py`
- **._require_status()** (6 connections) — `tools/cost_tracker.py`
- **BaseModel** (6 connections)
- **ApprovalRequiredError** (5 connections) — `tools/cost_tracker.py`
- **.budget_remaining_usd()** (5 connections) — `tools/cost_tracker.py`
- **.budget_reserved_usd()** (5 connections) — `tools/cost_tracker.py`
- **.test_cap_mode_blocks_overspend()** (5 connections) — `tests/contracts/test_phase0_contracts.py`
- **.test_approved_tools_persist_across_tracker_restarts()** (5 connections) — `tests/tools/test_cost_tracker_governance.py`
- *... and 52 more nodes in this community*

## Relationships

- [Pipeline Loader](Pipeline_Loader.md) (8 shared connections)
- [Core Utilities](Core_Utilities.md) (5 shared connections)
- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Pipeline Checkpoints](Pipeline_Checkpoints.md) (2 shared connections)
- [Playbook Generator](Playbook_Generator.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)
- [Tool Status Checks](Tool_Status_Checks.md) (1 shared connections)
- [Event Stream](Event_Stream.md) (1 shared connections)

## Source Files

- `lib/config_model.py`
- `tests/contracts/test_phase0_contracts.py`
- `tests/tools/test_cost_tracker_governance.py`
- `tools/cost_tracker.py`

## Audit Trail

- EXTRACTED: 155 (83%)
- INFERRED: 32 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*