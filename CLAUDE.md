# Guidelines for "Fundamentals of Software Architecture" Notes

**Book:** Fundamentals of Software Architecture — Mark Richards & Neal Ford
**Purpose:** Transform raw reading notes into clear, complete, and pedagogically effective study material.

---

## Expected structure per chapter

Each notes file should be named `chapter_XX.md` and follow this structure:

1. **Title & context** — Chapter name, number, and one sentence summarizing why this topic matters.
2. **Key concepts** — List of essential terms and definitions from the chapter.
3. **Deep dive** — Expanded explanation of the main ideas, organized with clear subheadings.
4. **Diagrams** — Text-based representations (ASCII/Mermaid) when they help visualize relationships, trade-offs, or flows.
5. **Practical examples** — Concrete cases or analogies that ground the theory.
6. **Connections** — Explicit links to previous chapters or cross-cutting concepts in the book.
7. **Review questions** — 3-5 questions to verify comprehension.

---

## Note transformation rules

When the user provides raw notes for a chapter, the agent must:

### Extend
- Complete ideas that are incomplete or overly summarized.
- Add context that the book provides but the notes omit (without inventing content outside the book).
- If a concept depends on another not explained in the notes, add a brief clarification or reference to the corresponding chapter.

### Clarify
- Rewrite ambiguous or confusing phrases in direct language.
- Prefer general-to-specific explanations: the idea first, then the detail.
- Use analogies only when they genuinely simplify; avoid forced analogies.
- When there are trade-offs, present them as a comparison table (pros/cons or scenarios where each option applies).

### Organize
- Group related ideas under descriptive subheadings.
- Use bullet lists for enumerations; short paragraphs for explanations.
- Maintain a consistent heading hierarchy: `##` for main sections, `###` for subsections.

### Do NOT
- Do not add personal opinions or content not found in the book.
- Do not remove the user's ideas even if they seem redundant — instead, integrate them better.
- Do not use unnecessary jargon; if a technical term appears, define it on first mention.
- Do not generate generic summaries like "this chapter talks about..."; go straight to the content.

---

## Language

- Notes are written in **English**.

---

## Formatting conventions

- Code or technical names go in `backticks`.
- Direct quotes from the book go in blockquotes (`>`).
- Use **bold** for key concepts; *italics* for emphasis.
- Mermaid diagrams are enclosed in ` ```mermaid ` blocks.

---

## Workflow

1. The user uploads or pastes their raw notes for a chapter.
2. The agent reads the notes and transforms them following these guidelines.
3. The agent presents the complete improved version.
4. The user reviews and can request specific adjustments.
