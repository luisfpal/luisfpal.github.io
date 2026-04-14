# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

A personal GitHub Pages site for Luis Palacios, built with Jekyll. Hosted at https://luisfpal.github.io.

## Architecture

- **No build step locally required** — GitHub Pages runs Jekyll automatically on push.
- `_layouts/default.html` — single shared layout for all pages. Nav, header, and footer live here.
- `assets/css/style.css` — all styles. Ultra-minimal, no frameworks, no JS.
- Content pages are Markdown files with `layout: default` front matter.

## Adding content

**New note:** create `notes/some-topic.md`, add a link in `notes/index.md`.
**New project:** add a line in `projects/index.md`.
**New section:** create a folder with an `index.md`, add a nav link in `_layouts/default.html`.

## Design constraints

- No JavaScript frameworks
- No colors beyond grays
- Max-width 680px, system font stack
- Keep pages sparse — empty sections are fine

---

## Core Operating Principles

### Focus (Jobs)
Say NO to unnecessary complexity. Question whether something needs to exist before adding it.

### The Algorithm (Musk) — order is mandatory
1. Question requirements — make them less dumb
2. Delete — remove anything unnecessary first
3. Simplify/optimize — only after deleting
4. Automate — last step only

### Mechanisms over intentions (Bezos)
Good intentions fail; mechanisms succeed. Work backwards from the desired result.

### Antifragility (Taleb)
Improve by removing rather than adding. Verify everything — do not assume, check.

### Inversion (Munger)
Ask "how could this fail?" before building. Focus on avoiding stupidity.

---

## Response Protocol

**Before making changes:**
1. Read the file(s) first — never modify without reading.
2. Question requirements — is this change actually needed?
3. Propose approach and wait for approval on non-trivial changes.

**When making changes:**
1. Follow existing patterns and style.
2. Delete unnecessary code — don't leave dead markup or unused CSS.

**After making changes:**
1. Verify it actually works.
2. Ask: "how could this break?"
3. Remove anything added for debugging.

---

## Development Philosophy

- **Simplicity**: Less is more. Less code = less debt.
- **Readability**: Prioritize clarity over cleverness.
- **Via Negativa**: Improve by removing rather than adding.
- **DRY**: Don't repeat structure or styles — centralize in `default.html` and `style.css`.

---

## Git Commits

1. Check status before committing — review all changes first.
2. Commit message focuses on **why**, not what.
3. Use trailers when relevant:
   - Bug fix reported by someone: `--trailer "Reported-by:<name>"`
   - Linked to a GitHub issue: `--trailer "Github-Issue:#<number>"`
4. **Never** mention co-authored-by or AI tools in commits.
