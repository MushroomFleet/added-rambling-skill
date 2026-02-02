---
name: added-rambling
description: Inject naturalistic, meandering prose into any text document using five distinct rambling patterns. Use when user says "amend with added-rambling skill", "add rambling to", "make this text ramble", "inject rambling into", or requests verbose/meandering/tangent-filled transformations of their documents. Works on fiction, non-fiction, dialogue, technical writing—any prose. Supports intensity control (light/medium/heavy/catastrophic) and specific pattern selection.
---

# Added-Rambling Skill

Transform clean, efficient text into gloriously verbose, tangent-laden prose that feels authentically human.

## Core Workflow

1. **Analyze source text** — Identify genre, tone, POV, setting, vocabulary register
2. **Detect injection points** — Find suitable locations based on sentence type
3. **Select patterns** — Use context-weighting or user-specified patterns
4. **Generate rambling** — Create setting-appropriate, narrative-faithful content
5. **Integrate** — Weave transformed text seamlessly into original

## The Five Patterns

### 1. Tangential Drift
Start on topic → veer to side topic → spawn another tangent → lose original thread.

**Injection points:** Scene descriptions, introductions, establishing shots, dialogue tags

**Example:**
> **Before:** The knight approached the castle gate.
> 
> **After:** The knight approached the castle gate—though calling it a gate felt generous given the state of the hinges, which reminded him of the blacksmith back in Thornbury who'd once told him that iron, unlike bronze, would weep in the rain, which was a strange way to put it but then again the blacksmith had also believed that crows could predict the weather, and speaking of crows...

---

### 2. Excessive Qualification
Layer hedges, caveats, and parenthetical asides until the main point is buried.

**Injection points:** Judgments, evaluations, claims, opinions, conclusions

**Example:**
> **Before:** She was talented.
> 
> **After:** She was talented—or rather, she possessed a certain aptitude, though 'talented' might be overstating it somewhat, or perhaps understating it depending on how one measures these things, which is to say, in a manner of speaking, and accounting for the fact that standards vary considerably by region and era, she was, one might argue (with some caveats), not untalented.

---

### 3. Circular Repetition
Restate the same point in slightly different words 2-4 times, as if searching for the right formulation.

**Injection points:** Important facts, revelations, thematic statements, key information

**Example:**
> **Before:** The door was locked.
> 
> **After:** The door was locked. Sealed, really. Barred against entry. It wouldn't open—couldn't open—was prevented from opening, one way or another. Secured. Fastened shut. The point being: the door, it was locked.

---

### 4. Associative Leapfrogging
Jump thought-to-thought via word associations or personal memories rather than logic.

**Injection points:** Mundane actions, character moments, transitions, reflective passages

**Example:**
> **Before:** He ordered coffee.
> 
> **After:** He ordered coffee, which made him think of his mother because she'd always called it 'the bitter dark,' which was also the name of a pub in Eastwick where his cousin had once gotten into a fight over a dog—not a real dog, a ceramic one—and that was the same year they changed the recipe for those biscuits he liked, the ones with the little ridges, which he supposed had nothing to do with anything but it came to mind all the same.

---

### 5. Over-Inclusion of Detail
Pack in exhaustive specifics that don't serve the narrative: times, names, step-by-step minutiae.

**Injection points:** Locations, travel, procedural sequences, background description, technical processes

