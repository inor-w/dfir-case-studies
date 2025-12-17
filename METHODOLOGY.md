# Methodology (how the examiner approaches a case)

These reports follow a consistent, defensible workflow.

## 1) Define scope and questions
- Translate “client questions” into testable claims
- Identify the artifacts needed to confirm/deny each claim

## 2) Preserve integrity
- Verify provided hashes or compute cryptographic hashes on intake
- Work from copies; mount images read-only where applicable
- Record tool versions and environment assumptions

## 3) Acquire or triage evidence (when applicable)
- Collect high-value artifacts first (triage mindset)
- Validate collection results (expected targets, counts, paths)

## 4) Analyze using multiple sources of truth
- Corroborate (registry + execution traces + logs, etc.)
- Separate observation (“what is”) from inference (“what it implies”)
- Treat timestamps carefully (UTC vs local; timestamp semantics differ by artifact)

## 5) Document and communicate
- Capture supporting evidence (screenshots, output excerpts)
- Write concise key findings tied to artifacts
- Keep conclusions within the evidence (no conjecture)
