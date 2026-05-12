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

/prologue
  P00-the-ledger-and-the-missing-forty-six.md

/arcs
  S01-session-01-opening-investigation.md
  S02-session-02-tbd.md

/sources
  source-session-map.md
  glossary-notes.md
```

## Organization Rule

- The **prologue** is separate because it establishes the whole series premise.
- Each **campaign session** becomes one arc file.
- Each arc file contains all webtoon episodes adapted from that session.
- Detailed episode designs are appended inside the relevant arc file instead of split into many separate episode files.
- The main bible stays readable and global.

## Deprecated Folder Note

The `/episodes` folder was part of an earlier structure. Going forward, episode designs should live inside their session arc file.
