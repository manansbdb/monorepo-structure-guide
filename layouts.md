# Suggested Layouts / Layouts Sugeridos

## English — Apps + packages

```
/
  apps/
    web/
    api/
  packages/
    ui/
    config/
    tsconfig/
  package.json
  pnpm-workspace.yaml
```

## English — Domain-oriented

```
/
  services/
    billing/
    identity/
  libs/
    shared-kernel/
  tooling/
```

## Português — Apps + pacotes

Use `apps/` para deployables e `packages/` para código partilhado versionável.

## Português — Orientado a domínio

Use `services/` por bounded context e `libs/` para kernels partilhados.
