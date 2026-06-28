# Intelligent-Agent

# An Intelligent Agent for Failure Analysis Using Human-in-the-Loop Learning

A multi-agent cognitive framework designed for automated failure diagnosis and controlled remediation within complex DevOps environments. This system combines Agentic Retrieval-Augmented Generation (RAG), local Large Language Models (LLMs), autonomous reasoning agents, and Human-in-the-Loop (HITL) governance to create a self-improving AIOps platform.

## 🚀 Key Objectives
* **Reduce MTTR:** Accelerate Mean Time to Resolution via automated root cause paths.
* **Dual-Engine RCA:** Cross-verify diagnostic hypotheses using independent evaluation engines.
* **Policy-Driven Safety:** Enforce granular execution restrictions before automated remediation.
* **Continuous Learning:** Capture human feedback and resolution actions to enrich future memory.

## 🏗️ System Architecture & Core Modules
The cognitive framework is divided into 12 interconnected operational modules:
1. **DevOps & Failure Simulation:** Simulates environment anomalies (service crashes, pipeline failures).
2. **Observability Data Collection:** Centralises logs, telemetry data, and system events.
3. **Knowledge Repository & RAG:** Vectorises past incidents, runbooks, and SOP documents using Onyx.
4. **Intelligent Agent Orchestration:** Directs message routing and handles agent collaboration.
5. **RCA Agent Module:** Generates an initial text-based evidence hypothesis using local LLMs.
6. **Infrastructure Validation:** Query active APIs to check live container states and health.
7. **HolmesGPT Analysis:** Independently processes metrics for a secondary diagnostic perspective.
8. **Root Cause Fusion Layer:** Merges multi-agent evidence into a single confidence-scored report.
9. **Human-in-the-Loop Governance:** Provides a UI layer for human engineering oversight and review.
10. **Automated Workflow Execution:** Dispatches recovery tasks directly to underlying toolsets.
11. **Policy & Compliance Control:** Classifies tasks as Allowed, Requires Approval, or Blocked.
12. **Continuous Learning:** Ingests finalized resolutions back into semantic storage.

## 🛠️ Technical Specifications & Tool Stack
* **Orchestration & Workflow:** n8n Workflow Engine, Python
* **Infrastructure & Automation:** Jenkins, Docker, k3s (Kubernetes), Chef
* **Telemetry & Observability:** OpenTelemetry (OTEL), Grafana
* **Knowledge Infrastructure:** Onyx RAG Platform, Ollama (Local LLM Inference)
* **Parallel Diagnostic Engine:** HolmesGPT
* **Knowledge Bases:** Jira API, Confluence, Markdown Runbooks, SOPs

## 📈 Project Roadmap
* **Phase 1: Outline & Design** (Completed) - Architecture definition and literature review.
* **Phase 2: Development** (In Progress) - Code implementation and agent orchestration loops.
* **Phase 3: Testing** (Pending) - Failure simulation, evaluation metrics, and MTTR testing.
* **Phase 4: Final Submission** (Pending) - Comprehensive validation evaluation.
