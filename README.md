# Flask starter

A minimal Flask app in Python, managed with uv, with one route, no database.

- `app.py`: the app and its `/` route
- `pyproject.toml`: the project and its dependencies

## Run

```sh
uv sync
uv run flask --app app run --debug
```

Then open http://localhost:5000.
