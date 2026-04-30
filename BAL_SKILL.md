---
name: design-system-balmuda
description: Creates implementation-ready design-system guidance with tokens, component behavior, and accessibility standards. Use when creating or updating UI rules, component specifications, or design-system documentation.
---

<!-- TYPEUI_SH_MANAGED_START -->

# BALMUDA（バルミューダ）公式サイト

## Mission
Deliver implementation-ready design-system guidance for BALMUDA（バルミューダ）公式サイト that can be applied consistently across e-commerce storefront interfaces.

## Brand
- Product/brand: BALMUDA（バルミューダ）公式サイト
- URL: https://www.balmuda.com/jp/
- Audience: online shoppers and consumers
- Product surface: e-commerce storefront

## Style Foundations
- Visual style: structured, accessible, implementation-first
- Main font style: `font.family.primary=Open Sans`, `font.family.stack=Open Sans, YuGothic_Family, YuGothic, Hiragino Kaku Gothic ProN, Meiryo, sans-serif`, `font.size.base=12px`, `font.weight.base=400`, `font.lineHeight.base=20.4px`
- Typography scale: `font.size.xs=10px`, `font.size.sm=11px`, `font.size.md=12px`, `font.size.lg=12.8px`, `font.size.xl=14px`, `font.size.2xl=14.4px`, `font.size.3xl=15.12px`, `font.size.4xl=16.8px`
- Color palette: `color.text.primary=#333333`, `color.border.muted=#999999`, `color.text.tertiary=#222222`, `color.text.inverse=#cccccc`, `color.surface.base=#000000`, `color.surface.muted=#ffffff`
- Spacing scale: `space.1=1px`, `space.2=6px`, `space.3=9px`, `space.4=10px`, `space.5=12px`, `space.6=14px`, `space.7=14.4px`, `space.8=16px`
- Radius/shadow/motion tokens: `radius.xs=60px`, `radius.sm=100px` | `motion.duration.instant=200ms`, `motion.duration.fast=300ms`, `motion.duration.normal=1000ms`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
concise, confident, implementation-focused

## Rules: Do
- Use semantic tokens, not raw hex values in component guidance.
- Every component must define required states: default, hover, focus-visible, active, disabled, loading, error.
- Responsive behavior and edge-case handling should be specified for every component family.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and tokens.
3. Define component anatomy, variants, and interactions.
4. Add accessibility acceptance criteria.
5. Add anti-patterns and migration notes.
6. End with QA checklist.

## Required Output Structure
- Context and goals
- Design tokens and foundations
- Component-level rules (anatomy, variants, states, responsive behavior)
- Accessibility requirements and testable acceptance criteria
- Content and tone standards with examples
- Anti-patterns and prohibited implementations
- QA checklist

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.

## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Prefer system consistency over local visual exceptions.

<!-- TYPEUI_SH_MANAGED_END -->
