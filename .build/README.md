# Same Words, New Language

Nine Bible passages, before and after Tyndale — the Latin Vulgate and John
Wycliffe's 1395 English on one side, William Tyndale's own 1520s–30s
translation on the other.
Special Collections & Archives, BYU–Idaho.

## Deliverables (`Same Words, New Language - Web.html`, root)

The web/embeddable version — for the exhibit's companion website
(spc.byui.edu), styled to House Style. Text-only, no images. Needs
`support.js` as a sibling file; loads its two fonts (Newsreader, Archivo)
from Google Fonts.

Published automatically to openEQUELLA on every push to `main` (see
`.github/workflows/oeq-publish.yml`).

## Print deliverables (`print/`)

The physical flip-card set: nine individual 4×6" landscape cards, a
reference card, a combined "Print - Flip Cards" sheet, plus the shared
`doc-page.js` and `_ds/` design-system assets that sheet depends on. These
are fabrication files for the physical exhibit, not part of the website.

**⚠️ Known inconsistency, flagged 2026-09-18, not yet fixed:** the web
version's Card 5 was swapped from "A stranger in a strange land" to
"Shepherds abiding in the field" (Luke 2:8) — see
`AI-GEN/2026-09-17-tyndale-flip-card-claude-design-prompt.md` in the
archives workflow vault for the decision and reasoning. **The print card
set still has the old "A stranger in a strange land" content for Card 5**
— it was not regenerated with the swap. Card 5's print card needs to be
rebuilt before these go to print, or the physical and digital versions of
this exhibit will tell two different stories.

## The ninth card

The web version and print set both include a ninth phrase, "Eat, drink,
and be merry" (Luke 12:19), beyond the 8-card starter set originally
recommended. This was Adam's own addition, not part of the original
design doc's recommendation — noted here for the record, not flagged as
an error.

## Companion exhibits

*The Words That Stayed* (the thirty-five surviving phrases), *Tyndale's
Exile* (the interactive route map), and *A Life in Translation* (the life
timeline) ship as their own repositories.
