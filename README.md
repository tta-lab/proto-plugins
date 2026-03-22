# proto-plugins

Community [proto](https://moonrepo.dev/proto) plugins for tools not included in moonrepo's built-in registry.

## Available Plugins

| Plugin | Tool | Source |
|--------|------|--------|
| [dagger.toml](./dagger.toml) | [Dagger](https://dagger.io) CI/CD engine | GitHub Releases |
| [golangci-lint.toml](./golangci-lint.toml) | [golangci-lint](https://golangci-lint.run) Go linter | GitHub Releases |
| [jb.toml](./jb.toml) | [jsonnet-bundler](https://github.com/jsonnet-bundler/jsonnet-bundler) Jsonnet package manager | GitHub Releases |
| [kubectl.toml](./kubectl.toml) | [kubectl](https://kubernetes.io/docs/reference/kubectl/) Kubernetes CLI | dl.k8s.io |
| [tanka.toml](./tanka.toml) | [Tanka](https://tanka.dev) Jsonnet-based Kubernetes config tool (`tk`) | GitHub Releases |

## Usage

Add a plugin to your `.prototools`:

```toml
dagger = "0.19.11"

[plugins]
dagger = "https://raw.githubusercontent.com/tta-lab/proto-plugins/main/dagger.toml"
```

Then install with:

```bash
proto install dagger
```
