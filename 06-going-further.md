# 06 — Going further

*Last tested: general knowledge — verify each service's current
interface before relying on exact click-paths.*

## What this chapter gives you

Chapters 01–05 are the stack, and the stack is complete: identity,
workbench, archive, announcement. Everything in *this* chapter is
optional — possibilities, not requirements. The seven services below
can help greatly with discovery and robustness, but none is
necessary to the stack, and other platforms beyond the ones named
here may serve as well or better. Treat this chapter as a menu, not
a curriculum: adopt what serves you, skip the rest deliberately.
A deliberate skip is a completed decision.

## 1. DataCite Commons: verify your DOI

DataCite is the registry that issues Zenodo DOIs. Its public portal,
DataCite Commons, is where the world sees your record's metadata.

1. Go to **commons.datacite.org** and search your DOI:
   `[YOUR DOI]`.
2. Check: title correct, creators correct (with ORCID linked),
   license as intended, publication year right.
3. If anything is wrong, fix it at the source — the Zenodo
   record's metadata (§Ch. 04 §5 covers metadata edits).

Do this once per record, right after publishing. It's your quality
control: this is what machines read when they cite you.

## 2. OpenAlex: check you're indexed

OpenAlex is a free, open index of scholarly works — the open
alternative to proprietary citation databases.

1. Go to **openalex.org** and search your name or ORCID iD.
2. Confirm your Zenodo records appear as works attributed to you.
3. Explore the **topic graph** around your works: it shows what
   the index considers your work related to — useful for finding
   the vocabulary your field actually uses, which feeds back into
   your keywords (Ch. 04) and hashtags (Ch. 05).

If a record is missing, it usually appears within days to weeks as
indexes harvest DataCite. Patience first, troubleshooting second.

## 3. Semantic Scholar: watch your field

Semantic Scholar (semanticscholar.org) indexes research literature
and lets you set **alerts**: email notifications when new papers
match your interests.

1. Create a free account.
2. Set alerts for your research areas — the plain-language terms
   from your keyword vocabulary.
3. Set an alert for your own name, so you learn when your work is
   discussed or cited.

This is how you find out the conversation exists, instead of
hoping it finds you.

## 4. Zotero: your working reference library

Zotero (zotero.org) is a free reference manager — your personal
card catalog for everything you read and everything you publish.

1. Install Zotero and create a free account (for syncing).
2. Add your own records with **Add by identifier**: paste the DOI
   (the "magic wand" tool) and Zotero pulls the full metadata.
3. Organize with collections and tags — your controlled
   vocabulary works here too.
4. Use it for everything you read, not just your own work: the
   library you build becomes the bibliography of your future
   writing, already formatted.

Your own DOIs belong in your own library. Catalog yourself the way
you'd catalog anyone worth citing.

## 5. Internet Archive: the heavy-media collection

The Internet Archive (archive.org) is a second, independent home
for your work — particularly media too heavy or awkward for the
rest of the stack. Its item pages render images, audio, and video
directly in the browser, so it doubles as a presentation venue
(see Ch. 01 §7 — evaluate it against the criteria there).

1. Create a free account at **archive.org**.
2. Create a **collection** for your practice:
   `[YOUR COLLECTION NAME]`, with a description.
3. Upload in batches: choose an **identifier** per item
   (short, stable, lowercase-with-hyphens — it becomes the URL),
   add title, description, date, and **license** (this is where
   the rights question from Ch. 03 §4 must already be answered —
   know what each batch contains and whose rights it carries
   before uploading).
4. Check the item page: metadata correct, media renders, license
   displayed.

Two archives in two organizations is not paranoia; it's the
beginning of a preservation strategy.

## 6. Wayback Machine: save everything, twice

The Wayback Machine (web.archive.org) keeps timestamped snapshots
of web pages — including your own record pages.

1. After every publish, run each canonical URL (Zenodo record,
   announcement post, profile pages) through **"Save Page Now."**
2. Do the same for every external URL you cite in your own
   writing — link rot (Ch. 01 §2) applies to other people's pages
   too.
3. Make it a habit, not a project: thirty seconds per URL, at
   publish time.

(Perma.cc offers permanent citation archiving along similar lines,
but its free tier is limited and primarily institutional — verify
current terms before depending on it. The Wayback Machine is the
default.)

## 7. Google Scholar profile: be findable where people look

Many people search for researchers on Google Scholar first. Give
them something to find.

1. Go to **scholar.google.com**, sign in, and choose **My profile**.
2. Verify with an email address you control.
3. Add your works — search by title or DOI; claim what's yours.
4. Set the profile to **public**.
5. Link your ORCID and homepage in the profile.

Check it yearly: Scholar sometimes misattributes works, and a
stray misattribution on your public profile is your problem to
fix.

## Pitfalls

- **Treating this chapter as urgent.** It's not — it's the ring
  *around* the core. Build Chapters 01–05 first; add these as the
  need arises.
- **Duplicate Scholar profiles.** One profile, one email, one
  identity — same discipline as ORCID (Ch. 02).
- **Archive.org uploads with undecided rights.** The license field
  is not the place to figure out rights; figure them out first
  (Ch. 03 §4).
- **Assuming harvest is instant.** OpenAlex, Scholar, and Semantic
  Scholar index on their own schedules. Verify after a few weeks,
  not a few hours.

## Checklist

Check off what you adopt; leave the rest — a deliberate skip is a
completed decision.

- [ ] DOI verified in DataCite Commons (per record)
- [ ] Works appearing under your name/ORCID in OpenAlex
- [ ] Semantic Scholar alerts set (field terms + own name)
- [ ] Own DOIs cataloged in Zotero via Add by identifier
- [ ] Archive.org collection created; first batch uploaded with
  correct rights metadata
- [ ] Canonical URLs saved to the Wayback Machine (per publish)
- [ ] Google Scholar profile public, works claimed, ORCID linked
