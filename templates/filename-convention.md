# Template: filename convention

Copy this pattern for every file you publish. Filenames are metadata:
chosen well, they sort chronologically, survive every operating
system, and stay unambiguous for decades.

## The pattern

```
[project-slug]_[YYYY-MM-DD]_[title-slug].[ext]
```

- **All lowercase.** Uppercase/lowercase mismatches cause real bugs
  on case-sensitive systems. Lowercase everywhere, no exceptions.
- **ISO date (`YYYY-MM-DD`).** Sorts chronologically as plain text.
  Never use ambiguous formats like `17Jan26` — is that January 2017
  or 2026?
- **Hyphens inside slugs, underscores between fields.** The
  underscores are the separators; the hyphens join words. This
  makes the filename machine-splittable: split on `_` and you get
  exactly three fields.
- **Title slug** derived from the work's title: lowercase, spaces
  and punctuation become hyphens, e.g. "Dune Study 4" →
  `dune-study-4`.
- **No spaces, no accented characters, no special characters.**
  If it isn't `a-z`, `0-9`, `-`, `_`, or `.`, it doesn't belong
  in a filename.

## Example (fictional)

Sam K.'s series "Procedural Landscapes," work titled "Dune Study 4,"
posted 2024-03-17:

```
procedural-landscape_2024-03-17_dune-study-4.jpg
```

Before/after, illustrative:

```
BEFORE:  DUNE_STUDY_17Mar24.jpg
AFTER:   procedural-landscape_2024-03-17_dune-study-4.jpg
```

## What counts as a project

The first field names the coherent body of work the file belongs
to — a painting series, an album, a run of essays, a software
release, a season of field recordings. If it gets released,
deposited, or announced as a unit, it's a project. Likewise, the
date field is whatever date orders the work — posting date,
performance date, completion date. Pick one meaning per project,
document it in the repo README, and never mix meanings within one
project.

## Rules

1. Decide the `[project-slug]` once, when the project starts. Never
   rename it mid-project — renames break every link and manifest
   that references the old names.
2. The date is the **original publication/posting date**, not the
   date you renamed or deposited the file. History is written once.
3. Apply the convention *before* the first release (Ch. 03 §5) and
   *before* the first deposit (Ch. 04) — renames after archiving
   create two names for one work.
4. Keep a one-line note of the convention in each repo's README
   (Ch. 03 §3), so future-you — or anyone else — can extend it
   consistently.

## Checklist

- [ ] Series slug fixed and documented
- [ ] All filenames lowercase, ISO dates, no spaces
- [ ] Dates are original publication dates
- [ ] Convention applied before first release and first deposit
