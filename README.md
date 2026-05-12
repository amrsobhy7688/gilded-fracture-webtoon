# Gilded Fracture Webtoon

A modular Markdown workspace for adapting the **Gilded Fracture** D&D campaign into a vertical-scroll webtoon.

## Project Format

- **Story format:** Vertical-scroll webtoon
- **Visual direction:** Anime-inspired, cinematic, vibrant, luminous, elegant, mystery-forward
- **Source basis:** Session notes first, not transcripts
- **Main protagonists:** Vesper Aurelius and Leo Gray

## Current Structure

```md
/bible
  00-production-bible.md
  character-bible.md
  location-bible.md
  visual-style-bible.md
  clue-tracker.md
  asset-tracker.md

/arcs
  S00-prologue.md
  S01-session-01-opening-investigation.md
  S02-session-02-tbd.md

/sources
  source-session-map.md
  glossary-notes.md
```

## Organization Rule

- Every major story block is an **arc file**.
- The **prologue** is Arc `S00`.
- Each **campaign session** becomes the next arc file: `S01`, `S02`, `S03`, etc.
- All webtoon episodes live **inside their parent arc file**.
- The main bible stays readable and global.

## Deprecated Folder Note

The `/episodes` and `/prologue` folders were part of earlier structures. Going forward, episode designs should live inside `/arcs`.
