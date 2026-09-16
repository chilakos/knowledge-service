# knowledge-service

RBC Assist knowledge service. Architecture decision records and diagrams for grounding RBC Assist on on-prem S3-compatible content without manual copies. The design uses Microsoft Fabric OneLake shortcuts (through the on-premises data gateway), the Azure AI Search OneLake files indexer, the Azure Content Understanding skill with selective vision-model routing, and the Luminate Data Gateway (ADR-015).

| Document | Status |
|---|---|
| [ADR-020: On-prem RAG grounding via OneLake shortcuts](docs/adr/ADR-020-onprem-rag-grounding-via-onelake-shortcuts.md) | Proposed (Rev 2), conditional on decision gate G1–G7 |

## Diagrams

- `docs/adr/diagrams/02-target-architecture.png`: target architecture (editable SVG alongside)
- `docs/adr/diagrams/03-query-sequence.png`: query-time sequence
- `docs/adr/diagrams/01-current-state.png`: current manual-copy pipeline

The Mermaid source for each diagram is embedded in the ADR under the image.
