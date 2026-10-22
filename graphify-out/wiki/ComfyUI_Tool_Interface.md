# ComfyUI Tool Interface

> 25 nodes · cohesion 0.11

## Key Concepts

- **ComfyUIError** (25 connections) — `tools/_comfyui/client.py`
- **.generate()** (11 connections) — `tools/_comfyui/client.py`
- **._history_entry()** (6 connections) — `tools/_comfyui/client.py`
- **.poll()** (6 connections) — `tools/_comfyui/client.py`
- **.wait_ws()** (6 connections) — `tools/_comfyui/client.py`
- **._wait()** (5 connections) — `tools/_comfyui/client.py`
- **.download()** (4 connections) — `tools/_comfyui/client.py`
- **._history_entry_if_reachable()** (4 connections) — `tools/_comfyui/client.py`
- **.submit()** (4 connections) — `tools/_comfyui/client.py`
- **.upload_image()** (4 connections) — `tools/_comfyui/client.py`
- **Path** (4 connections)
- **fake_generate()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **fake_generate()** (2 connections) — `tests/contracts/test_comfyui_tools.py`
- **.__init__()** (1 connections) — `tools/_comfyui/client.py`
- **Exception** (1 connections)
- **Queue a workflow for execution. Returns the ``prompt_id``.** (1 connections) — `tools/_comfyui/client.py`
- **Block until *prompt_id* finishes. Returns the history entry.** (1 connections) — `tools/_comfyui/client.py`
- **Raised when ComfyUI returns an error or times out. ``prompt_id`` is set when…** (1 connections) — `tools/_comfyui/client.py`
- **Return a completed history entry, or ``None`` while it is absent.** (1 connections) — `tools/_comfyui/client.py`
- **Best-effort history probe while the websocket remains usable.** (1 connections) — `tools/_comfyui/client.py`
- **Block until *prompt_id* finishes, watching ComfyUI's websocket feed. Reacts to…** (1 connections) — `tools/_comfyui/client.py`
- **Wait for *prompt_id*, preferring the websocket feed over polling. Falls back to…** (1 connections) — `tools/_comfyui/client.py`
- **Download an output artifact from the ComfyUI server.** (1 connections) — `tools/_comfyui/client.py`
- **Upload a local image so it can be referenced by LoadImage nodes. Returns the…** (1 connections) — `tools/_comfyui/client.py`
- **Submit → wait → download. Returns list of artifact paths. Pass…** (1 connections) — `tools/_comfyui/client.py`

## Relationships

- [SaveAudio Tests](SaveAudio_Tests.md) (10 shared connections)
- [Custom Workflow](Custom_Workflow.md) (7 shared connections)
- [Workflow Testing](Workflow_Testing.md) (4 shared connections)
- [Tool Testing](Tool_Testing.md) (4 shared connections)
- [ComfyUI Music](ComfyUI_Music.md) (4 shared connections)
- [ComfyUI Tests](ComfyUI_Tests.md) (2 shared connections)

## Source Files

- `tests/contracts/test_comfyui_tools.py`
- `tools/_comfyui/client.py`

## Audit Trail

- EXTRACTED: 52 (83%)
- INFERRED: 11 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*