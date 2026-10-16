# SutRa — Interactive Storytelling Platform

> **Tagline:** *Every Choice Weaves a New Story.*

**SutRa** is an interactive storytelling platform and authoring studio where writers create branching choose-your-own-adventure narratives and readers experience them through choices that shape the plot, alter variables, and lead to multiple distinct endings.

---

## 🌟 Key Features

### 📖 Reading Experience
* **Cinematic Dark-Mode Home Page**: Styled with amber accents, genre pill badges, star ratings, and featured story cards.
* **Immersive Reading Player**: Features smooth typewriter text rendering, interactive choice buttons, active state inventory drawer, and discovered ending trackers.
* **Variable & Condition Tracking**: Dynamic plot branching based on reader inventory items (e.g., `has_key`, `magnifying_lens`), affection meters, and deduction scores.
* **Rich Multi-Genre Library**: Preloaded with high-quality branching stories (Mystery, Thriller, Romance, Horror, Sci-Fi, and Comedy) including *Sherlock Holmes: The Adventure of the Black Onyx*.

### 🎨 Visual Story Editor & Visual Graph
* **Interactive Story Graph**: Pan, zoom, and drag scene nodes visually. Add and disconnect choice paths in real time.
* **4-Choice Branching Constraint**: Enforces up to 4 choices per decision scene to guarantee deep story paths.
* **Story Health Validator**: Automated graph auditor that alerts authors to unreachable scenes, dead-end paths, missing start scenes, or unlinked choices.
* **Safe Scene Deletion with Narrative Continuity**:
  * **Prose Filtering**: Automatically strips decorative/enhancement flavor text added for pacing.
  * **Inline Linking Continuity**: Extracts essential items, clues, and plot state modifications into concise `[Continuity Note]` entries and injects them directly into destination scenes.
  * **Deletion Dry-Run**: Pre-deletion simulation previewing stripped text, preserved variable state, and graph connectivity before committing changes.

### 💾 Data Persistence & Portability
* **Full Local Persistence**: Automatic saving to browser storage so local progress, story drafts, and discovered endings are retained across sessions.
* **JSON Import & Export**: Download full story schema structure as standalone JSON files or import external story bundles safely.
* **Undo / Redo & Versioning**: Snapshot history allowing authors to revert destructive changes cleanly.

---

## 🎯 Preloaded Story Library Specifications

All preloaded stories in SutRa conform to the following structural guarantees:
* **Minimum Reading Time**: $\ge$ 2 minutes estimated read time based on total word count.
* **Minimum Scene Count**: $\ge$ 6 fully written scenes per story.
* **Choice Breadth**: 4 distinct choice options on every non-ending decision scene.

| Title | Genre | Est. Read Time | Scenes | Key Variables / Features |
| :--- | :--- | :--- | :--- | :--- |
| **Sherlock Holmes: Black Onyx** | Mystery | ~8 min | 10 | Clue score, inventory tracking, conditional paths |
| **The Undertow** | Crime Drama | ~6 min | 7 | Trust meter, brawl choices, 4 reachable endings |
| **Nighthawks** | Noir Thriller | ~5 min | 6 | Evidence tracking, timed tension choices |
| **Pariah Station** | Sci-Fi Thriller | ~6 min | 7 | Keycard clearance, battery power management |
| **The Midnight House** | Gothic Horror | ~5 min | 7 | Flashlight battery, sanity level, secret door |
| **Echoes Across Autumn** | Romance | ~4 min | 6 | Affection score, emotional branching endings |
| **Novice Wizard Misadventures** | Comedy | ~3 min | 6 | Spell energy meter, chaotic mishaps |

---
