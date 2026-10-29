# DockShift Feedback & Issue Tracker

Official Community Issue Tracker, Bug Reports & Feature Requests for [DockShift](https://dockshift.org/).

[Live Website](https://dockshift.org/) • [Run → Compose](https://dockshift.org/run-to-compose/) • [Compose → Run](https://dockshift.org/compose-to-run/) • [Compose → K8s](https://dockshift.org/compose-to-k8s/) • [Report Issue](https://github.com/aquarkgn/dockshift-feedback/issues)

---

## About DockShift

[DockShift](https://dockshift.org/) is a fast, 100% in-browser Docker Run ⇄ Docker Compose bidirectional converter with structured JSON AST export and AI Prompt Skill integrations.

- **Zero-Backend**: All parsing and AST transformations happen entirely in your browser using native JavaScript. Zero cold-start latency, zero telemetry of your container commands, and complete data privacy.
- **Bi-directional Conversion**: Convert `docker run` commands to `docker-compose.yml`, or decompile Compose YAML back into executable `docker run` CLI commands.
- **Structured JSON AST**: Export intermediate Abstract Syntax Trees for AI agents, CI/CD scripts, or automated tooling.
- **Prompt Skill**: Instant 1-click execution for top IDEs (Cursor, VS Code, Windsurf, Trae, Zed).

---

## Submitting Feedback & Bug Reports

This repository is dedicated to tracking bugs, edge-case parsing syntax, feature requests, and CLI improvements for DockShift.

### Found a Conversion Bug or Unsupported Flag?
Docker CLI supports hundreds of flags and syntax variations. If DockShift fails to parse a specific command or outputs incorrect Compose YAML:
1. Check existing [Issues](https://github.com/aquarkgn/dockshift-feedback/issues) to avoid duplicates.
2. [Open a new Bug Report](https://github.com/aquarkgn/dockshift-feedback/issues/new?template=bug_report.yml).
3. Provide:
   - Your input command or YAML
   - Expected output
   - Actual output

### Request a Feature or New Syntax
Want support for Docker Swarm, Podman, Kubernetes CRDs, or specific container runtimes?
- [Submit a Feature Request](https://github.com/aquarkgn/dockshift-feedback/issues/new?template=feature_request.yml).

---

## Security & Privacy Note

DockShift executes 100% client-side. When submitting an issue, please **sanitize any sensitive information** (such as private tokens, database passwords, or private domain names) from your Docker commands before posting publicly.

---

## Links

- **Live Site**: https://dockshift.org/
- **Documentation & Legal**: https://dockshift.org/
