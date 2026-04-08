# Hermes Golden

Hermes runtime wrapper for managed Railway deployments.

This repo packages a public admin surface plus Hermes-compatible runtime endpoints used by the Hermes AI control plane.

## Included

- Hermes admin/config UI
- public health endpoints
- Hermes workspace compatibility endpoints
- runtime command/file/config helpers
- container entrypoint for Railway

## Environment

Important variables:

- `ADMIN_USERNAME`
- `ADMIN_PASSWORD`
- `HERMES_HOME`
- `HERMES_DATA_ROOT`
- `HERMES_WORKSPACE_DIR`
- `HERMES_STATE_DIR`
- `API_SERVER_ENABLED`
- `API_SERVER_KEY`
- `API_SERVER_HOST`
- `API_SERVER_PORT`

## Deploy

Build and deploy on Railway using the included `Dockerfile`.
