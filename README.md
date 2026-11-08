<<<<<<< HEAD
# Automotive Aftermarket Analytics Platform

A learning and portfolio project for the fictional AutoParts Intelligence Europe.
All source data will be synthetic.

Planned pipeline: synthetic sources → Python ingestion → Snowflake Bronze →
dbt Silver → Gold sales star schema → governed KPI views.

## Verified setup — 8 November 2026

- Workspace: `/Users/biswarupchakraborty/Desktop/automotive-aftermarket-analytics`.
- Operating system: macOS, Apple Silicon (`Darwin arm64`).
- Git and the VS Code application are installed.
- Project virtual environment: `.venv`, created with Homebrew Python 3.12.
- The default shell Python is 3.15; use the project environment below.
- No project dependencies have been installed yet.
- No Git repository or GitHub remote was present during inspection.
- No project Snowflake configuration, Snowflake/dbt environment variables,
  `~/.dbt/profiles.yml`, or `~/.snowflake/connections.toml` was found.
  No Snowflake connection has been attempted.

## Use the Python environment

From this project directory:

```bash
source .venv/bin/activate
python --version
python -c 'import sys; print(sys.executable)'
```

In VS Code, run **Python: Select Interpreter** and choose
`.venv/bin/python`. The VS Code command-line launcher (`code`) was not found
on PATH; the application can still open this folder.

## Next milestone

Verify current package compatibility, then install Python dependencies into
`.venv`. Initialize Git and connect the intended GitHub repository. Configure
Snowflake later, without committing credentials. No ingestion, source generators,
Snowflake objects, or dbt models have been implemented or tested yet.
=======
# automotive-aftermarket-analytics
>>>>>>> f830f5ca0322e42422b2488b8a6d78e9c48f9ff5
