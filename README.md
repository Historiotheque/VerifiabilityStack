# The Verifiability Stack

*A reproducible guide for independent artist-researchers: how to build the
credibility infrastructure that institutions normally provide — as one
person, with no institution.*

## Who this is for

You are an artist, a researcher, or both. You are **independent**: no
university, no lab, no department, no research office. Nobody assigns you
an institutional email, nobody archives your work for you, nobody mandates
that you register an identifier or deposit your outputs anywhere.

This guide is for you. It documents, step by step, how to assemble a
**verifiability stack**: a small set of free, public infrastructures that
together make your work identifiable, timestamped, citable, and
findable — the way institutional researchers' work already is.

## Who this is not for

If your university library already runs a repository, wires your DOIs,
and maintains your profile for you, you don't need this guide — though
you may still find it useful to understand what happens on your behalf.

### A note on the running example

The guide's examples follow one fictional artist-researcher — Sam K.,
a painter (every example is labeled **(fictional)**). But every
pattern generalizes across media: a "project" here means any coherent
body of work released together — a painting series, an album, a suite
of field recordings, a run of essays, a software tool. Where you see
a posting date, read whatever date orders the work (performance date,
completion date). The stack doesn't care about medium.

## The problem in one paragraph

Institutions confer credibility through infrastructure, not just
reputation. When a university researcher publishes, a whole apparatus
moves underneath them: persistent identifiers, archives, libraries,
mandates. An independent artist-researcher doing equivalent work gets
none of that — so the work, however good, is harder to find, harder to
cite, harder to date, and easier to dismiss. This guide replaces the
apparatus, piece by piece, with tools anyone can use for free.

## The stack at a glance

| Layer | Tool | The failure it fixes |
|---|---|---|
| Identity | ORCID | "Which person with this name made this work?" |
| Workbench | GitHub (repos + releases) | Work scattered across hard drives and platforms |
| Archive | Zenodo (records + DOIs) | Link rot; no timestamp; nothing citable |
| Series home | Zenodo community | A body of work with no single address |
| Presentation | A venue you choose (criteria in Ch. 01) | Presenting on platforms you don't control |
| Announcement | Social (e.g. Bluesky) | Publishing into the void; nobody knows it's out |
| Discovery | DataCite, OpenAlex, Semantic Scholar, Google Scholar, Zotero, Archive.org, Wayback | The work exists but can't be found |

Each layer is covered in its own chapter. You build them in order.

## How to use this guide

1. **Read `01-why-verifiability.md` first.** It explains what verifiability
   means, what it doesn't do, and what life looks like without it. If the
   argument doesn't convince you, the procedures won't be worth your time.
2. **Work through the chapters in order.** Each one assumes the previous
   layers exist. Chapter 06 is optional — adopt what serves you, skip
   the rest.
3. **Follow the steps literally the first time.** Every procedure was tested
   by doing it. Each file carries a "last tested" date — if yours is much
   newer than that date, interfaces may have changed; proceed carefully and
   consider reporting back.
4. **Placeholders look like `[THIS]`.** Anything in square brackets and
   capitals is something you must replace with your own information.
   Fictional examples are always labeled **(fictional)**.

## Conventions

- **Voice:** second person, plain language. No assumed institutional
  background, no assumed technical background beyond everyday computer use.
- **Dates:** every procedure file ends with a "Last tested" line.
- **Names:** all personal names in examples are fictional placeholders.
- **Reproducibility:** a step that can't be followed exactly as written is
  a bug in this guide. The guide itself is held to the standard it teaches.

## License

**Recommendation: CC BY 4.0** for the guide text, so others can reuse, translate, and remix it. (A reproducibility guide that can't be reproduced would be a poor joke.) Your artworks and research outputs themselves can carry whatever license you choose; the guide is a separate object.

## Contents

- `01-why-verifiability.md` — the argument: what verifiability is, why
  independents need it, what life is like without it.
- `02-identity-orcid.md` — registering and using an ORCID iD.
- `03-code-github.md` — repositories, releases, licensing.
- `04-archive-zenodo.md` — records, DOIs, communities, versioning.
- `05-announce.md` — announcing a release: threads, alt text, hashtags,
  copyright.
- `06-going-further.md` — DataCite, OpenAlex, Semantic Scholar, Zotero,
  Archive.org, Wayback/perma.cc, Google Scholar.
- `07-maintenance.md` — the ongoing rhythm once the stack exists.

## A note on presentation

This guide is venue-neutral about *where* you present your work to an
audience. Archiving (preservation, citability) and presenting
(audience, discourse) are different problems: the stack solves the
first completely and treats the second as a decision you make with
open eyes. Chapter 01 covers the risks of presentation platforms and
the criteria for choosing one. No chapter prescribes a specific venue.
- `templates/` — filename conventions, manifest template, paste-kit pattern.
