# AI Engineering Standards

This document defines the coding standards and architectural patterns for this
project. All AI-generated code must adhere to these instructions.

## 1. General Formatting

- **Indentation:** Use 2 spaces for all file types.
- **Line Length:** Wrap documentation, comments, and strings at 80 characters.
- **Naming:** Use `Sentence case` for all documentation headings.

## 2. TypeScript Standards

- **Strictness:** Adhere to strict type checking. Avoid `any`.
- **Naming:** Use `camelCase` for variables and `PascalCase` for types.
- **Syntax:** Use ES Modules (ESM) and modern TypeScript features.
- **Exports:** Prefer named exports over default exports.

## 3. Styling (BEM Methodology)

- **Methodology:** Use **BEM** (Block Element Modifier).
- **Format:** `block-name__element-name--modifier-name`.
- **Nesting:** Strictly avoid deep nesting. Only nest pseudo-classes
  (e.g., `&:hover`) or modifiers (e.g., `&--active`).
- **Variables:** Use `hyphen-case` for SCSS variables.

## 4. Documentation & Git

- **Style:** Follow the Google Documentation Style Guide.
- **Commits:** Follow **Conventional Commits** (`feat:`, `fix:`, `chore:`).
- **Links:** Use relative markdown links (e.g., `[Link](FILE.md)`).

## 5. Architectural Intent

- **Modularity:** Design for high cohesion and low coupling.
- **Automation:** Prioritize patterns that work with automated versioning
  and semantic release workflows.
