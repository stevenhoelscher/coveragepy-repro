setup env:
```
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
source .envrc
``

reproduce:
```
pytest
```

error:
```
   raise ConfigError(f"Couldn't read config file {filename}: {err}") from err
coverage.exceptions.ConfigError: Couldn't read config file pyproject.toml: Expected newline or end of document after a statement (at line 3, column 14)
```
