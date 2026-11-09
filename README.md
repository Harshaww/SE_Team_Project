# SE_Team_Project: YouTube Video Intelligence MCP Server

Cut through YouTube's algorithm noise: an MCP server that builds
constraint-based study playlists (topic, duration, max video length)
from objective metadata.

## Features (planned)
- FR-1 Similar videos
- FR-2 Similar channels
- FR-3 Recommendations
- FR-4 Engagement analysis
- FR-5 Playlist creation (with explicit user confirmation)

## Status
Stage 1: Requirements (in progress)

## Repository layout
- `brain/`: Obsidian vault (PARA). Entry point: `brain/index.md`
- `docs/srs/`: Software Requirements Specification
- `docs/adr/`: Architecture Decision Records
- `skills/`: Agent Skills (one folder per skill, each with a `SKILL.md`)
- `src/`, `tests/`: server code and tests
- `.github/workflows/`: CI

## Branching strategy
- `main` is protected and always stable.
- Work happens on `feature/<issue#>-short-name` branches.
- Every change (code, skills, brain) is merged by pull request with at least one review.
