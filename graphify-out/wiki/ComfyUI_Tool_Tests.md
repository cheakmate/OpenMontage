# ComfyUI Tool Tests

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

- [Tool Base Runtime](Tool_Base_Runtime.md) (14 shared connections)
- [ComfyUI Client Helpers](ComfyUI_Client_Helpers.md) (12 shared connections)
- [ComfyUI Video Workflow Tests](ComfyUI_Video_Workflow_Tests.md) (3 shared connections)
- [Image Selector Tests](Image_Selector_Tests.md) (3 shared connections)
- [Comfy Video Selector](Comfy_Video_Selector.md) (3 shared connections)
- [ComfyUI Generation Client](ComfyUI_Generation_Client.md) (2 shared connections)
- [ComfyUI Music Tests](ComfyUI_Music_Tests.md) (2 shared connections)
- [Workflow Contract Tests](Workflow_Contract_Tests.md) (2 shared connections)
- [Project Init Validation](Project_Init_Validation.md) (1 shared connections)
- [Workflow Patching](Workflow_Patching.md) (1 shared connections)
- [Tool Registry Discovery Tests](Tool_Registry_Discovery_Tests.md) (1 shared connections)
- [ComfyUI Setup Registry](ComfyUI_Setup_Registry.md) (1 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`

## Audit Trail

- EXTRACTED: 87 (96%)
- INFERRED: 4 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*