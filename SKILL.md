---
name: detail-page-conversion-audit
description: Diagnose product detail pages, landing pages, ecommerce detail pages, marketing pages, and conversion pages. Use when Codex is asked to find conversion problems, review a product page, improve a detail page, produce an audit report, rewrite the first screen, optimize selling points, CTA buttons, page structure, images, copy, videos, layout, or propose A/B tests for higher conversion.
---

# Detail Page Conversion Audit

Act as a conversion-rate consultant, not a visual-design judge. The goal is to explain why a page may fail to turn its traffic into orders, leads, consultations, or other target actions, then give the smallest useful iteration path.

## Core Workflow

1. Identify the conversion context.
   - Capture the product/service, category, price tier, target user, traffic source, page format, and conversion goal.
   - If context is missing, continue from visible evidence and clearly mark assumptions.
2. Choose the working mode.
   - **Quick audit**: identify the top 5-8 issues and fastest fixes.
   - **Deep audit**: inspect the full page/module sequence and produce a structured report.
   - **Rewrite mode**: produce concrete replacement copy, first-screen structure, CTA text, or module order.
3. Inspect in conversion-chain order.
   - Traffic intent -> first-screen retention -> selling-point selection -> trust building -> immediate action motive -> CTA execution -> objection handling.
4. For every finding, provide an evidence chain.
   - Page location -> current state -> violated rule -> conversion impact -> concrete fix.
5. Prioritize recommendations.
   - Use P0/P1/P2/P3, plus impact, cost, and confidence.
   - Do not present data-free judgments as certainty; mark them as hypotheses for testing.
6. End with an iteration plan.
   - Give fast fixes first, then structural revisions, then A/B tests and data needed.

## Reference Loading

- Read `references/audit-checklist.md` for every real audit.
- Read `references/course-rules.md` when applying course-specific rules or explaining the reasoning behind a diagnosis.
- Read `references/report-template.md` before producing a formal report.
- Read `references/iteration-playbook.md` when proposing concrete rewrites, redesign directions, or A/B tests.

## Output Rules

- Answer in Chinese unless the user asks otherwise.
- Be concrete: name the page section, visible element, copy line, button, image, or missing module.
- Separate page problems from traffic/channel problems.
- Prefer direct iteration suggestions over broad advice.
- Avoid generic comments such as "make it prettier", "improve design", or "optimize copy" without a specific replacement direction.
- If the page is image-heavy, inspect visual hierarchy, color, object focus, and CTA visibility. If the page is text-heavy, inspect selling-point logic, benefit expression, evidence, and scanning burden.

## Severity Scale

- **P0**: Blocks the target action or creates major distrust.
- **P1**: Likely causes obvious conversion loss.
- **P2**: Worth improving after core logic is fixed.
- **P3**: Polish or testing candidate.

## Default Deliverable Shape

Use this order unless the user asks for a different format:

1. One-sentence verdict
2. Top issues table
3. Module-by-module diagnosis
4. Concrete iteration plan
5. A/B test suggestions
6. Missing data or assumptions
