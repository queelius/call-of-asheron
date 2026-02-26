# Consistency Auditor Report

**Date**: 2026-02-25
**Scope**: Full manuscript (6,674 lines, all 5 volumes)
**Auditor**: worldsmith:consistency-auditor

---

## HIGH Issues

### H1. Thomas's Totem Object Discontinuity (baby tooth vs. carved rabbit)

- **Location**: Line 1531 (Ch 4) vs. lines 5028, 6431, 6521, 6619, 6644 (Ch 12 onward)
- **Quoted text (line 1531)**: "Thomas pulled out the leather cord from under his shirt---William's baby tooth, the one tooth he'd been home to see come loose."
- **Quoted text (line 5028)**: "Thomas's fingers found the carved rabbit in his pocket"
- **Quoted text (line 6644)**: "He'd carved it for William, but William had never received it."
- **Problem**: In Ch 4, Thomas's totem is William's baby tooth on a leather cord (worn around neck). From Ch 12 onward, it is a carved wooden rabbit in his pocket (carved for William but never delivered). There is no transition scene showing him acquiring or carving the rabbit, and the baby tooth disappears without mention. These appear to be two different objects. The baby tooth is a found object (taken from life); the rabbit is a made object (created from love). The manuscript treats them as if the rabbit has always been the totem.
- **Suggestion**: Either (a) add a brief moment in Vol I or Vol II where Thomas carves the rabbit (perhaps during a quiet night, using his knife, after losing the baby tooth), or (b) unify them --- Thomas has both objects, the tooth and the rabbit, and the rabbit becomes dominant as the tooth wears down. The backlog already flags this.

### H2. Sara: Age and Arrival Timeline Contradictions

- **Location**: Line 4522 (Ch 11, "The Reckoning") vs. line 5609 (Ch 15, "The Siege of Haven")
- **Quoted text (line 4522)**: "One of them was a girl named Sara. She was twelve. She'd only been with us for three weeks."
- **Quoted text (line 5609)**: "A young woman named Sara, who'd arrived through the portals only six months ago"
- **Problem**: In Vol I (The Reckoning, ~4 months after arrival), Sara is described as a twelve-year-old girl who arrived three weeks ago. In Vol III (The Siege, ~3 years after arrival), Sara is described as a "young woman" who arrived "six months ago." If this is the same character, she should be approximately 15 by the siege. The shift from "girl" to "young woman" is plausible over 3 years, but the "arrived six months ago" contradicts her earlier arrival. If she's a different Sara, the repeated name creates confusion, especially since she appears during battle scenes both times and is associated with Thomas.
- **Suggestion**: If same Sara, change "arrived through the portals only six months ago" to something reflecting her longer presence. If different Sara, give the second character a different name.

### H3. Gaius's Arrival Timeline Inconsistency

