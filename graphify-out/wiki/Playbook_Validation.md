# Playbook Validation

> 20 nodes · cohesion 0.16

## Key Concepts

- **load_playbook()** (22 connections) — `styles/playbook_loader.py`
- **list_playbooks()** (14 connections) — `styles/playbook_loader.py`
- **parametrize** (8 connections)
- **TestStylePlaybooks** (7 connections) — `tests/contracts/test_phase3_contracts.py`
- **TestSkillsExist** (5 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_color_palette_complete()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_compatible_with_manifest()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_has_required_sections()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_loads_and_validates()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_pacing_rules_present()** (3 connections) — `tests/contracts/test_phase3_contracts.py`
- **test_premium_minimalist_playbook_exists_and_validates()** (3 connections) — `tests/contracts/test_taste_governance_contracts.py`
- **.test_director_skills_exist()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_director_skills_have_required_sections()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_meta_skills_exist()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_meta_skills_have_required_sections()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **.test_all_listed()** (2 connections) — `tests/contracts/test_phase3_contracts.py`
- **Path** (2 connections)
- **Any** (1 connections)
- **Load and validate a style playbook by name. Presets live directly in the styles…** (1 connections) — `styles/playbook_loader.py`
- **List all available playbook names (presets + generated custom ones).** (1 connections) — `styles/playbook_loader.py`

## Relationships

- [Pipeline Checkpoints](Pipeline_Checkpoints.md) (5 shared connections)
- [Playbook Generator](Playbook_Generator.md) (5 shared connections)
- [Playbook Loader](Playbook_Loader.md) (5 shared connections)
- [Tool Contracts](Tool_Contracts.md) (4 shared connections)
- [Project Init](Project_Init.md) (3 shared connections)
- [Video Composition](Video_Composition.md) (2 shared connections)
- [Theme Text Contrast Tests](Theme_Text_Contrast_Tests.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [Pipeline Loader](Pipeline_Loader.md) (1 shared connections)

## Source Files

- `styles/playbook_loader.py`
- `tests/contracts/test_phase3_contracts.py`
- `tests/contracts/test_taste_governance_contracts.py`

## Audit Trail

- EXTRACTED: 58 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*