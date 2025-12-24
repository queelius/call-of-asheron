# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

The Call of Asheron is an epic fantasy novel (~95k words, 186 pages) written in LaTeX. Four protagonists are transported from Ispar to the alien world of Dereth, where lifestones grant immortality at the cost of accumulating death-trauma. The novel explores forced migration, consciousness, transformation, and what survival costs.

**Status**: Complete draft, revised December 2024. Focus on trusting readers, showing rather than telling.

## Building

```bash
pdflatex the_call_of_asheron.tex
pdflatex the_call_of_asheron.tex  # Run twice for TOC
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

## Recent Revisions (Dec 2024)

### Trust Readers More
- Cut Virindi omniscient exposition section (~73 lines) that told readers what characters thought
- Cut "One Hundred Years Hence" epilogue that reduced characters to labels
- Removed narrator archetype labeling; show through physical action instead

### Deepened Characterization
- **Matriarch**: Added sympathetic framing—she's seeking understanding, not just conquering
- **Thomas-Virindi**: Echo of longing theme in final scene; they've both changed
- **Voice differentiation**: Restored distinct voices in final confrontation

### Worldbuilding Document
See `WORLDBUILDING_DESIGN.md` for detailed background on:
- Olthoi hive structure and Matriarch's tragedy
- Virindi origin (the Keth'ra) and what they lost
- Empyrean history and the Consensus
- Harbinger Protocol psychological selection mechanics
- Crystalline ecology and Isparian cultures