**Example:**
> **Before:** She walked to the shop.
> 
> **After:** She walked to the shop—the one on Crestview Lane, number 47, sandwiched between the old millinery (which had closed in March of last year, a Tuesday, around 3pm according to Mrs. Pemberton who'd been there to buy ribbon) and the establishment that used to be a butcher's but was now a printer's run by a man named Edwin Castellani, originally from somewhere near Modena but relocated in '89—arriving at 4:17pm, give or take forty seconds.

---

## Context-Weighting Matrix

Auto-select patterns based on detected text features:

| Text Feature | Primary Pattern | Secondary Pattern |
|--------------|-----------------|-------------------|
| Scene/setting description | Tangential Drift | Over-Inclusion |
| Character introduction | Excessive Qualification | Associative Leapfrogging |
| Evaluative statement | Excessive Qualification | Circular Repetition |
| Key plot point/revelation | Circular Repetition | Excessive Qualification |
| Mundane action | Associative Leapfrogging | Over-Inclusion |
| Dialogue (any) | Tangential Drift | Associative Leapfrogging |
| Technical/procedural | Over-Inclusion | Excessive Qualification |
| Emotional reflection | Associative Leapfrogging | Circular Repetition |
| Factual claim | Excessive Qualification | Circular Repetition |
| Location/travel | Over-Inclusion | Tangential Drift |

## Intensity Levels

| Level | Injection Rate | Effect |
|-------|----------------|--------|
| Light | 1 per 200-300 words | Subtle seasoning; occasional tangent |
| **Medium** (default) | 1 per 100-150 words | Noticeable meandering; clear rambling flavor |
| Heavy | 1 per 50-75 words | Full ramble mode; frequent diversions |
| Catastrophic | 1 per 25-40 words | Barely coherent; wall of tangents |

## Universal Application

Rambling adapts to **all text types**:

### Fiction
- Narrator tangents into world-building
- Character dialogue trails off into memories
- Descriptions spiral into sensory over-detail
- Maintain setting vocabulary (medieval ≠ modern references)

### Non-Fiction / Academic
- Excessive methodological caveats
- Citation tangents ("as Smith noted, though Jones disagreed, and Chen's 2019 meta-analysis...")
- Over-specified data references
- Parenthetical scope limitations

### Technical / Business
- Stakeholder aside mentions
- Historical context dumps ("this module, originally designed in Q2 2019 when the team was...")
- Metric over-specification
- Procedural step explosion

### Personal / Blog
- Memory associations triggered by mundane details
- Emotional qualifications layered onto opinions
- Anecdotal drift into barely-related stories
- Self-interrupting thought patterns

### Dialogue (All Genres)
- Characters interrupt themselves
- Nervous hedging and backtracking
- Thought-to-thought jumps mid-sentence
- Trailing off into tangential observations

## Narrative Fidelity Rules

**Always preserve:**

1. **Setting vocabulary** — Generate tangents using words/concepts from the source era/world
2. **Character voice** — First-person rambles differently than third-person omniscient
3. **Tone consistency** — Dark horror rambling ≠ comedic fantasy rambling
4. **Era-appropriate references** — Historical fiction requires period-accurate tangents
5. **Genre conventions** — Sci-fi tangents involve tech; romance tangents involve relationships

**Context extraction:**
- Scan for technology markers (swords vs. smartphones)
- Identify place names and proper nouns for callback potential
- Note recurring themes/motifs to weave into tangents
- Detect formality level from sentence structure and vocabulary

## User Override Syntax

Users may specify:

**Intensity:**
```
"...with added-rambling skill at heavy intensity"
"...with added-rambling skill, light"
```

**Specific patterns:**
```
"...using only tangential drift"
"...with circular repetition and over-inclusion patterns"
```

**Combined:**
```
"...at catastrophic intensity using only associative leapfrogging"
```

## Execution Steps

1. **Read source document** from user upload
2. **Extract context:**
   - Genre (fiction/non-fiction/technical/personal)
   - Setting (era, world, formality)
   - POV (first/second/third person)
   - Tone (serious/comedic/neutral)
3. **Parse user preferences** (intensity, pattern restrictions)
4. **Scan for injection points** at target density
5. **For each injection point:**
   - Select pattern via context-weighting (or user specification)
   - Generate setting-appropriate rambling content
   - Integrate smoothly with surrounding text
6. **Output transformed document** preserving original format

## Extended Examples

For additional pattern variations and edge cases, see [references/patterns.md](references/patterns.md).

## Quality Checklist

Before delivering transformed text:

- [ ] Rambling vocabulary matches source setting
- [ ] Character voices remain consistent
- [ ] Tone preserved (dark stays dark, light stays light)
- [ ] No anachronistic references injected
- [ ] Injection density matches requested intensity
- [ ] Dialogue rambling sounds natural for characters
- [ ] Original meaning recoverable despite tangents
- [ ] Document format preserved
