---
name: hermes-skill-understand-onboard
description: Generate an evidence-backed onboarding guide from a repository and its operational surfaces. Use when a user asks for this workflow or a closely related task.
---

# Understand Onboard

Generate an evidence-backed onboarding guide for a codebase. Optimize for a new contributor completing a first safe task without guessing.

## Workflow

1. Inspect README files, package manifests, entry points, tests, scripts, configuration, and deployment notes.
2. Explain the architecture in dependency order: user entry, core flow, persistence, integrations, and operations.
3. Provide setup commands only when verified from repository evidence.
4. Identify safe first tasks, required checks, and protected areas.
5. Include a troubleshooting section based on observed failure paths.
6. Mark undocumented or unverified steps explicitly.

Never include credentials, private endpoints, or instructions that bypass project safety controls.

<!-- JIT-HARNESS:START -->
## Harness contract

For runtime adaptation or benchmarking, read [docs/JIT-HARNESS.md](docs/JIT-HARNESS.md) and validate [harness/manifest.json](harness/manifest.json). Treat the manifest as a planning and verification contract, not as authority to invoke tools. Preserve the skill's existing approval boundaries, stop on permission ambiguity, and do not claim successful execution without re-reading the resulting artifact or state.
<!-- JIT-HARNESS:END -->
