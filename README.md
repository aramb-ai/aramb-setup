# setup-aramb

GitHub Action to set up aramb CLI and BuildKit.

## Usage

```yaml
- uses: aramb-ai/aramb-setup@v1
- run: aramb build
```

## Inputs

| Input | Description | Default |
|-------|-------------|---------|
| `version` | Aramb CLI version | `latest` |
| `buildkit-version` | BuildKit version | `latest` |
| `skip-buildkit` | Skip BuildKit setup | `false` |
