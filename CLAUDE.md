# CLAUDE.md

## Operations Manager Profiler

### Stack
- FastAPI + Uvicorn + httpx
- Supabase (REST API via httpx)
- Anthropic Claude API for AI features
- Single-file backend (main.py) + HTML pages

### Development
```bash
uvicorn main:app --reload --port 8001
```

### Pages
- `/` -- Landing + Assessment (6 dimensions)
- `/games` -- 3 mini-games (delegation, crisis, team building)
- `/academy` -- Mastery-gated course (psychological safety, delegation, feedback)

### 6 Management Dimensions
PeopleBuilder, ProcessArchitect, StrategicThinker, ChangeDriver, CultureKeeper, ResultsDriver
