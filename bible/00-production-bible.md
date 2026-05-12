# GF Webtoon - Production Bible

**Format:** Vertical-scroll webtoon  
**Style Direction:** Anime-inspired, cinematic, vibrant, luminous, elegant, mystery-forward  
**Source Basis:** Session notes first, not transcripts  
**Primary Characters:** Vesper Aurelius and Leo Gray  
**Series Tagline:** *The Empire does not run on faith alone. It runs on faith and receipts.*

---

## 1. Core Adaptation Goal

Turn the campaign into a polished vertical webtoon that feels like:

- A divine-bureaucratic thriller wrapped in radiant anime fantasy.
- A two-protagonist investigation where Vesper and Leo enter the same conspiracy from different doors.
- A luminous empire with rot under the gold leaf.
- A story where paperwork, faith, and murder share the same handwriting.

---

## 2. Adaptation Principles

### Preserve

- The phrase-level identity of the campaign.
- The dual-lead structure:
  - **Leo Gray:** street-level investigation, covert work, forged documents, hidden evidence.
  - **Vesper Aurelius:** noble office, sanctity compliance, divine social theater, magical perception.
- The contrast between public order and private corruption.
- Every major clue with exact continuity.

### Compress

- Long exposition becomes broadcast captions, ledger pages, architectural shots, documents, and silent reaction panels.
- D&D procedural checks become clean visual beats: eyes, hands, seams, marks, seals, and reveals.

### Avoid

- Dumping lore too early.
- Making the Empire generically evil.
- Turning every session beat into equal panel weight.

---

## 3. Expandable Architecture

Recommended hierarchy:

```md
Gilded Fracture Webtoon Repo
├─ README.md
├─ bible
│  ├─ 00-production-bible.md
│  ├─ character-bible.md
│  ├─ location-bible.md
│  ├─ visual-style-bible.md
│  ├─ clue-tracker.md
│  └─ asset-tracker.md
├─ arcs
│  ├─ S00-prologue.md
│  ├─ S01-session-01-opening-investigation.md
│  └─ S02-session-02-tbd.md
└─ sources
   ├─ source-session-map.md
   └─ glossary-notes.md
```

---

## 4. Arc / Episode Logic

Every major story block is an **arc file**.

- The **prologue** is Arc `S00`.
- Each **campaign session** becomes the next arc file: `S01`, `S02`, `S03`, etc.
- All webtoon episodes live **inside their parent arc file**.
- The main bible stays readable and global.

| Unit | Meaning | Example |
|---|---|---|
| Arc | Major story block | S00: Prologue, S01: Session 01 Opening Investigation |
| Webtoon Episode | Chapter inside the arc | S01-E01: Leo at the Tea House |
| Scroll Section | Internal episode chunk | S01-E01-S03: Leo’s Apartment |
| Panel Cluster | Micro-scene beat | Stamp montage, clue reveal, thought-reading beat |

---

## 5. Numbering System

```md
S00 = Prologue Arc
S00-E01 = Prologue, Episode 1
S01 = Session Arc 1
S01-E01 = Session 1, Episode 1
S01-E01-S01 = Session 1, Episode 1, Scroll Section 1
S01-E01-S01-P001 = Session 1, Episode 1, Section 1, Panel 1
```

This keeps everything under the arc file structure.

---

## 6. Current Arc Index

| File | Source | Status | Function |
|---|---|---|---|
| arcs/S00-prologue.md | Session notes prologue | Designed | Series premise |
| arcs/S01-session-01-opening-investigation.md | SRC-S01 | In Design | Session 1 adaptation arc |

---

## 7. Episode Index Logic

Episodes should be listed inside their parent arc file, not as separate files by default.

Example inside `arcs/S01-session-01-opening-investigation.md`:

| Episode | Source Scene | Main POV | Function | Status |
|---|---|---|---|---|
| S01-E01 | Leo at the Tea House | Leo | Introduce Leo and Felda’s hidden note | Planned |
| S01-E02 | Vesper’s First Day | Vesper | Introduce Vesper’s office and assignment | Planned |

---

## 8. Webtoon Compilation System

Design each episode as:

```md
Episode
├─ Opening Hook
├─ Scroll Section 1
│  ├─ Panel Cluster A
│  ├─ Panel Cluster B
│  └─ Scroll Pause
├─ Scroll Section 2
│  ├─ Panel Cluster C
│  ├─ Panel Cluster D
│  └─ Visual Reveal
└─ Cliffhanger
```

Practical rule:

- 6 to 8 scroll sections per episode.
- 2 to 4 panel clusters per scroll section.
- 3 to 8 panels per cluster.
- 1 major reveal image per episode.
- 1 cliffhanger image at the end.

---

## 9. Status Labels

| Status | Meaning |
|---|---|
| Planned | Outline only |
| Designed | Detailed episode structure exists |
| Scripted | Final panel/dialogue script drafted |
| Thumbnailed | Rough vertical layout planned |
| In Art | Being illustrated |
| Lettered | Text added |
| QA | Continuity and readability review |
| Final | Ready for release/archive |

---

## 10. Deprecated Structure

The following folders/files are deprecated from earlier structure experiments:

```md
/prologue
/episodes
/arcs/A01-faith-and-receipts.md
```

Going forward, use only:

```md
/arcs/S00-prologue.md
/arcs/S01-session-01-opening-investigation.md
```

---

## 11. Change Log

### 2026-05-12

- Created GitHub Markdown workspace.
- Established expandable architecture.
- Standardized protagonist name as **Leo Gray**.
- Updated model: the prologue is Arc `S00`; every campaign session becomes an arc file; episodes are nested inside arc files.
