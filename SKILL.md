---
name: port-scanner-but-for-localhost-shows
description: port scanner but for localhost - shows me what ports are in use and what process is using them. i always fo...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: port scanner but for localhost - shows me what ports are in use and what process is using them. i always forget if its lsof or netstat or ss and the flags are different on mac vs linux

# Context
just make it work on both mac and linux plz

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: test-driven-builder description: A builder that generates Agent Skills by writing tests first, then building the implementation to satisfy them. version: 0.1.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.