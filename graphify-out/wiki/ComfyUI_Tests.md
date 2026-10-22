# ComfyUI Tests

> 38 nodes · cohesion 0.07

## Key Concepts

- **test_comfyui_tools.py** (48 connections) — `tests/contracts/test_comfyui_tools.py`
- **TestWebsocketWait** (10 connections) — `tests/contracts/test_comfyui_tools.py`
- **_install_fake_websocket()** (10 connections) — `tests/contracts/test_comfyui_tools.py`
- **_FakeWSConn** (6 connections) — `tests/contracts/test_comfyui_tools.py`
- **TestModelRequirements** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_wait_does_not_swallow_genuine_comfyuierror_from_websocket()** (5 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_wait_falls_back_to_poll_when_websocket_unavailable()** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **_FakeWSTimeout** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **_raise_on_websocket_import()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_t2v_builder_patches_frame_count_into_length_not_batch_size()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_wait_ws_completes_on_executing_none_node()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_wait_ws_execution_error_raises_with_prompt_id()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_wait_ws_ignores_other_prompts_on_shared_connection()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_wait_ws_returns_job_completed_before_connection()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_wait_ws_timeout_raises_comfyuierror_with_prompt_id()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.recv()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_t2v_workflow_latent_is_temporal_not_an_image_batch()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.close()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.__init__()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **.settimeout()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **_import()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_flux2_workflow_has_templated_nodes()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_i2v_workflow_has_templated_nodes()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_t2v_metadata_stack_uses_14b_compatible_vae()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- **test_t2v_workflow_has_templated_nodes()** (1 connections) — `tests/contracts/test_comfyui_tools.py`
- *... and 13 more nodes in this community*

## Relationships

- [SaveAudio Tests](SaveAudio_Tests.md) (12 shared connections)
- [Core Utilities](Core_Utilities.md) (6 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [Custom Workflow](Custom_Workflow.md) (3 shared connections)
- [Workflow Testing](Workflow_Testing.md) (3 shared connections)
- [Image Selector](Image_Selector.md) (3 shared connections)
- [ComfyUI Tool Interface](ComfyUI_Tool_Interface.md) (2 shared connections)
- [Tool Execution](Tool_Execution.md) (2 shared connections)
- [ComfyUI Music](ComfyUI_Music.md) (2 shared connections)
- [Tool Registry](Tool_Registry.md) (2 shared connections)
- [Atlas Provider Tests](Atlas_Provider_Tests.md) (2 shared connections)
- [Video Tool Readiness](Video_Tool_Readiness.md) (2 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`

## Audit Trail

- EXTRACTED: 87 (96%)
- INFERRED: 4 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*