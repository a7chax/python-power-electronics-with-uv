# Power Electronics Simulator

This repository demonstrates how to install and run [Python Power Electronics](https://www.pythonpowerelectronics.com/downloads.html) using the `uv` project manager.

**Version:** 4.4.0 (Released: February 19, 2023)

## Setup

> **Note:** If you haven't installed `uv` yet, please follow the [installation guide](https://docs.astral.sh/uv/getting-started/installation/#__tabbed_1_1) first.

```bash
# Install Python
uv python install 3.8

# Run migrations
uv run python simulator_interface/manage.py makemigrations simulations
uv run python simulator_interface/manage.py migrate

# Start server
uv run python simulator_interface/manage.py runserver
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