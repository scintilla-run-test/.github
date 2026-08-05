# scintilla-run-test

Independent acceptance organization for **scintilla-run**.

Runner, revision/alias, durable invocation/workflow, KV/secrets, clients, UI, MCP, and PostgreSQL certification.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `gleam-runner-conformance` | protocol conformance | `ready` | `matrix` |
| `revision-alias-weighting` | protocol conformance | `ready` | `matrix` |
| `sync-async-cancel` | API contract | `ready` | `matrix` |
| `workflow-durable-runs` | scheduler/failover | `ready` | `matrix` |
| `kv-secrets-security` | security | `ready` | `matrix` |
| `clients-contract` | SDK consumer | `ready` | `matrix` |
| `operator-ui-e2e` | browser E2E | `ready` | `matrix` |
| `mcp-contract` | MCP contract | `ready` | `matrix` |
| `postgres-chaos-persistence` | chaos/fault injection | `ready` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.
