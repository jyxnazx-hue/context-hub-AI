<!-- BEGIN:nextjs-agent-rules -->
# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` before writing any code. Heed deprecation notices.
<!-- END:nextjs-agent-rules -->
## Agentic Library Governance Rules
* All design changes must be reflected in `agentic-library/active_manifest.json` before code implementation.
* For every generation, provide a "Trust Trace" rationale explaining the choice of clusters used.
* Prioritize assets marked as "Primary" in the manifest when refactoring components.
* Maintain a "Human-in-the-Loop" workflow by pausing for approval after clustering but before final code sync[cite: 1, 2].

