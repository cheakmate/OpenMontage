# ComfyUI Client Helpers

> 39 nodes · cohesion 0.08

## Key Concepts

- **ComfyUIClient** (59 connections) — `tools/_comfyui/client.py`
- **TestClientHelpers** (17 connections) — `tests/contracts/test_comfyui_tools.py`
- **TestMultiServer** (12 connections) — `tests/contracts/test_comfyui_tools.py`
- **.random_seed()** (6 connections) — `tools/_comfyui/client.py`
- **.unavailable_reason()** (6 connections) — `tools/_comfyui/client.py`
- **.is_default_url()** (5 connections) — `tools/_comfyui/client.py`
- **.test_generate_resume_prompt_id_skips_resubmit()** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_submit_surfaces_node_errors_before_http_error()** (4 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_generate_passes_history_item_type_to_view()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_generate_reads_audio_key_from_savaudio_node()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_submit_includes_client_id_for_websocket_targeting()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_is_default_url_true_only_when_both_vars_unset()** (3 connections) — `tests/contracts/test_comfyui_tools.py`
- **._capability_url()** (3 connections) — `tools/_comfyui/client.py`
- **.__init__()** (3 connections) — `tools/_comfyui/client.py`
- **.test_is_default_url_when_env_not_set()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_is_not_default_url_when_env_set()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_poll_timeout_carries_prompt_id_for_recovery()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_random_seed_range()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_unavailable_reason_custom_url()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_unavailable_reason_default_url()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_capability_env_var_takes_priority_over_shared()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_explicit_server_url_wins_over_capability_env_var()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_falls_back_to_shared_when_capability_var_unset()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_no_capability_behaves_as_before()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.test_other_capability_env_var_does_not_leak_across_tools()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- *... and 14 more nodes in this community*

## Relationships

- [ComfyUI Tool Tests](ComfyUI_Tool_Tests.md) (12 shared connections)
- [Workflow Patching](Workflow_Patching.md) (11 shared connections)
- [ComfyUI Generation Client](ComfyUI_Generation_Client.md) (10 shared connections)
- [ComfyUI Video Workflow Tests](ComfyUI_Video_Workflow_Tests.md) (6 shared connections)
- [Tool Base Runtime](Tool_Base_Runtime.md) (4 shared connections)
- [ComfyUI Music Tests](ComfyUI_Music_Tests.md) (4 shared connections)
- [ComfyUI Model Status](ComfyUI_Model_Status.md) (3 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tools/_comfyui/client.py`
- `tools/audio/comfyui_music.py`
- `tools/video/comfyui_video.py`

## Audit Trail

- EXTRACTED: 94 (85%)
- INFERRED: 16 (15%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*