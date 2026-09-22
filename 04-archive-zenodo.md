# 04 — Archive: Zenodo

*Last tested: 2026-09-21 (manual deposit via "New upload," current form;
GitHub integration flow as documented).*

## What this chapter gives you

The **archive layer**: frozen, timestamped, citable records of your
work, each carrying a DOI. This is the layer that answers Ch. 01's
failures directly — link rot, untrustworthy dates, nothing to cite.
GitHub (Ch. 03) is where the work lives and changes; Zenodo is where
a version of it is frozen forever and given a permanent address.

## 0. What Zenodo is (thirty seconds)

Zenodo (zenodo.org) is a free, open research archive run by CERN. You
deposit files with descriptive metadata; Zenodo stores them
permanently, timestamps the deposit, versions it, and mints a **DOI**
for it via DataCite. Anyone — including you in ten years — can cite
that DOI and land on exactly the files you deposited. No institution
required, no fees, no catch.

## 1. Two ways to deposit

- **Path A — GitHub integration** (§2). For anything that already
  lives in a GitHub repo: flip one switch, and every GitHub release
  is automatically archived with its own DOI. Recommended default.
- **Path B — Manual upload** (§3). For anything not in GitHub, or
  when you want full control of the record: upload files directly
  through the "New upload" form.

Both produce the same kind of record. Choose per deposit.

## 2. Path A: GitHub integration, step by step

