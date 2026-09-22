# Template: manifest

A manifest is the deposit's table of contents: a plain-text file
listing every work in a release — filename, title, date — in one
place. It is human-readable without any platform, survives even if
a platform's metadata degrades, and is the first thing a stranger
opens to understand what a record contains.

Keep the manifest **in the repo** (so it's covered by versioning,
Ch. 03) **and in the deposit** (so the archived snapshot includes
it, Ch. 04). Update it before every release, never after.

## The template

Copy everything below the line into `[project-slug]_MANIFEST_[YYYY-MM-DD].md`
(or simply `MANIFEST.md` inside a per-release folder — pick one and
stay consistent).

---

```md
# MANIFEST — [PROJECT NAME] ([YEAR OR SCOPE])

[One sentence: what this release contains.]

| # | Filename | Title | Date posted | Notes |
|---|----------|-------|-------------|-------|
| 1 | [project-slug]_[YYYY-MM-DD]_[title-slug].[ext] | [Title] | [YYYY-MM-DD] | |
| 2 | [project-slug]_[YYYY-MM-DD]_[title-slug].[ext] | [Title] | [YYYY-MM-DD] | |
| 3 | [project-slug]_[YYYY-MM-DD]_[title-slug].[ext] | [Title] | [YYYY-MM-DD] | |

Total works: [N]

[YOUR NAME] (c) [YEAR]. All rights reserved.
```

## Filled example (fictional)

```md
# MANIFEST — Procedural Landscapes (2024)

Twenty-three procedural paintings posted during 2024, in web
resolution as originally published.

| # | Filename | Title | Date posted | Notes |
|---|----------|-------|-------------|-------|
| 1 | procedural-landscape_2024-01-06_first-light.jpg | First Light | 2024-01-06 | |
| 2 | procedural-landscape_2024-02-19_salt-field.jpg | Salt Field | 2024-02-19 | |
| 3 | procedural-landscape_2024-03-17_dune-study-4.jpg | Dune Study 4 | 2024-03-17 | series highlight |

Total works: 23

Sam K. (c) 2024. All rights reserved.
```

## Rules

1. **Filenames in the manifest must match the actual files
   character for character.** The manifest is a contract; a
   mismatch is a broken contract. Verify by script or by eye —
   but verify.
2. **Dates are original publication dates** (same rule as the
   filename convention).
3. **Titles are the works' real titles**, not filenames. If a work
   has no title yet, title it before manifesting — "untitled-14"
   is a title of last resort, not a plan.
4. **The Notes column is for exceptions**, not essays: "series
   highlight," "reworked version of #7," "excluded from deposit
   at the artist's request." If a work was removed from a release,
   say so here rather than silently renumbering.
5. **Never edit a manifest after its release is published.**
   Corrections go in the next version's manifest, with a note.
6. **The date column holds whatever date orders the work**
   (posting, performance, completion) — one meaning per manifest,
   stated in the one-sentence description under the title.

## Checklist

- [ ] Every row's filename matches an actual file, exactly
- [ ] Dates are original publication dates
- [ ] Total count matches the row count
- [ ] Manifest committed to the repo before the release
- [ ] Manifest included in the deposit's files
