# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

The Call of Asheron is an epic fantasy novel (~95k words, 186 pages) written in LaTeX. Four protagonists are transported from Ispar to the alien world of Dereth, where lifestones grant immortality at the cost of accumulating death-trauma. The novel explores forced migration, consciousness, transformation, and what survival costs.

**Status**: Complete manuscript. Revised Dec 2024 (trust readers, show don't tell), Feb 2025 (repetition sweep, volume balance, expansions). Focus on trusting readers, showing rather than telling.

## Building

```bash
pdflatex the_call_of_asheron.tex
pdflatex the_call_of_asheron.tex  # Run twice for TOC

# Clean auxiliary files if needed
rm -f *.aux *.log *.toc *.out
```

## Document Structure

Uses `memoir` class with two-column layout. Structure:

- **Volume I: The Calling** (12 chapters) - Protagonist introductions, individual arcs, first convergence
- **Volume II: The Awakening** (2 chapters) - Paths of Power, First Convergence
- **Volume III: The Schism** (2 chapters) - Olthoi Resurgence, Breaking Point
- **Volume IV: The Crucible** (2 chapters) - Evolution, Final Gambit
- **Volume V: The Transformation** (2 chapters) - Rituals, Final Battle

No epilogue. Ends with grounded present-moment scene.

## The Four Harbingers

| Character | Archetype | Core Drive |
|-----------|-----------|------------|
| **Duulak** | Scholar/mage | Understanding (retreats into analysis to escape guilt about Yasmin) |
| **Thomas** | Hunter | Return home (grief for Mara and William fuels desperate leadership) |
| **Maajid** | Transcendent | Transformation (embraces the "cosmic joke," loses humanity for perception) |
| **Marcus** | Commander | Purpose (builds civilization, becomes "armor with nothing inside") |

Each transformation is **physical, costly, and irreversible**. Ground abstract changes in concrete sensory details.

## LaTeX Conventions

### Dialogue
```latex
\begin{dialogue}
\item `Speaker text here'
\item `Response here'
\end{dialogue}
```
Note: Backticks open, apostrophes close (not standard LaTeX quotes).

### Virindi Speech
Always italicized: `\emph{We observe.}`

### Section Organization
- `\part*{}` for volumes
- `\chapter{}` for major plot movements
- `\section{}` for POV/scene changes
- No subsections

## World Elements

- **Lifestones**: Resurrect the dead but preserve death memories permanently
- **Olthoi**: Insectoid hive-mind, led by the Matriarch (intelligent, adaptive)
- **Virindi**: Thought-beings who observe and manipulate
- **Asheron**: Last Empyrean, architect of the Harbinger Protocol
- **The Mechanism**: Reality itself—the mystery that exceeds all bounded understanding

## Editorial Principles (from Dec 2024 revision)

### Show, Don't Tell
- Cut explanatory passages that follow scenes already demonstrating the point
- Ground transformations in physical sensation (nosebleeds, trembling hands, fingerprints fading)
- Use objects as emotional barometers (Yasmin's stone, Thomas's carved rabbit)

### Dialogue
- Use fragments, interruptions (`---`), incomplete thoughts
- No philosophical paragraphs under stress
- Physical reactions interspersed (jaw tightening, voice shaking)

### Character Grounding
- **Maajid**: Mother's cardamom memory as anchor; physical cost of timeline perception
- **Thomas**: Elena relationship; leadership through comforting individuals
- **Duulak**: Yasmin's stone; "grief-displaying subject" moment shows transformation
- **Marcus**: Condolence letters with steady hands; unopened letters showing avoidance

### Avoid
- Repetitive philosophical circling (characters conclude once, then demonstrate through behavior)
- "Cosmic joke" overuse (kept for Maajid's voice, cut from narration)
- Thesis statements disguised as scene endings ("That had to be enough")
- Omniscient exposition explaining character psychology
- Archetype labels in narration ("the Scholar," "the Commander")
- Distant future epilogues that flatten characters to allegorical functions

## Document Roles

| Role | File | Purpose |
|------|------|---------|
| **Manuscript** | `the_call_of_asheron.tex` | The novel. LaTeX source, single file. |
| **Timeline Authority** | `docs/timeline.md` | Authoritative chronological reference. All "when" questions answered here. |
| **Character Tracking** | `docs/characters.md` | Voice patterns, arc trajectories, emotional flickers, relationships. |
| **Lore/History** | `docs/lore.md` | The Mechanism, Three Failed Paths, Matriarch origin, Empyrean history, Virindi origin. |
| **Systems/Mechanics** | `docs/systems.md` | Magic-as-interface, ley lines, lifestones, hive architecture, Harbinger Protocol, geography. |
| **Themes/Anti-Cliche** | `docs/themes.md` | Core themes, genre avoidances, deliberate patterns (don't "fix" these). |
| **Style Conventions** | `docs/style.md` | LaTeX formatting, POV rules, prose principles, repetition management. |
| **Outline/Diagnostic** | `docs/outline.md` | Chapter-by-chapter breakdown, thread tracking, volume balance, character appearances. |
| **Editorial Backlog** | `docs/backlog.md` | Deferred ideas, continuity items, completed revisions log. |
| **Worldbuilding Design** | `WORLDBUILDING_DESIGN.md` | Original comprehensive design document (~900 lines). Lore and systems docs are extracted from this; it remains as deep reference. |

### Canonical Hierarchy

1. **Manuscript** — ground truth for what the story says
2. **Timeline** — authoritative for sequencing and duration claims
3. **Characters** — authoritative for voice patterns and arc state
4. **Lore, Systems** — authoritative for world facts
5. **Style, Themes** — authoritative for editorial decisions
6. **Outline** — diagnostic tool, not authoritative (reflects manuscript, doesn't drive it)
7. **Backlog** — holding pen, nothing here is canonical until promoted

### Propagation Notes

- **Timeline ↔ Characters:** Tightly coupled — death counts, transformation milestones, and "when they know what" depend on both. Check both when either changes.
- **Lore ↔ Systems:** Lore owns history and motivation; Systems owns mechanics. The Matriarch's origin is lore; her hive architecture is systems.
- **Style ↔ Themes:** Themes drive what to avoid; Style implements the rules. "No archetype labels" is a theme commitment; "use names not roles" is a style rule.
- **Outline → Everything:** The outline cross-references all docs. Update it when the manuscript changes significantly.
- **WORLDBUILDING_DESIGN.md:** Read-only reference. If new worldbuilding is needed, add to lore/systems docs, not this file.

## Recent Revisions

### Feb 2025 Editorial Pass
- Repetition sweep: "the particular" 29→9, "cosmic joke" 28→16, "forty-three years" 10→2
- Ch 9 "Echoes" compression (~190 lines cut — removed recap of already-shown material)
- Marcus redundancy compression (identity-through-duty internal monologue)
- Final Battle: Day headers removed, transitional scenes added (~80 lines)
- Matriarch Confrontation expanded (~80 lines)
- Resolution section enhanced
- Worldsmith documentation ecosystem created (docs/ directory)

### Dec 2024 Revision
- Cut Virindi omniscient exposition (~73 lines)
- Cut "One Hundred Years Hence" epilogue
- Removed narrator archetype labeling
- Added Matriarch sympathetic framing
- Restored Thomas-Virindi longing theme
- Voice differentiation in final confrontation
