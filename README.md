# Power Electronics Simulator

## Setup

> **Note:** If you haven't installed `uv` yet, please follow the [installation guide](https://docs.astral.sh/uv/getting-started/installation/#__tabbed_1_1) first.

```bash
# Install Python
uv python install 3.8

# Run migrations
uv run python manage.py makemigrations simulations
uv run python manage.py migrate

# Start server
uv run python manage.py runserver
```

## Circuit Files Directory
### Unix (Linux, Macos)
run the commmand down below then copy to the output
```
echo ${PWD}/circuit_files
```

### Windows
#### Powershell
```
$PWD.Path
```