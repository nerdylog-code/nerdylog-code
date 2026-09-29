# Daniel Vinícius Ferreira Guimarães

**Applied AI & Agent Systems Engineer**

I build practical AI systems and automation with a focus on reproducibility,
controlled tool execution, retrieval quality, and enterprise integration
boundaries.

- Applied AI and agent systems
- RAG and evaluation pipelines
- MCP and controlled tool execution
- Microsoft 365 / Graph integration patterns
- Document and business-process automation
- Python-first engineering

## Featured Engineering Work

### [Agent Engineering Sprint](https://github.com/nerdylog-code/agent-engineering-sprint)
A local-first agent engineering lab covering structured tool execution, hybrid
RAG, adversarial evaluation, MCP, JWT/RBAC tenant controls, observability, and
resilience checks with reproducible evidence.

### [Microsoft 365 Agent Integration](https://github.com/nerdylog-code/microsoft-365-agent-integration)
A sanitized clean-room reference implementation for bounded MCP and Microsoft
Graph integration patterns, using synthetic fixtures and offline permission/error
contracts instead of a live tenant.

### [Meta-Harness](https://github.com/nerdylog-code/meta-harness)
A Hermes Agent/Desktop extension demonstrating multi-agent orchestration,
capability routing, declarative topologies, engine adapters, event storage, and
controlled plugin validation with rollback.

### [Business Process Automation Lab](https://github.com/nerdylog-code/business-process-automation-lab)
A reproducible business-process lab: discovers the AS-IS model from a synthetic event log
(directly-follows graph with conformance checking), derives BPMN 2.0 with diagram interchange,
designs the TO-BE with automation, and measures impact using residuals measured by its own rule
engine instead of estimated factors. Includes an importable n8n flow with retry/DLQ/alerting, a
Power Automate recipe, and a reproducibility gate that compares artifact hashes across two runs.

### [Deploy & Observability Lab](https://github.com/nerdylog-code/deploy-observability-lab)
A small service packaged the way production expects: non-root multi-stage image, liveness/
readiness/startup probes, Prometheus metrics with bounded label cardinality, structured JSON logs
carrying a propagated request_id, Kubernetes manifests with resources and autoscaling, SLI/SLO
targets, and a runbook for deploy, verification and rollback.

### [Applied Business Automation](https://github.com/nerdylog-code/efd-contribuicoes-recibos)
Local-first fiscal/document automation examples for extracting structured fields
from synthetic PDF fixtures and producing review-friendly workbooks. See also
[DAMEF Report](https://github.com/nerdylog-code/damef-report) and the
[Fiscal Document Validation Lab](https://github.com/nerdylog-code/fiscal-document-validation-lab).

## Core Stack

Only technologies represented in the public projects:

- Python
- FastAPI
- Agent systems
- RAG and retrieval evaluation
- MCP
- Microsoft Graph / Microsoft 365 / Entra ID patterns
- OpenTelemetry
- Docker
- Kubernetes manifests, health/readiness probes, Prometheus metrics and SLOs
- Process mining (directly-follows graphs) and BPMN 2.0
- Reproducible pipelines (fixed seeds, artifact hash comparison)
- GitHub Actions
- JavaScript / Node.js
- Excel / OpenPyXL
- pandas
- PDF/document parsing
- SQL / SQLite

## What I build

- AI agents with tool execution and controlled permissions
- Retrieval, reranking, abstention, and evaluation pipelines
- Enterprise integration reference architectures
- Document and business-process automation
- Multi-agent orchestration and plugin systems
- Reproducible engineering experiments with explicit limitations

## Data, reporting and business analysis

Analyst-grade deliverables over synthetic datasets, held to the same rule as the engineering work:
the artifacts are checked, not merely described.

- [World Cup 2026 — Power BI](https://github.com/nerdylog-code/world-cup-2026-powerbi) — dataset, DAX measures, Excel and dashboard
- [Superstore Retail Analytics](https://github.com/nerdylog-code/superstore-retail-analytics) — SQL, SQLite and Excel dashboard
- [Financial Markets Analytics](https://github.com/nerdylog-code/financial-markets-analytics) — SQL, SQLite and reproducible reporting
- [HR Attrition Analytics](https://github.com/nerdylog-code/hr-analytics-attrition) — SQL, SQLite and Excel dashboard
- [Portfolio index](https://github.com/nerdylog-code/portfolio-dados) — entry point across the data projects

## How I work

- **Every public repository carries a runnable check**: a test suite where there is logic, an
  artifact check against a versioned baseline where there is data. Green CI on push, not a badge claim.
- **Reproducibility is enforced**: deterministic seeds and hash comparison between runs, so results
  can be re-derived instead of trusted.
- **Limitations are written down**: each project states what it is not — synthetic data, no production
  claims, and what would need a real environment (tenant, cluster, client data).

## Links

- [GitHub](https://github.com/nerdylog-code)
- Location: Brazil
