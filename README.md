# P-Stream Docs

Documentation site for P-Stream, built with [Astro](https://astro.build) and [Starlight](https://starlight.astro.build).

## Development

```bash
pnpm install
pnpm dev
```

## Build

```bash
pnpm build
```

## Docker

Build and run with Docker:

```bash
docker build -t smov-docs .
docker run -p 8080:8080 smov-docs
```

Or use Docker Compose:

```bash
docker compose up
```

The container image is also available at [ghcr.io/okikio/smov-docs](https://ghcr.io/okikio/smov-docs).

## Environment Variables

| Variable | Default | Description |
|----------|---------|-------------|
| `SITE_URL` | `https://okikio.github.io` | The base site URL for the build |
| `BASE_PATH` | `/smov-docs` | The base path for the site |
| `PORT` | `8080` | Port for the Docker container |
