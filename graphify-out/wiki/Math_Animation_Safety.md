# Math Animation Safety

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

- [Core Utilities](Core_Utilities.md) (8 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Character Animation](Character_Animation.md) (3 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [Project Init](Project_Init.md) (1 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (1 shared connections)

## Source Files

- `tests/tools/test_math_animate_safety.py`
- `tools/graphics/math_animate.py`

## Audit Trail

- EXTRACTED: 68 (77%)
- INFERRED: 20 (23%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*