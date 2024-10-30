# UV Probe
This is a probe of UV — new tooling for Python

- Video here: https://www.youtube.com/watch?v=gSKTfG1GXYQ
- Github here: https://github.com/astral-sh/uv?tab=readme-ov-file
- Docs here: https://docs.astral.sh/uv/


After setting up gh *project name*, I can head into the project dir and just run uv init

Ran 
 - uv init
 - uv add ruff // This sets up the venv etc
 - uv run ruff check
 - uv run hello.py // Off to the races
 - It looks like, I don't need to run source .venv/bin/activate — just use uv run and I get all the benefits of a virtual environment
