# 03 — Workbench: GitHub

*Last tested: 2026-09-21 (repository setup and release flow).*

## What this chapter gives you

A **workbench**: a versioned, public home for your work, where every
state of a project is recorded and where *releases* — frozen,
named snapshots — become the trigger for archiving in Ch. 04.
The division of labor is simple: **GitHub is where the work lives
and changes; Zenodo is where it gets frozen, timestamped, and
cited.** This chapter builds the first half.

## 0. What GitHub is (thirty seconds)

GitHub hosts **repositories** ("repos"): folders with a memory. Every
change to every file is recorded, timestamped, and reversible. Repos
can hold anything digital — code, images, texts, manifests — and
public repos are free. For the stack, "public" is not optional: a
workbench nobody can see can't support verifiability.

## 1. Create an account

1. Go to **github.com** and sign up with `[YOUR EMAIL]` — the same
   permanent, institution-independent address from Ch. 02.
2. Choose a username: `[YOUR USERNAME]`. This becomes part of every
   URL you will ever publish (`github.com/[YOUR USERNAME]/...`),
   so choose it the way you'd choose a domain name: stable,
   professional, and spelled the way you want to be found. Jokes
   age badly in URLs.

## 2. Create a repository

1. Choose **New repository**.
2. Name it `[YOUR-REPO-NAME]`. Pick one naming style and never
   deviate: all-lowercase-with-hyphens (`field-recordings-2026`)
   or PascalCase (`FieldRecordings2026`). Consistency is the whole
   game — your future self will thank you when there are forty of
   these.
3. Set visibility to **Public**. Double-check: the default can vary,
   and a private repo silently breaks everything downstream.
4. Initialize with a **README** (there's a checkbox). You'll fill it
   in next.

> **Example (fictional).** *Sam K., the independent painter-researcher
> from Ch. 01, creates a repo called `procedural-landscapes` for one
> series of works. One repo per series — not one repo for the entire
> practice. Small repos are navigable; giant ones are attics.*

## 3. The README: your repo's front door

Every repo needs a README.md that answers, in order:

1. **What is this?** One paragraph: the series or project, in plain
   language.
2. **What's in here?** A short inventory of the folders and files.
3. **How is it organized?** Your naming conventions, briefly.
4. **License.** What others may and may not do with this work (§4).
5. **How to cite.** Leave a placeholder for now —
   `DOI: [TO BE MINTED IN CH. 04]` — and come back to fill it in
   once the archive issues one. Future readers will use this line;
   make it easy to find.

Write it for a stranger arriving with no context. That stranger is
your most important reader.

## 4. LICENSE: choose before you publish

Decide the license **before the first release** (§5), because the
archive will snapshot whatever is in the repo at release time —
including the LICENSE file. A work with no license file lives in
legal ambiguity (in most jurisdictions "no license stated" defaults
to all rights reserved, but nobody reading the repo can tell).

Plain-language options:

- **All rights reserved.** Write your own `LICENSE.md`: your name,
  the year, and the words "All rights reserved." Simple,
  unambiguous, and the right default for artworks you intend to
  control fully. If you work under a moniker, use the form
  `Copyright (c) [YEAR] [MONIKER] ([LEGAL NAME])` — the public
  identity first, the legal name in parentheses for
  disambiguation. Consistency with the name on the work matters
  more than which name you pick.
- **Creative Commons.** For work you want shared under conditions:
  CC BY (share and adapt, with credit), CC BY-NC (no commercial
  use), and others. Plain-language chooser at
  choosealicense.com — run by GitHub, no account needed.
- **Software licenses** (e.g. MIT) if the repo is primarily code.

There is no universally right answer; there is only the answer that
matches your intent *for this repo*. Different repos in your
practice may carry different licenses — that's normal. Decide per
repo, state it in the LICENSE file, and mention it in the README.

## 5. Releases: freezing a version

A **release** is a named snapshot of the repo at a moment in time:
"this is v1.0, the 2026 series as published." Releases are what Ch.
04 archives — no release, nothing to mint a DOI for.

1. In the repo, go to **Releases** and choose **Draft a new
   release**.
2. Create a tag: `v1.0.0` (or `v1.0` — pick a scheme; *semantic
   versioning*, MAJOR.MINOR.PATCH, is the common one: bump MINOR
   for new works added, MAJOR for restructured collections).
3. Title the release in words: `[PROJECT NAME] v1.0 — [YEAR OR
   SCOPE]`.
4. Write release notes: what this snapshot contains, what changed
   since the last one, what it doesn't contain. A reader should be
   able to understand the version without opening the files.
5. **Publish release.** The snapshot is now frozen and addressable.

## 6. Organizations (optional, recommended as you grow)

An **organization** is a shared home for multiple repos — useful
when one account starts holding dozens of them (one per project,
per year). Think of it as the practice's umbrella:
`github.com/[YOUR ORG]/[YOUR-REPO]`.

1. Create the organization from your account settings; name it
   `[YOUR ORG NAME]` with the same care as a username.
2. Give it a profile README describing the practice it houses.
3. Create new repos *inside* the organization from then on.

This is optional — a single account works fine to start — but if
you plan to build the full stack, set the org up early. Moving
repos later breaks URLs, and the stack is allergic to broken URLs.

## 7. Keep it maintained, lightly

- Write commit messages in plain language ("add three March
  works, fix manifest typo"). The history is a lab notebook;
  future-you is its reader.
- Update the README when the repo's contents change meaningfully.
- Never rewrite a published release's contents. If something must
  change, make a new release (v1.1) — Ch. 04 explains why
  immutability matters.

## Pitfalls

- **Private by accident.** The single most common setup error. If
  anything downstream fails mysteriously, check visibility first.
- **No LICENSE before the first release.** The archived snapshot
  then carries no rights statement — exactly the ambiguity §4
  exists to prevent.
- **A username you'll regret.** It's on every URL, every citation,
  every profile. Boring and durable beats clever.
- **Giant files.** GitHub warns past ~50 MB per file and refuses
  past ~100 MB. Keep web-resolution copies in the repo; archive
  full-resolution masters where they belong (Ch. 04/06).
- **Editing a published release.** The archive may already hold a
  snapshot of it — now two "v1.0"s disagree. Always version
  forward.

## Checklist

- [ ] Account created with a permanent email; durable username chosen
- [ ] Repo created, Public, initialized with README
- [ ] README answers: what, what's inside, organization, license, citation
- [ ] LICENSE.md committed *before* the first release
- [ ] First release published with a version tag and real release notes
- [ ] (Optional) Organization created; new repos live inside it
