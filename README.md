# Codefast Day 14 · Aceternity Theme Lab

## Mission
- Rebuild `ui.aceternity.com` theme controls with live previews, design token mapping, and publish flow.
- Allow designers to tweak tokens, export configurations, and view contrast checks.

## Implementation Checklist
1. Sync Figma tokens and map them to Radix primitives powering Aceternity components.
2. Build live preview playground using shad UI, supporting light/dark/hi-contrast modes.
3. Persist custom themes in IndexedDB; offer export to JSON and shareable URLs.
4. Run automated contrast and accessibility audits per token change.

## Telemetry & QA
- Track theme edits, exports, and accessibility warnings in Datadog dashboards.
- Write unit tests for token mappers and integration tests for preview rendering.

## Deliverables
- README outlining token pipelines, preview architecture, and publishing workflow.
- Designer onboarding guide with step-by-step walkthrough.
