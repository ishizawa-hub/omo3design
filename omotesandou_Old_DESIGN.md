# 羽毛布団の通販

## Mission
Create implementation-ready, token-driven UI guidance for 羽毛布団の通販 that is optimized for consistency, accessibility, and fast delivery across content site.

## Brand
- Product/brand: 羽毛布団の通販
- URL: https://omotesando-futonten.com/?srsltid=AfmBOoo3Andli_eAmvocN7j5CKJndB-Dia2HrK5D3resD4FAUBDAjxc_
- Audience: readers and knowledge seekers
- Product surface: content site

## Style Foundations
- Visual style: minimal, utility-first, accessibility-prioritized
- Main font style: `font.family.primary=sans-serif`, `font.family.stack=sans-serif`, `font.size.base=20.33px`, `font.weight.base=400`, `font.lineHeight.base=28.8px`
- Typography scale: `font.size.xs=12.8px`, `font.size.sm=15px`, `font.size.md=16px`, `font.size.lg=20.33px`, `font.size.xl=22.4px`, `font.size.2xl=38.4px`, `font.size.3xl=41.6px`
- Color palette: `color.text.primary=#000000`, `color.surface.muted=#f7f7f7`, `color.surface.raised=#ffffff`, `color.border.muted=#999999`
- Spacing scale: `space.1=5px`, `space.2=10.16px`, `space.3=11.2px`, `space.4=20px`, `space.5=36px`, `space.6=45px`, `space.7=48px`, `space.8=60.99px`
- Radius/shadow/motion tokens: `motion.duration.instant=500ms`, `motion.duration.fast=1000ms`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
Concise, confident, implementation-focused.

## Rules: Do
- Use semantic tokens, not raw hex values, in component guidance.
- Every component must define states for default, hover, focus-visible, active, disabled, loading, and error.
- Component behavior should specify responsive and edge-case handling.
- Interactive components must document keyboard, pointer, and touch behavior.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.
- Do not ship component guidance without explicit state rules.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and semantic tokens.
3. Define component anatomy, variants, interactions, and state behavior.
4. Add accessibility acceptance criteria with pass/fail checks.
5. Add anti-patterns, migration notes, and edge-case handling.
6. End with a QA checklist.

## Required Output Structure
- Context and goals.
- Design tokens and foundations.
- Component-level rules (anatomy, variants, states, responsive behavior).
- Accessibility requirements and testable acceptance criteria.
- Content and tone standards with examples.
- Anti-patterns and prohibited implementations.
- QA checklist.

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.
- Include known page component density: links (63), lists (2), inputs (1), navigation (1).

- Extraction diagnostics: Audience and product surface inference confidence is low; verify generated brand context.

## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Teams should prefer system consistency over local visual exceptions.
