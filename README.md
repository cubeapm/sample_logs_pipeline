# Sample Logs Pipeline

This is a sample project to demonstrate how to ingest logs into CubeAPM. It uses Fluent Bit to collect logs from various sources and feed them into CubeAPM. This repository has a docker compose file to set up all these services conveniently.

## Setup

Clone this repository and go to the project directory. Then run the following commands

```
docker compose up --build
```

CubeAPM will now be available at `http://localhost:3125`.

## Contributing

Please feel free to raise PR for any enhancements - additional integrations, version updates, documentation updates, etc.
