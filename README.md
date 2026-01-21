# Drawio

A self-hosted drawio application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/drawio/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/drawio" ~/.local/srv/docker/drawio
cd ~/.local/srv/docker/drawio
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install drawio
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
