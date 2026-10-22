# Math Animate Safety Scan

> 35 nodes · cohesion 0.12

## Key Concepts

- **MathAnimate** (34 connections) — `tools/graphics/math_animate.py`
- **test_math_animate_safety.py** (18 connections) — `tests/tools/test_math_animate_safety.py`
- **._scan_scene_code()** (14 connections) — `tools/graphics/math_animate.py`
- **._render()** (9 connections) — `tools/graphics/math_animate.py`
- **._probe_output()** (5 connections) — `tools/graphics/math_animate.py`
- **Any** (5 connections)
- **test_blocks_dangerous_calls()** (4 connections) — `tests/tools/test_math_animate_safety.py`
- **test_blocks_dangerous_imports()** (4 connections) — `tests/tools/test_math_animate_safety.py`
- **._cleanup()** (4 connections) — `tools/graphics/math_animate.py`
- **.execute()** (4 connections) — `tools/graphics/math_animate.py`
- **._find_output()** (4 connections) — `tools/graphics/math_animate.py`
- **test_blocks_aliased_dangerous_builtin()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_blocks_builtins_module_via_print_self()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_blocks_getattr_reflection_bypass()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_blocks_no_import_builtins_secret_read()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_blocks_sandbox_escape_dunders()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_execute_blocks_dangerous_code_before_running_manim()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_safe_scene_passes_scan()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_super_init_is_allowed()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **test_syntax_error_defers_to_manim()** (3 connections) — `tests/tools/test_math_animate_safety.py`
- **._detect_scene_name()** (3 connections) — `tools/graphics/math_animate.py`
- **Path** (3 connections)
- **test_allow_unsafe_code_bypasses_scan()** (2 connections) — `tests/tools/test_math_animate_safety.py`
- **_is_blocked_dunder()** (2 connections) — `tools/graphics/math_animate.py`
- **.estimate_cost()** (2 connections) — `tools/graphics/math_animate.py`
- *... and 10 more nodes in this community*

## Relationships

- [Tool Base Runtime](Tool_Base_Runtime.md) (14 shared connections)
- [Character Animation Tests](Character_Animation_Tests.md) (3 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Lyria BGM Generator](Lyria_BGM_Generator.md) (1 shared connections)

## Source Files

- `tests/tools/test_math_animate_safety.py`
- `tools/graphics/math_animate.py`

## Audit Trail

- EXTRACTED: 68 (77%)
- INFERRED: 20 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*