# Cloud-Native Learning

Long-form, first-principles deep dives into cloud-native engineering — written for
practitioners who already run the infrastructure and want the mental model, not the marketing.

Each topic lives in its own folder under [`docs/`](docs/), with the write-up as a
`README.md` you can read directly on GitHub, the diagrams as PNGs plus their SVG
sources, and a print-ready PDF.

---

## Topics

| # | Topic | What it covers | Status |
| --- | --- | --- | --- |
| 01 | [**Agentic AI in the cloud-native ecosystem**](docs/01-agentic-ai-cloud-native/) | MCP · Kubernetes MCP servers · AI agents · SRE agents (kagent, HolmesGPT, K8sGPT) · Agent Skills · RAG · runbooks · agent security (OWASP ASI) · observability (OTel GenAI) · AI gateways · authenticating MCP from Cursor · Kubernetes as an AI platform | ✅ Sept 2026 |

> Future topics will follow the same `docs/NN-topic-name/` pattern — Kubernetes internals,
> platform engineering, observability, and whatever else is worth writing down properly.

---

## How these are written

A few conventions that apply across every topic here:

- **First principles before tooling.** Each guide starts from the smallest true statement
  about the system and builds up, so the tool names land on a structure that already makes sense.
- **Mapped onto what you already run.** New concepts are explained against Kubernetes, Envoy,
  GitOps, Prometheus and RBAC rather than in the abstract.
- **Diagrams are authored, not decorative.** Every figure is a hand-built SVG showing a real
  mechanism. The sources are in each topic's `assets/svg/` so they can be edited rather than redrawn.
- **Claims are linked.** Where a guide cites a number or a version, the source is linked inline
  and repeated in a Sources section.
- **Dated, not evergreen.** This ecosystem moves fast. Every guide states when it was compiled
  and flags what is likely to change.

---

## Repository layout

```
cloud-native-learning/
├── README.md                              ← you are here
└── docs/
    └── 01-agentic-ai-cloud-native/
        ├── README.md                      ← the guide (renders on GitHub)
        ├── cloud-native-ai-field-guide.pdf ← print-ready, 39 pages
        ├── cloud-native-ai-field-guide.docx
        └── assets/
            ├── d01_stack.png              ← diagrams as used in the guide
            ├── ...
            └── svg/                       ← editable SVG sources
```

---

## License

Text and diagrams: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — use them,
adapt them, just keep the attribution.

Maintained by [Kashish Lakhara](https://techwithkashish.com) ·
[@kashishtwts](https://x.com/kashishtwts)