1. Log in to **zenodo.org** using your GitHub account.
2. Find the GitHub section of your Zenodo settings. You'll see your
   repos (and your organization's repos) listed with a toggle next
   to each.
3. **Toggle on** the repo you want archived: `[YOUR-ORG]/[YOUR-REPO]`.
4. Make a release on GitHub, exactly as in Ch. 03 §5.
5. Zenodo notices the release, archives a snapshot of the repo, and
   mints a DOI. Open the new record and check it: title, files,
   metadata.
6. Note the **two DOIs** Zenodo gives you: a *version DOI* (this
   exact snapshot — cite this for reproducibility) and a *concept
   DOI* (always resolves to the latest version — cite this when you
   mean "the series as a whole").

From here on, the rhythm is: release on GitHub → record appears on
Zenodo. Minutes, not hours.

## 3. Path B: Manual upload, step by step

1. On zenodo.org, choose **New upload** and add your files —
   `[YOUR FILES]`, already named under your filename convention.
2. **Title:** `[SERIES NAME] ([YEAR OR SCOPE])`. Put the year or
   scope in the title itself (see §5 on why): e.g.
   `[SERIES NAME] (2024)` (placeholder).
3. **Resource type:** choose the closest match (e.g. *Image* →
   *Other* for digital paintings that fit no preset).
4. **Description:** what the work is, how it was made, what the
   record contains. Write it once, carefully — this text is what
   strangers and search engines will read.
5. **Creators:** `[YOUR NAME]`, with your ORCID iD attached
   (`https://orcid.org/[YOUR ORCID ID]`).
6. **Copyright statement:** `[YOUR NAME] (c) [YEAR]. All Rights
   Reserved.` (or your chosen terms — must match the LICENSE in
   the repo, Ch. 03 §4).
7. **Record access:** set to **Public**. (Note: the form no longer
   has the old "Access right" dropdown — record-level access is
   the control now.)
8. **License:** check what the form pre-populates. If it shows a
   Creative Commons license you did not choose, **remove it** and
   use **Add custom**: Title `All Rights Reserved`, description
   `© [YOUR NAME] [YEAR]. All rights reserved.` (or your actual
   terms — if you work under a moniker, use
   `© [MONIKER] ([LEGAL NAME]) [YEAR]`, per Ch. 03 §4). Never
   leave a license you didn't intend.
9. **Keywords:** the form has no dedicated keywords field. Append a
   single line at the very end of the Description:
   `Keywords: [term]; [term]; [term]`.
10. **Community:** if you maintain one (§4), attach it here.
11. Publish — or, if a community is attached, **Submit for review**
    (see §4), then accept it.

> **Example (fictional).** *Sam K. deposits 23 works from 2024 as
> "Procedural Landscapes (2024)": uploads the JPGs, pastes a
> three-paragraph description, sets the custom All Rights Reserved
> license, appends the Keywords line, attaches the community, and
> submits for review.*

## 4. Communities: giving a body of work one address

A **community** is a named collection on Zenodo — a single page that
gathers all your records on a theme, series, or practice. It solves
the "where is the whole body of work?" problem, especially once you
adopt the yearly-record doctrine of §5.

1. Create a community: name it `[YOUR COMMUNITY NAME]`, write a
   description of what it collects and the standards for inclusion.
2. Attach it to each deposit at upload time (§3, step 10).
3. **The submit-for-review flow:** when a community is attached,
   the form has no "Publish" button — instead it says **Submit for
   review**. After submitting, go to the community's page, find
   your submission, and **accept it yourself** as the community
   owner/curator. This two-step is normal, not an error.

One community per practice (or per major branch of it) is plenty.
The community plus a consistent title pattern (`[SERIES] ([YEAR])`)
plus shared keywords is what keeps a multi-year series unified
across separate records.

## 5. Versioning doctrine: one record per coherent period

Do not put an entire multi-year series in a single record. Zenodo
caps records at **100 files** — a series spanning years of output
will hit that ceiling, and a 100-file record is unnavigable anyway.

The doctrine this guide recommends:

- **One record per year** (or per coherent production period).
  Title each `[SERIES NAME] ([YEAR])`.
- **New years become new versions** of the record (Path A) or new
  records in the same community (Path B) — either way, the
  community page holds the series together.
- **Sparse years merge.** Three works from 2021 and two from 2022
  don't each need a record; one record covering 2021–2022 does.
- **Overflowing years:** if one year genuinely exceeds ~100 files,
  **email support@zenodo.org first** and request a quota increase —
  this is a normal, granted request. Splitting a year into
  half-year records is the backup plan, not the default.
- **Metadata-only fixes** (correcting a title, adding a keyword)
  don't need a new version — edit the record's metadata directly.

## 6. After the DOI is minted

A DOI nobody links to is a tree falling unheard. Close the loop:

1. **ORCID:** add the DOI to your record (Ch. 02 §3) — one minute,
   by hand.
2. **GitHub:** fill in the citation placeholder in the repo README
   (Ch. 03 §3) with the version DOI.
3. **Wayback Machine:** run the record URL through "Save Page Now"
   so an independent copy of the landing page exists outside
   Zenodo too. (Full workflow in Ch. 06.)
4. Announce it (Ch. 05).

## Pitfalls

- **Leaving the pre-populated CC license in place.** The form
  assumes Creative Commons; if that's not your intent, remove it
  and add your custom license. An unintended open license on
  all-rights-reserved work is painful to unwind.
- **Keywords anywhere but the Description's last line.** There is
  no keywords field; the appended `Keywords:` line is the whole
  mechanism. Don't skip it — it's what makes the record findable.
- **"Where's the Publish button?"** — you attached a community.
  Submit for review, then accept it on the community page (§4).
- **Editing published files instead of versioning.** A published
  record is frozen; that's the point. Changes go in a new version.
- **One giant record for everything.** The 100-file cap and
  simple navigability both argue for yearly records (§5).

## Checklist

- [ ] Deposit path chosen (GitHub integration or manual upload)
- [ ] Title carries the year/scope: `[SERIES] ([YEAR])`
- [ ] Description written for strangers and search engines
- [ ] License verified — pre-populated CC removed if unintended
- [ ] `Keywords:` line appended to the Description
- [ ] Community attached; submission accepted
- [ ] Version DOI noted; concept DOI noted
- [ ] DOI added to ORCID; citation line filled in on GitHub
- [ ] Record URL saved to the Wayback Machine
