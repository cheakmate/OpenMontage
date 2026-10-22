# Backlot CLI

> 10 nodes · cohesion 0.36

## Key Concepts

- **__main__.py** (15 connections) — `backlot/__main__.py`
- **cmd_open()** (7 connections) — `backlot/__main__.py`
- **main()** (5 connections) — `backlot/__main__.py`
- **_spawn_server()** (4 connections) — `backlot/__main__.py`
- **_port()** (3 connections) — `backlot/__main__.py`
- **cmd_serve()** (2 connections) — `backlot/__main__.py`
- **_server_alive()** (2 connections) — `backlot/__main__.py`
- **webbrowser** (2 connections)
- **Backlot CLI. python -m backlot open [project-id] # start server if needed, open…** (1 connections) — `backlot/__main__.py`
- **Start the server as a detached background process.** (1 connections) — `backlot/__main__.py`

## Relationships

- [Tool Testing](Tool_Testing.md) (3 shared connections)
- [Lyria BGM Generation](Lyria_BGM_Generation.md) (3 shared connections)
- [Audio Mixing](Audio_Mixing.md) (2 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [Backlot Project Management](Backlot_Project_Management.md) (1 shared connections)

## Source Files

- `backlot/__main__.py`

## Audit Trail

- EXTRACTED: 26 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*