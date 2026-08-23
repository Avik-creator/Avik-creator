## Avik Mukherjee

I build infrastructure for AI agents — the systems that discover them, watch what they do, verify their output, and keep them governed. Mostly Go and TypeScript, usually with Postgres underneath.

Backend engineer at **[SuperAlign](https://superalign.ai)**, working on enterprise discovery and governance for shadow AI: cross-platform scanner daemons, a realtime control plane for fleets of endpoints, and an extension SDK that ships telemetry into customer-owned Splunk and S3.

### Things I've built

| | |
| --- | --- |
| **[Mindstate](https://github.com/Avik-creator/Mindstate)** | Durable memory for AI agents over MCP — session handoffs, task-scoped recall, and memories that can be superseded rather than silently going stale. |
| **[miniqueue](https://github.com/Avik-creator/miniqueue)** | A Postgres-backed job queue in Go. Lease semantics, at-least-once delivery, crash recovery — every tradeoff documented, tested against real Postgres. |
| **[kube-lite](https://github.com/Avik-creator/kubelite)** | Kubernetes' core ideas rebuilt from the ground up in Go: reconciler loop, scheduler, rollout controller, health probes, dead-node detection. |
| **[pgxray](https://pganalyzer.avikmukherjee.com)** | Paste SQL, get an `EXPLAIN ANALYZE` plan tree and index suggestions grounded in your real schema. Read-only by construction. |
| **[bridgecord](https://bridgecord.avikmukherjee.com)** | Website chat that lives in Discord or Slack — one thread per visitor, with optional AI answers from your own site content. |
| **[markdown-to-video](https://github.com/Avik-creator/markdown_video)** | Write a video in Markdown. Renders and exports to MP4 entirely in the browser. |

### How I learn things

By taking them apart. A [Redis server](https://github.com/Avik-creator/redis_implementation), a [load balancer](https://github.com/Avik-creator/load-balancer-from-scratch), [Reed–Solomon erasure coding](https://github.com/Avik-creator/erasure-coding), a [MITM proxy](https://github.com/Avik-creator/mitm-proxy), [React Query](https://github.com/Avik-creator/react-query-from-scratch) — rebuilt from scratch so I can explain why each piece exists, not just that it does.

---

**[avikmukherjee.com](https://avikmukherjee.com)** · **[@avikm744](https://x.com/avikm744)**