- **Location**: Line 2467 (Ch 7, Marcus's arrival period, weeks 1-6), line 5278 (Ch 13, ~6 months, Lucia scene), line 5545 (Ch 15, ~3 years), line 5891 (Ch 17, ~3.5 years)
- **Quoted text (line 5545)**: "his lieutenant, Gaius---who had eventually followed him through a portal---reported"
- **Quoted text (line 5891)**: "Gaius, his lieutenant, who'd followed him through a portal two years after his own arrival"
- **Problem**: Gaius appears in Marcus's very first scenes on Ispar (line 412) and on Dereth (line 2467), behaving as his existing lieutenant. He is present throughout Vol I at Fort Ironwood. Then line 5545 says he "eventually followed him through a portal" and line 5891 says he arrived "two years after" Marcus. But Gaius appears at Fort Ironwood in Marcus's earliest Dereth scenes, well before the two-year mark. This is a genuine contradiction: either Gaius was already on Dereth from early on, or he arrived two years later and shouldn't appear in Vol I's Fort Ironwood scenes.
- **Suggestion**: The simplest fix is to remove the "two years after" and "eventually followed" language. Instead, Gaius could have followed Marcus through the portal almost immediately (within days/weeks), which is consistent with his presence in all Vol I scenes. Alternatively, Gaius's early Fort Ironwood appearances need to be attributed to a different lieutenant.

---

## MEDIUM Issues

### M1. Volume I/Volume II Structural Overlap (Duplicate Events)

- **Location**: Ch 10-12 (Vol I) vs. Ch 13-14 (Vol II)
- **Problem**: The First Convergence is presented in Ch 10 (~3 months after arrival) with full detail, then re-presented in Ch 14 as "The First Convergence" (~2 years after arrival). Similarly, Asheron appears physically in Ch 12 and again in Ch 16. The Harbinger Protocol is decoded in both Ch 12 (Asheron explains) and Ch 13 (Duulak discovers independently). The time-differential is revealed in both Ch 12 (line 4954) and Ch 16 (line 5787).
- **Assessment**: The outline flags this and notes it may be intentional (Volume I detailed, Volume II compressed recap). However, the chronological confusion is significant. Ch 14's "Two years after the first arrivals" contradicts Ch 10's ~3-month timeline for what appears to be the same event. If these are different events, the narrative doesn't distinguish them clearly enough.
- **Suggestion**: Add a brief temporal anchor at the start of Volume II clarifying the time jump and relationship to Volume I events. Something like: "The first years compressed into memory..." Alternatively, consider whether Ch 14 recaps material already fully covered in Ch 10-12 and could be trimmed to only the new information (the Realization scene at the end).

### M2. "Forty-Three" Numerical Coincidence

- **Location**: Lines 237, 405, 2465, 2783, 3387, 3391, 3416, 3439, 3678, 3875, 5141, 5534 (Marcus's age), 5940 (hybrids killed)
- **Problem**: The number 43 appears with remarkable frequency: Marcus is 43 years old, Duulak has died 43 times at the 6-month mark, Marcus kills 43 hybrids, Marcus has 43 soldiers too traumatized to return to duty, and the Virindi give Thomas a 43% cooperation probability. The style doc records "forty-three years" was reduced from 10 to 2 instances, but the number 43 itself recurs in other contexts. This creates a sense of authorial fingerprint rather than organic worldbuilding.
- **Suggestion**: Vary some of these numbers. The 43 deaths (Duulak) and 43 age (Marcus) are well-established; changing others (hybrids, traumatized soldiers, probability percentage) would reduce the pattern.

### M3. Archetype Labels in Narration (Line 4665)

- **Location**: Line 4665
- **Quoted text**: "Four leaders, becoming more purely their archetype functions."
- **Problem**: The editorial principles explicitly prohibit archetype labels in narration ("the Scholar," "the Commander"). This line uses "archetype functions" in the narrator's voice, which violates the spirit of that rule. The CLAUDE.md and themes doc both flag this as a pattern to avoid.
- **Suggestion**: Rewrite to show rather than tell. E.g., "Four leaders, each crystallizing into the version of themselves Asheron had designed them to become."

### M4. Maajid's Death Count Arithmetic

- **Location**: Lines 2337, 2400, 3547, 3709
- **Problem**: The character doc says "41 deaths in first three months" and "42nd deliberate" (total 42 by the meeting). The manuscript at line 3547 has Duulak saying "forty-two times in three months." At line 3709, Maajid's death count at the meeting should be 47. The timeline doc notes the 37th death as a threshold. The arithmetic is roughly consistent but scattered across many locations, making it hard for readers to track.
- **Assessment**: LOW priority --- the counts are approximately consistent and the manuscript doesn't require precise tracking.

### M5. "Something that might have been" Pattern (6 instances, target 3-4)

- **Location**: Lines 375, 550, 2119, 2160, 3228, 5780
- **Problem**: The style doc records 5 instances with a target of 3-4. I count 6 instances of "something that might have been [X] or might have been [Y]" or close variants. This exceeds the target.
- **Suggestion**: Cut 2 instances, keeping the strongest. Line 5780 (Asheron looking at Thomas "with something that might have been respect") is the most impactful and should be retained.

---

## LOW Issues

### L1. Maajid's Portal Location

- **Location**: Line 381 ("In the humble village") vs. line 1938 ("The Cosmic Joke" --- portal in royal courtyard in Mawwuz)
- **Problem**: CLAUDE.md says Marcus's portal appeared "at Legion training ground after promotion ceremony (line 5151)." The manuscript at line 5151 confirms this. However, the timeline doc says Maajid's portal appeared "day before entrance examination" in a "royal court." The manuscript at lines 1938-1996 shows the portal in a "royal courtyard" in Mawwuz. This is consistent internally but CLAUDE.md line 26 says "Ch 2 opening, line ~381" for Maajid's crossing. Line 381 is actually Maajid's brief introduction in Ch 1, not his full crossing scene.
- **Assessment**: Minor cross-reference error in documentation, not in manuscript.

### L2. Elena's Relationship to Thomas in Volume IV

- **Location**: Line 5891
- **Quoted text**: "Elena, borrowed from Haven, whose hunter's eyes missed nothing."
- **Problem**: Elena is described with "hunter's eyes" --- but Elena is Haven's co-leader and defender, not a hunter. Thomas is the hunter. This phrasing may be attributing Thomas's characteristic to Elena.
- **Suggestion**: Change to "whose fighter's eyes missed nothing" or "whose survivor's eyes missed nothing."

### L3. Cosmic Joke Count (16 instances per style doc)

- I count approximately 16 instances in the manuscript, which matches the style doc's target. The reduction from 28 appears successful.

---

## Strengths

1. **Death counts are internally consistent within volumes.** Thomas's 10 deaths at 5 weeks, 17 by "months to years," and 11 during the siege are trackable and non-contradictory.
2. **The time-differential math is consistent.** 20:1 ratio, 6 months = 10 years, centuries at 3+ years --- all track correctly.
3. **Physical transformation markers are consistent across appearances.** Duulak's translucent hands, Maajid's flickering form, Marcus's five bodies, Thomas's white hair --- each is introduced and maintained through subsequent appearances.
4. **The Matriarch's characterization is consistent.** Seeker, not conqueror, from her first mention (Ch 11) through the final confrontation.
