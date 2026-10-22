# Character Animation

> 79 nodes · cohesion 0.05

## Key Concepts

- **ToolResult** (540 connections) — `tools/base_tool.py`
- **test_character_animation_pipeline.py** (31 connections) — `tests/contracts/test_character_animation_pipeline.py`
- **character_animation.py** (29 connections) — `tools/character/character_animation.py`
- **TalkingHead** (18 connections) — `tools/avatar/talking_head.py`
- **ImageGen** (18 connections) — `tools/graphics/image_gen.py`
- **test_remotion_diagnostics.py** (14 connections) — `tests/tools/test_remotion_diagnostics.py`
- **CharacterSpecGenerator** (13 connections) — `tools/character/character_animation.py`
- **QwenImage21** (13 connections) — `tools/graphics/qwen_image_21.py`
- **ActionTimelineCompiler** (12 connections) — `tools/character/character_animation.py`
- **CharacterAnimationReviewer** (12 connections) — `tools/character/character_animation.py`
- **CharacterRigRenderer** (12 connections) — `tools/character/character_animation.py`
- **PoseLibraryBuilder** (12 connections) — `tools/character/character_animation.py`
- **SvgRigBuilder** (12 connections) — `tools/character/character_animation.py`
- **test_character_renderer_can_handoff_to_video_compose()** (11 connections) — `tests/contracts/test_character_animation_pipeline.py`
- **test_base_tool_dependencies.py** (11 connections) — `tests/tools/test_base_tool_dependencies.py`
- **test_character_animation_smoke_flow()** (8 connections) — `tests/contracts/test_character_animation_pipeline.py`
- **_write_json()** (8 connections) — `tools/character/character_animation.py`
- **.execute()** (8 connections) — `tools/graphics/image_gen.py`
- **Any** (8 connections)
- **DummyTool** (7 connections) — `tests/tools/test_base_tool_dependencies.py`
- **._run_sadtalker()** (7 connections) — `tools/avatar/talking_head.py`
- **._run_musetalk()** (6 connections) — `tools/avatar/talking_head.py`
- **.execute()** (6 connections) — `tools/character/character_animation.py`
- **.execute()** (6 connections) — `tools/character/character_animation.py`
- **BinaryDependencyTests** (5 connections) — `tests/tools/test_base_tool_dependencies.py`
- *... and 54 more nodes in this community*

## Relationships

- [Core Utilities](Core_Utilities.md) (129 shared connections)
- [Tool Testing](Tool_Testing.md) (82 shared connections)
- [Tool Execution](Tool_Execution.md) (35 shared connections)
- [Video Composition](Video_Composition.md) (18 shared connections)
- [Audio Mixing](Audio_Mixing.md) (16 shared connections)
- [HyperFrames Render](HyperFrames_Render.md) (15 shared connections)
- [Tool Status Checks](Tool_Status_Checks.md) (15 shared connections)
- [TTS Provider Tests](TTS_Provider_Tests.md) (12 shared connections)
- [Tool Contracts](Tool_Contracts.md) (11 shared connections)
- [Tool Cache Tests](Tool_Cache_Tests.md) (11 shared connections)
- [Phase Comparison](Phase_Comparison.md) (10 shared connections)
- [Kling Tools](Kling_Tools.md) (8 shared connections)

## Source Files

- `tests/contracts/test_character_animation_pipeline.py`
- `tests/tools/test_base_tool_dependencies.py`
- `tests/tools/test_provider_refresh.py`
- `tests/tools/test_remotion_diagnostics.py`
- `tools/audio/cartesia_tts.py`
- `tools/avatar/talking_head.py`
- `tools/base_tool.py`
- `tools/character/character_animation.py`
- `tools/enhancement/bg_remove.py`
- `tools/enhancement/face_restore.py`
- `tools/graphics/image_gen.py`
- `tools/graphics/qwen_image_21.py`
- `tools/video/showcase_card.py`

## Audit Trail

- EXTRACTED: 606 (75%)
- INFERRED: 199 (25%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*