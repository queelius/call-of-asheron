# Style Conventions

Prose guardrails: how the story is told, distinct from what it tells. This document maintains consistency across editing sessions and prevents well-meaning "corrections" of deliberate stylistic choices.

---

## LaTeX Formatting

### Dialogue
```latex
\begin{dialogue}
\item `Speaker text here'
\item `Response here'
\end{dialogue}
```
**Note:** Backticks open, apostrophes close. This is NOT standard LaTeX quoting (`\`text'`) — it's a deliberate formatting choice used throughout the manuscript.

### Virindi Speech
Always italicized: `\emph{We observe.}` — transmitted directly into minds, not spoken aloud.

### Em Dashes
Use `---` (three hyphens) for em dashes in interruptions, asides, and breaks. This is standard LaTeX.

### Section Organization
- `\part*{}` for volumes (Volume I through V)
- `\chapter{}` for major plot movements
- `\section{}` for POV/scene changes
- No subsections (removed Dec 2024 — `\subsection*{Day One}` etc. were converted to continuous narrative)

### Document Class
`memoir` with two-column layout.

---

## POV & Narration

### Third-Person Close
Each section follows one character's perspective closely. The narrator can access that character's thoughts and perceptions but NOT other characters' internal states.

**Do:** "Thomas watched Marcus's jaw tighten" (observable)
**Don't:** "Marcus felt the familiar weight of command settle onto his shoulders" (unless it's Marcus's section)

### No Omniscient Exposition
The Virindi omniscient exposition section (~73 lines telling readers what characters thought) was cut in Dec 2024. Don't reintroduce this pattern.

**Do:** Show through physical action, dialogue, objects
**Don't:** "What none of them realized was..." or "Each Harbinger processed this differently..."

---

## Prose Principles

### Show, Don't Tell
- Cut explanatory passages that follow scenes already demonstrating the point
- Ground transformations in physical sensation (nosebleeds, trembling hands, fingerprints fading)
- Use objects as emotional barometers:
  - Yasmin's obsidian stone (Duulak)
  - Carved wooden rabbit (Thomas)
  - Condolence letters with steady hands (Marcus)
  - Cardamom pods (Maajid)

### Dialogue Under Stress
- Use fragments and interruptions (`---`)
- Incomplete thoughts
- Physical reactions interspersed (jaw tightening, voice shaking, hands trembling)
- No philosophical paragraphs under stress — that's for calm scenes
- Characters conclude once, then demonstrate through behavior (no repetitive philosophical circling)

### Voice Differentiation
Each character should sound distinct in dialogue. See `characters.md` for full voice patterns. Quick reference:

- **Duulak:** Analytical, hypothesis-driven. "The probability of..." "If I'm interpreting correctly..." Longer sentences. Academic vocabulary.
- **Thomas:** Terse, visceral, practical. Fragments. Hunter metaphors. "Take the shot or don't."
- **Marcus:** Military precision. Orders, assessments, tactical framing. Even personal thoughts in strategic language.
- **Maajid:** Irreverent, paradoxical. Shifts from casual to profound mid-sentence. "Can't it be both?" Uses "the void" as shorthand.

---

## Repetition Management

### Current Counts (Feb 2025 revision)

| Pattern | Count | Target | Notes |
|---------|-------|--------|-------|
| "the particular [noun] of [person]" | 9 | 8-10 | Was 29 → 19 → 9. Keep for Thomas and Maajid sections (visceral). |
| "cosmic joke" | 16 | ~16 | Was 28 → 26 → 16. Tracks Maajid's arc — keep where it evolves. |
| "forty-three years" | 2 | 2-3 | Was 10 → 7 → 2. Keep in Marcus's intro and strongest usage. |
| "forty-three" (all uses) | 9 | ~10 | Was 16 → 9. Varied unrelated uses (sightings, deaths, hybrids). Keep for Marcus's age (43) and cooperation probability (43%). |
| "something like wonder, something like grief" | 1 | 1 | Duplicate rewritten. |
| "something that might have been" | 4 | 3-4 | Was 6 → 4. Rewrote weakest 2 instances. |
| "the question is" | 18 | ~10 | Authorial fingerprint — natural in Duulak, bleeds into all characters. Watch in future edits. |

### Intentional Repetitions (DO NOT "fix")

- **"Cosmic joke"** progression through Maajid's arc (see `themes.md`)
- **Thomas touching the rabbit** at emotionally significant moments
- **Marcus's tactical framing** of personal situations — this IS his character
- **Lifestone resurrection** described differently per character each time
- **"The Mechanism"** — always capitalized, always mysterious, never explained

---

## Anti-Patterns to Watch

These creep back in during editing. Watch for and remove:

1. **Archetype labels in narration:** "the Scholar studied...", "the Commander assessed..." → Use their names
2. **Post-scene explanation:** Scene shows Thomas's grief → narrator paragraph explaining that Thomas felt grief → cut the paragraph
3. **"Perhaps that was answer enough"** — thesis-statement scene endings. Let scenes end on action or image
4. **"Portal gave him what he sought/feared"** — was appearing 4 times. Each should be unique
5. **Recap within recap:** Ch 9 "Echoes" pattern — each POV re-describing the other three characters. Already compressed significantly in Feb 2025 revision
