## Avik Mukherjee

I build infrastructure that has to hold up under load: Postgres proxies, schedulers, queues, and the systems that keep AI agents governed. Mostly Go and TypeScript, usually with Postgres underneath.

Backend engineer at **[SuperAlign](https://superalign.ai)**, working on enterprise discovery and governance for shadow AI: cross-platform scanner daemons, a realtime control plane for fleets of endpoints, and an extension SDK that ships telemetry into customer-owned Splunk and S3.

### Things I've built

| | |
| --- | --- |
| **[QueryGuard](https://github.com/Avik-creator/queryguard)** | A Postgres wire-protocol proxy that prices each query before it runs and gives every tenant a cost budget. With a rogue tenant running full scans, innocent p99 stays at 1.1–3.5 ms instead of 5–8 ms. v1.0, tested on PG 16–18. |
| **[Governor](https://github.com/Avik-creator/governor)** | A resource governor for fan-out workloads like agents spawning sub-agents: hierarchical quotas, crash-safe leases and tenant fairness over gRPC. Cuts a starved tenant's p95 wait from 553 ms to 27 ms. |
| **[Mindstate](https://github.com/Avik-creator/Mindstate)** | Durable memory for AI agents over MCP — session handoffs, task-scoped recall, and memories that can be superseded rather than silently going stale. |
| **[miniqueue](https://github.com/Avik-creator/miniqueue)** | A Postgres-backed job queue in Go. Lease semantics, at-least-once delivery, crash recovery — every tradeoff documented, tested against real Postgres. |
| **[kube-lite](https://github.com/Avik-creator/kubelite)** | Kubernetes' core ideas rebuilt from the ground up in Go: reconciler loop, scheduler, rollout controller, health probes, dead-node detection. |
| **[pgxray](https://pganalyzer.avikmukherjee.com)** | Paste SQL, get an `EXPLAIN ANALYZE` plan tree and index suggestions grounded in your real schema. Read-only by construction. |
| **[bridgecord](https://bridgecord.avikmukherjee.com)** | Website chat that lives in Discord or Slack — one thread per visitor, with optional AI answers from your own site content. |
| **[markdown-to-video](https://github.com/Avik-creator/markdown_video)** | Write a video in Markdown. Renders and exports to MP4 entirely in the browser. |

### How I learn things

By taking them apart. A [Redis server](https://github.com/Avik-creator/redis_implementation), a [load balancer](https://github.com/Avik-creator/load-balancer-from-scratch), [Reed–Solomon erasure coding](https://github.com/Avik-creator/erasure-coding), a [MITM proxy](https://github.com/Avik-creator/mitm-proxy), [React Query](https://github.com/Avik-creator/react-query-from-scratch) — rebuilt from scratch so I can explain why each piece exists, not just that it does.

---

**[avikmukherjee.com](https://avikmukherjee.com)** · **[LinkedIn](https://www.linkedin.com/in/avik-mukherjee-8ab9911bb/)** · **[@avikm744](https://x.com/avikm744)**
