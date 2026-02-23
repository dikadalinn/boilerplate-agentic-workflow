# Boilerplate Agentic Workflow

This repository contains the boilerplate and standard structure for an **Agentic Workflow Documentation Setup**. It is designed to provide a unified, structured approach for agents to read, write, and maintain documentation within a project.

## Roadmap of the Documentation Workflow for Agentic Workflow

Implementing an agentic workflow for documentation involves systematically guiding an AI agent to understand, update, and generate documentation. Below is the roadmap outlining this process:

### Phase 1: Context Gathering & Environment Setup
1. **Directory Structure Analysis**: The agent scans the workspace (e.g., `docs/`, `docs-template/`, `.opencode/`) to understand existing documentation organization.
2. **Knowledge Items (KI) Review**: The agent examines existing Knowledge Items to avoid redundant research and align with established architectural patterns.
3. **Template Standardization**: The agent uses predefined templates from `docs-template/` to ensure all new documentation follows a consistent format.

### Phase 2: Documentation Generation & Updates
1. **Automated Code Analysis**: The agent analyzes source code and architectural decisions to draft accurate technical documentation.
2. **Iterative Refinement**: Using instructions (e.g., Markdown files in `.obsidian` or similar context folders), the agent updates existing files to match current logic.
3. **Change Logging**: Documentation of what changed is automatically recorded to maintain an audit trail.

### Phase 3: Validation & formatting
1. **Linting and Markdown Verification**: The agent ensures generated documents adhere to standard Markdown rules and proper formatting (e.g., GitHub Flavored Markdown).
2. **Link and Reference Checking**: Ensuring all internal file references and inter-document links are valid and appropriately mapped.

### Phase 4: Version Control and Deployment
1. **Git Operations**: The agent can autonomously (or semi-autonomously) add, commit, and push documentation refinements to standard repositories.
2. **Continuous Integration**: (Future) Webhooks and CI pipelines trigger documentation builds and deployments (e.g., static site generation) based on agentic commits.

## Integrated AI Agents

The framework is designed to work collectively with specialized AI roles defined in the `.opencode/agents/` directory, following a strict multi-phase workflow:

- **Business Analyst (`@business-analyst`)**: Facilitates Phase 1 (Business Context), defining the BRD, flow, and NFRs.
- **System Analyst (`@system-analyst`)**: Handles Phase 2 (System Context), translating business logic into architecture, databases, and API specs.
- **Product Manager (`@product-manager`)**: Focuses on Phase 3 (Product Context), developing the PRD, UI states, user stories, and backlogs.
- **Tech Lead (`@tech-lead`)**: Acts as the CTO in Phase 4 (Tech Context). Establishes coding standards, orchestrates executions, and supervises sub-agents.
- **Subagents (`backend-dev`, `frontend-dev`, `qa-engineer`)**: Task-specific developer roles operating under the Tech Lead in Phase 5 to execute backlog tasks with precision.

## Getting Started

1. Clone this repository.
2. Review the `docs-template/` directory for scaffolding new documents.
3. Place initial project definitions in the `docs/` directory.
4. Interact with your AI coding assistant to automatically expand, format, and maintain files according to the roadmap above.
