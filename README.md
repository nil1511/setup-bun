# setup-bun
> Huge inspiration [setup-deno](https://github.com/denoland/setup-deno)

Set up your GitHub Actions workflow with a specific version of Bun.

## Usage

### Latest stable

```yaml
- uses: xhyrom/setup-bun@v0.1.0
  with:
    bun-version: latest
```

### Specific version

```yaml
- uses: xhyrom/setup-bun@v0.1.0
  with:
    bun-version: "0.1.2"
```