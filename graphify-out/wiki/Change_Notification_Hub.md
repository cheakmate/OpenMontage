# Change Notification Hub

> 7 nodes · cohesion 0.33

## Key Concepts

- **ChangeHub** (6 connections) — `backlot/server.py`
- **.subscribe()** (2 connections) — `backlot/server.py`
- **.unsubscribe()** (2 connections) — `backlot/server.py`
- **Queue** (2 connections)
- **.__init__()** (1 connections) — `backlot/server.py`
- **.publish()** (1 connections) — `backlot/server.py`
- **Fan-out of project-change notifications to SSE subscribers. Subscriptions are…** (1 connections) — `backlot/server.py`

## Relationships

- [Board Server Pages](Board_Server_Pages.md) (1 shared connections)

## Source Files

- `backlot/server.py`

## Audit Trail

- EXTRACTED: 8 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*