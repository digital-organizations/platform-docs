# Platform Engineering Documentation

# Platform Engineering Documentation

This repository contains all internal documentation for the Platform Engineering team.

📌 **Source of Truth:** GitHub  
📌 **Rendered UI:** Wiki.js (Git Sync enabled)

## Structure Overview
- `00-overview`: High-level introduction, architecture, glossary
- `01-onboarding`: New engineer onboarding guides
- `02-standards`: Engineering & security standards
- `03-architecture`: Detailed system and infra architecture
- `04-services`: Internal service documentation
- `05-how-to-guides`: Task-focused guides
- `06-runbooks`: On-call and operational runbooks
- `07-troubleshooting`: Known issues and debugging patterns
- `08-security`: Security guidelines & processes
- `09-adrs`: Architecture Decision Records
- `10-operations`: RCAs, maintenance, backup, checklists

---

## Using with Wiki.js
1. Go to: `Administration → Storage → Git`
2. Set repository URL of this repo
3. Choose branch: `main`
4. Set sync mode: **Bidirectional**
5. Set folder path: `docs/`

---

## Contributing
1. Create a branch  
2. Make updates  
3. Submit PR for review

---




platform-docs/
│
├── README.md
├── docs/
│   ├── 00-overview/
│   │   ├── platform-introduction.md
│   │   ├── architecture-overview.md
│   │   ├── glossary.md
│   │   └── faq.md
│   │
│   ├── 01-onboarding/
│   │   ├── new-engineer-guide.md
│   │   ├── access-setup.md
│   │   ├── tools-required.md
│   │   └── team-processes.md
│   │
│   ├── 02-standards/
│   │   ├── coding-guidelines.md
│   │   ├── branching-strategy.md
│   │   ├── naming-conventions.md
│   │   ├── security-standards.md
│   │   └── compliance-basics.md
│   │
│   ├── 03-architecture/
│   │   ├── high-level-architecture.md
│   │   ├── network-architecture.md
│   │   ├── infra-components.md
│   │   ├── kubernetes-architecture.md
│   │   ├── ci-cd-architecture.md
│   │   └── monitoring-observability.md
│   │
│   ├── 04-services/
│   │   ├── service-catalog.md
│   │   ├── api-gateway.md
│   │   ├── authentication.md
│   │   ├── storage-and-databases.md
│   │   └── messaging-and-events.md
│   │
│   ├── 05-how-to-guides/
│   │   ├── setup-local-dev.md
│   │   ├── deploy-a-service.md
│   │   ├── create-terraform-module.md
│   │   ├── add-new-k8s-namespace.md
│   │   ├── configure-ci-pipeline.md
│   │   └── rotate-secrets.md
│   │
│   ├── 06-runbooks/
│   │   ├── template-runbook.md
│   │   ├── api-server-down.md
│   │   ├── high-cpu-on-node.md
│   │   ├── service-deployment-failed.md
│   │   ├── cluster-storage-full.md
│   │   └── restart-ingress-controller.md
│   │
│   ├── 07-troubleshooting/
│   │   ├── k8s-troubleshooting.md
│   │   ├── ci-cd-issues.md
│   │   ├── terraform-errors.md
│   │   ├── dns-issues.md
│   │   └── networking.md
│   │
│   ├── 08-security/
│   │   ├── secrets-management.md
│   │   ├── vulnerabilities-handling.md
│   │   ├── compliance.md
│   │   └── access-roles-and-permissions.md
│   │
│   ├── 09-adrs/
│   │   ├── ADR-001-container-orchestration-choice.md
│   │   ├── ADR-002-ci-cd-tool.md
│   │   ├── ADR-003-monitoring-stack.md
│   │   ├── ADR-004-logging-architecture.md
│   │   └── template.md
│   │
│   └── 10-operations/
│       ├── incident-management.md
│       ├── rca-template.md
│       ├── backup-recovery.md
│       ├── maintenance-policy.md
│       └── operational-checklists.md
