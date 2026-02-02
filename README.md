# 🌀 Added-Rambling Skill

A Claude skill for injecting naturalistic, meandering prose into any text document. Transform clean, efficient writing into gloriously verbose, tangent-laden rambling that feels authentically human.

## What It Does

The **added-rambling** skill reads your input text, identifies suitable injection points, and weaves in context-appropriate rambling using five distinct patterns. It preserves narrative fidelity—a medieval fantasy won't suddenly reference smartphones, and a technical document won't drift into fairy tales.

**Before:**
> The knight approached the castle gate.

**After:**
> The knight approached the castle gate—though calling it a gate felt generous given the state of the hinges, which reminded him of the blacksmith back in Thornbury who'd once told him that iron, unlike bronze, would weep in the rain, which was a strange way to put it but then again the blacksmith had also believed that crows could predict the weather, and speaking of crows...

## The Five Rambling Patterns

| Pattern | Description | Best For |
|---------|-------------|----------|
| **Tangential Drift** | Starts on topic, veers onto loosely related side topics, spawns tangents until the original thread is lost | Scene descriptions, introductions, establishing shots |
| **Excessive Qualification** | Layers hedges, caveats, and parenthetical asides onto every statement | Character judgments, opinions, evaluative statements |
| **Circular Repetition** | Restates the same point in slightly different words multiple times | Key revelations, important facts, thematic statements |
| **Associative Leapfrogging** | Jumps thought-to-thought via word associations or memories rather than logic | Mundane actions, character moments, transitions |
| **Over-Inclusion of Detail** | Packs in exhaustive specifics that don't serve the narrative | Locations, travel sequences, procedural descriptions |

## Installation

1. Download the `added-rambling.skill` file from the [Releases](https://github.com/MushroomFleet/added-rambling-skill/releases) page
2. Upload to your Claude skill library
3. The skill will automatically trigger when you use the activation phrase

## Usage

### Basic Trigger
```
Amend my 'draft.md' with the added-rambling skill
```

### Supported File Types
- `.md` (Markdown)
- `.txt` (Plain text)
- `.docx` (Word documents)
- Any prose-based document

### Intensity Levels

| Level | Description | Injection Rate |
|-------|-------------|----------------|
| Light | Subtle seasoning | ~1 per 200-300 words |
| **Medium** (default) | Noticeable meandering | ~1 per 100-150 words |
| Heavy | Full ramble mode | ~1 per 50-75 words |
| Catastrophic | Barely coherent | ~1 per 25-40 words |

### Specifying Intensity
```
Amend my 'draft.md' with the added-rambling skill at heavy intensity
```

### Requesting Specific Patterns
```
Amend my 'draft.md' with the added-rambling skill using only tangential drift and circular repetition
```

## Universal Application

This skill works on **all text types**—fiction, non-fiction, technical writing, and dialogue alike:

| Text Type | Rambling Flavor |
|-----------|-----------------|
| Fiction (narrative) | Character tangents, world-building asides, sensory over-description |
| Academic/Technical | Excessive caveats, methodological digressions, citation tangents |
| Business/Reports | Stakeholder asides, historical context dumps, metric over-specification |
| Personal/Blog | Memory associations, emotional qualifications, anecdotal drift |
| Dialogue | Character-voice tangents, nervous hedging, thought-interruptions |

## Examples

### Fiction Example

**Input:**
> She was talented.

**Output (Excessive Qualification):**
> She was talented—or rather, she possessed a certain aptitude, though 'talented' might be overstating it somewhat, or perhaps understating it depending on how one measures these things, which is to say, in a manner of speaking, and accounting for the fact that standards vary considerably by region and era, she was, one might argue (with some caveats), not untalented.

### Non-Fiction Example

**Input:**
> The experiment confirmed our hypothesis.

**Output (Excessive Qualification + Circular Repetition):**
> The experiment—and one hesitates to call it definitive, though it was certainly suggestive, or at minimum not unsuggestive—confirmed, or appeared to confirm, or at least failed to disconfirm, our hypothesis. The hypothesis was supported. Validated, one might say. Borne out by the data, such as it was, which is to say the data pointed in the direction we'd anticipated, more or less.

### Dialogue Example

**Input:**
> "I need to leave," he said.

**Output (Associative Leapfrogging):**
> "I need to leave," he said, "which reminds me—did I tell you about my uncle who always said goodbye three times? Once for politeness, once for meaning it, once because he'd forgotten he already said it. He had a dog like that too, a retriever, though what it retrieved was anyone's guess. Anyway, I should go."

## How It Works

1. **Text Analysis**: The skill reads your document and identifies the genre, tone, POV, and setting
2. **Injection Point Detection**: Suitable locations for rambling are identified based on sentence type and context
3. **Pattern Selection**: Context-weighted algorithm selects appropriate patterns (or uses your specified patterns)
4. **Dynamic Generation**: Rambling content is generated using vocabulary and references consistent with the source material
5. **Integration**: Transformed text is woven seamlessly into the original document

## Configuration

The skill uses sensible defaults but can be customized:

| Option | Default | Description |
|--------|---------|-------------|
| `intensity` | Medium | How frequently rambling is injected |
| `patterns` | All (context-weighted) | Which rambling patterns to use |
| `preserve_dialogue` | false | Set to true to only ramble in narration |

## Contributing

Contributions welcome! Areas of interest:
- Additional rambling patterns
- Genre-specific tuning
- Edge case handling

## License

MIT License - See [LICENSE](LICENSE) for details.

---

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{added_rambling_skill,
  title = {Added-Rambling Skill: A Claude skill for injecting naturalistic rambling patterns into text},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/added-rambling-skill},
  version = {1.0.0}
}
```

### Donate

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)
