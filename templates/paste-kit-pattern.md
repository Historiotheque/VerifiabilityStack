# Template: paste-kit pattern

A paste-kit is a single file holding **every block of text you will
paste into a deposit form, in form order** — written once, carefully,
before you ever open the form. It eliminates retyping, keeps
wording consistent across records, and turns a fiddly web form into
a calm copy-paste exercise.

Write the kit. Read it once fully. Correct anything wrong. *Then*
open the form.

## The pattern

One section per form field, in the order the form presents them.
Each section: the field name as a header, then the exact block.
A trailing reference section — clearly marked DO NOT PASTE — holds
notes to yourself (reminders, per-field quirks, the keyword list in
full).

```md
# PASTE KIT — [DEPOSIT TITLE]

--- [FIELD 1: e.g. TITLE] ---
[exact text]

--- [FIELD 2: e.g. DESCRIPTION] ---
[exact text]

Keywords: [term]; [term]; [term]

--- [FIELD 3: e.g. CREATORS] ---
Name: [YOUR NAME]
ORCID: https://orcid.org/[YOUR ORCID ID]

--- [FIELD 4: e.g. LICENSE / RIGHTS] ---
[exact license text]

---------- do not paste below this line ----------
[Reminders: form quirks, e.g. "remove the pre-populated license
first", "keywords have no dedicated field — the Keywords: line
above is the whole mechanism", full keyword list for reference.]
```

## Filled example (fictional, Zenodo-style form)

```md
# PASTE KIT — Procedural Landscapes (2024)

--- TITLE ---
Procedural Landscapes (2024)

--- DESCRIPTION ---
Procedural Landscapes are abstract digital paintings by Sam K.,
made through procedural generation and texture synthesis.

This record gathers the works posted during 2024, in web resolution
as originally published. The manifest (MANIFEST.md) lists each
work's title and original posting date.

Sam K. (c) 2024. All Rights Reserved.

Keywords: procedural landscapes; digital painting; texture synthesis;
abstract art; generative art

--- CREATORS ---
Name: Sam K.
ORCID: https://orcid.org/0000-0000-0000-0000

--- LICENSE ---
Custom — Title: All Rights Reserved
Custom — Description: © Sam K. 2024. All rights reserved.

---------- do not paste below this line ----------
- Remove the form's pre-populated CC license BEFORE adding the custom one.
- No dedicated keywords field: the Keywords: line at the end of the
  Description is the whole mechanism.
- Record access: Public.
- Attach the community before submitting; the button will read
  "Submit for review", not "Publish".
```

## Rules

1. **Adapt the field list to the form you're filling.** The pattern
   is universal; the fields aren't. Open the form once, read-only,
   note every field in order, close it, then write the kit.
2. **The kit is written in your voice, for strangers.** The
   description block is what search engines and future researchers
   read — write it once, well, and reuse it across records with
   only the year/scope changed.
3. **Keep the finished kit in the repo** next to the manifest.
   Next year's deposit starts from this file, not from a blank
   form.
4. **One kit per deposit.** Don't maintain a mega-kit for all
   deposits; small, per-release kits stay accurate.

## Checklist

- [ ] Every form field has a section, in form order
- [ ] Kit read fully and corrected before the form is opened
- [ ] Keywords line present (adapted to the form's mechanism)
- [ ] License block matches the repo's LICENSE (Ch. 03 §4)
- [ ] Finished kit committed to the repo for next time
