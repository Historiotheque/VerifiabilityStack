# 05 — Announce

*Last tested: 2026-09-21 (announcement pattern; threaded shape tested
on a 300-character/post platform).*

## What this chapter gives you

The **announcement pattern**: how to tell the world a release exists
so the DOI actually gets used. Ch. 04 put it bluntly — a DOI nobody
links to is a tree falling unheard. Announcement is the other half
of publishing.

## 0. The rule

**One announcement per release, not per work.** You announce the
record — the dated, citable collection — not each file inside it.
This keeps your public presence proportional to your archival
activity and keeps you far from anything resembling spam.

## 1. What an announcement contains

Every announcement, on any platform, carries the same six elements:

1. **What it is** — the project and its scope, in one sentence:
   `[PROJECT NAME] ([YEAR]): [one-line description].`
2. **What changed** — if it's a new version: what's new since the
   last one. If it's the first release: say so.
3. **The DOI link** — the full `https://doi.org/[YOUR DOI]`. This
   is the only link that matters; it is the citable address.
4. **The work itself, attached** — for visual work, attach 2–4
   images directly to the post. Do not rely on link previews: an
   archive record page is built for machines and librarians, not
   for looking at art. People see the work in the feed; the link
   underneath is the record.
5. **Hashtags** — your controlled vocabulary (§4).
6. **Copyright line** — `© [YOUR NAME] [YEAR]. All rights
   reserved.` (or your actual terms). Cheap, unambiguous, always
   include it.

## 2. Three shapes, one announcement

The six elements (§1) are the requirement; how you arrange them
depends on the platform. Three shapes cover nearly everything:

**A. The single post.** If the platform has no meaningful length
limit — a blog, a news page, a newsletter — publish one
announcement containing all six elements. Simplest, and always an
option: when in doubt, write the single post first. It's the
canonical text the other shapes adapt.

**B. The thread.** If the platform constrains length *and* lets you
reply to your own post: post 1 carries the news and the images;
post 2, as a self-reply, carries the details (what's new, the
copyright line, extra tags).

**C. The numbered series.** If the platform constrains length but
has no self-reply threading: publish numbered posts — (1/2),
(2/2) — each self-contained enough to make sense alone, each
carrying the DOI link.

> **Worked example — shape B (fictional).** *Sam K. publishes
> "Procedural Landscapes (2024)" on a 300-character-per-post
> platform:*
>
> *Post 1 (images attached):*
> `Procedural Landscapes are now on Zenodo with a DOI — 23 procedural
> paintings from 2024, archived with full titles and dates.`
> `https://doi.org/10.5281/zenodo.0000000`
> `#proceduralart #digitalpainting`
>
> *Post 2 (reply to post 1):*
> `Earlier years will follow as new versions of the same record.`
> `© Sam K. 2024. All rights reserved.`

Check character counts before posting — write the text in a file
first, count, then paste.

## 3. Alt text: describe every image you attach

Alt text is what screen readers read aloud and what search engines
index. Write it for every attached image, in this exact format:

`{Title} — {medium or short description} by {name}, {year}.`

Rules:

- **No quotation marks** around the title — some screen readers
  announce them aloud.
- Keep it one line, plain text, factual.
- Use the work's real title, not a filename.

> **Example (fictional).**
> `Dune Study 4 — procedural digital painting (noise field) by Sam K., 2024.`

## 4. Hashtags as controlled vocabulary

Don't improvise hashtags per post. Maintain a **controlled
vocabulary**: a fixed list of tags you define once and reuse
forever. Two tiers:

- **Custom tags** (your interior): tags only you use, e.g.
  `#[yourproject]`, `#[yourtheory]`. Search any of them and the
  results should be almost exclusively your work — a breadcrumb
  trail across platforms.
- **Standard tags** (the on-ramps): ordinary tags like
  `#digitalpainting` that outsiders actually search.

Keep the definitions in one glossary file. When you invent a new
tag, define it there first, then use it. Never the reverse.

On platforms with no hashtag mechanism, apply the same discipline
to whatever tagging or keyword field exists; where none exists,
skip this element — the other five carry the announcement.

## 5. Timing

- Announce **after the DOI resolves** — open the
  `https://doi.org/...` link yourself and confirm it lands on the
  record before you post. A dead DOI in an announcement is
  embarrassing and avoidable.
- Announce once per release. If a platform's algorithm buries it,
  that's the platform's problem (Ch. 01 §7) — the record doesn't
  need the algorithm.

## Pitfalls

- **Link-only posts.** Nobody clicks through to an archive record
  cold. Attach the work.
- **Missing alt text.** Inaccessible and unindexed — a third of
  the announcement's value, discarded.
- **Hashtag stuffing.** Ten tags looks desperate and breaks the
  controlled-vocabulary discipline. Three to five, from your
  glossary.
- **Announcing drafts.** Only published, DOI-minted records. If
  the record isn't live, the announcement is fiction.
- **A different message per platform.** Keep one canonical text;
  adapt mechanically. Your future self, reconstructing history,
  will thank you.

## Checklist

- [ ] DOI resolves (opened it yourself)
- [ ] Announcement text written in a file, character-counted
- [ ] 2–4 images attached (visual work)
- [ ] Alt text on every image, in the `{Title} — ...` format
- [ ] Hashtags from your glossary only (3–5)
- [ ] Copyright line included
- [ ] Published in the shape the platform supports (single post,
  thread, or numbered series)
