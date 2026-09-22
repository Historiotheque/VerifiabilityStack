# 01 — Why verifiability

*Last tested: n/a (conceptual chapter — no procedures).*

## 1. The situation of the independent artist-researcher

Consider two people doing equivalent work. One is a postdoctoral
researcher at a university. The other is independent — no affiliation,
no department, no research office.

The postdoc's work moves through infrastructure they never had to
build: their university gives them an identity in its systems, a
repository that archives their outputs, a library that mints DOIs, a
funder that mandates open deposit, a profile page that aggregates it
all. When they publish, the apparatus publishes with them.

The independent artist-researcher gets none of this. Not because their
work is lesser — it may be better — but because **credibility in
research is largely a function of infrastructure**, and the
infrastructure was built for institutions.

This is the gap the Verifiability Stack closes. Not by imitating
prestige, but by assembling the same underlying machinery from free,
public parts.

## 2. Life without the stack

Without verifiability infrastructure, the same failures recur. They
are boring, technical, and devastating in combination.

**Link rot.** You post a series of works on a platform in 2019 and cite
the URLs in a text. By 2026 the platform has redesigned, throttled, or
shut down; half the links are dead. There is no canonical address for
the work — only whatever URL happened to work that day.

**Identity ambiguity.** Your name is not unique. Search engines mix
your work with three other people sharing your name, one of whom is
also an artist. There is no machine-readable statement anywhere that
says *this* work belongs to *this* person.

**No trustworthy timestamp.** You need to show a work existed by a
certain date — for priority, for a grant application, for your own
records. All you have is a social media post with a platform-assigned
date, on a platform that could delete it tomorrow.

**Platform dependence.** Your entire public record lives on two or
three commercial platforms — Facebook, Instagram, and their kin —
whose algorithms decide who sees your work, whose terms of service
can change under you, whose accounts can be restricted or banned
without appeal, and which can shut down or pivot away from your
medium entirely. Formats are constrained to what the platform
allows; exporting your own archive is difficult or impossible; and
"reach" can collapse overnight for reasons nobody will explain to
you. You are a tenant, not an owner — and the landlord is not in the
preservation business.

**Nothing citable.** A peer wants to reference your series in their
own research. There is no identifier to cite, no stable record, no
suggested citation format. So they describe it vaguely, or they don't
cite it at all — and uncited work is invisible work.

**The credibility question.** A curator, an editor, or a grant
committee asks, politely: "Where is this published?" You have no good
answer. Not because the work isn't serious, but because seriousness
has no address.

> **Example (fictional).** *Sam K. is an independent painter-researcher
> who has produced a ten-year series of procedural works, documented
> only on social media. When a journal invites Sam to submit, the
> editor asks for stable references for the works discussed. Sam
> spends three weeks reconstructing dates from old posts — and two of
> the posts are gone, deleted in a platform purge. The submission is
> delayed a year.*

None of these failures is about quality. All of them are about
addressability.

## 3. What "verifiability" actually means

Verifiability is not prestige, reputation, or peer approval. It is a
narrower, more mechanical claim: **a stranger can confirm, without
trusting you, that a work exists, is yours, dates from when you say,
and can be found again tomorrow.**

Four guarantees, each supplied by one layer of the stack:

1. **Identity** — a persistent identifier for the *person* (ORCID),
   so works attach to exactly one human being and not to a name
   collision.
2. **Persistence** — a persistent identifier for the *work* (DOI),
   so the address doesn't rot when platforms redesign or die.
3. **Timestamp and version** — an archive that records *when* a
   deposit was made and keeps every version (Zenodo), so priority
   and provenance are checkable.
4. **Citability** — open metadata (title, creator, date, license)
   in standard formats, so other people — and machines — can
   reference the work properly.

Two definitions, in plain language:

- **DOI (Digital Object Identifier):** a permanent address for a
  digital object. Unlike a URL, it is managed by a registry
  (DataCite/Crossref) and keeps resolving even if the underlying
  files move.
- **ORCID iD:** a permanent identifier for a researcher — a number,
  like `0000-0000-0000-0000` (placeholder), that disambiguates you
  from everyone sharing your name, for life, across institutions
  (or the absence of them).

## 4. What verifiability doesn't do

Honesty requires the limits, stated plainly:

- It does not make the work good. Metadata never substitutes for
  engagement with the work itself.
- It does not create an audience. A DOI is an address, not an
  invitation.
- It does not confer peer review, prestige, or institutional
  approval. Those are separate systems with their own gatekeepers.
- It does not protect against all platform risk — it *reduces* it
  by keeping a canonical copy outside commercial platforms.

The stack is the foundation, not the house. But without a
foundation, the house sinks — quietly, over years, through link rot
and obscurity.

## 5. Why artists and artist-researchers especially

Researchers in the sciences already live inside this apparatus; their
institutions built it around them. Artists have historically lived
outside it — the art world runs on galleries, reputation, and
physical objects, none of which need DOIs.

The **artist-researcher** sits in the gap: producing work that is
simultaneously art and research, in a world — peer-reviewed journals
of artistic research, practice-based PhD programs, online venues
built for the form — that increasingly expects research-grade
documentation of artistic practice. For this person, verifiability
infrastructure isn't a bureaucratic extra. It's the condition under
which the work can circulate *as research*.

And for the independent among them, there is no one else who will
build it.

## 6. How the stack answers each failure

| Without the stack | With the stack |
|---|---|
| Links rot | DOI resolves permanently |
| Name collisions | ORCID identifies exactly one person |
| "When was this made?" | Archive timestamps every deposit and version |
| Tenant on platforms | Canonical copy in an open archive |
| Nothing to cite | Standard metadata, suggested citation |
| "Where is this published?" | A record with a DOI, in a named collection |
| Presenting on rented land | The archive is yours; presentation is a separate, deliberate choice (see §7) |

## 7. Presentation is a separate problem

Archiving and presenting are different jobs. An archive guarantees
the work survives, is identifiable, and can be cited. Presentation —
putting the work before an audience, in a form that invites
engagement and discourse — is a different decision, with its own
risks, and this guide deliberately leaves it open.

The risks overlap with platform dependence (§2), but they deserve
their own attention, because the temptation is to treat a platform
as an archive:

- **The platform is not the record.** A social media profile is a
  broadcast channel, not a canonical address. If it vanished
  tomorrow, what would remain?
- **Visibility is rented.** Algorithmic feeds decide who sees what;
  "reach" is granted and withdrawn opaquely.
- **Formats are dictated.** Aspect ratios, durations, compression,
  text limits — the platform's constraints become your work's
  constraints, unless you keep a canonical version elsewhere (which
  the stack gives you).
- **Terms change.** Content policies, monetization rules, API
  access, account standing — all mutable without your consent.
- **Exit is hard.** Export tools are partial or absent; follower
  graphs and comment histories usually can't leave with you.

None of this means "don't use platforms." It means: choose them as
*presentation venues*, deliberately, while the archive holds the
canonical record. Criteria worth applying to any venue, commercial
or community-run:

1. Can you keep a canonical, full-quality copy outside it?
2. Can you leave — exporting your work and your audience data?
3. Does it support (or at least not contradict) your license?
4. Does it serve the audience you actually want — peers, public,
   both?
5. If it disappeared in a year, what would you lose?

Venues built specifically for practice-based research exist, as do
general open archives whose item pages render media directly —
evaluate candidates against the criteria above; the guide prescribes
none. The choice is yours. The stack's job is to make sure the
choice is never load-bearing for the survival of the work.

## 8. What changes once it's built

The building is front-loaded: registering, configuring, and wiring
the layers takes real effort — days, not minutes. That effort is the
price this guide asks you to pay once.

After that, the rhythm changes completely. Publishing a new series
becomes: make a release, let the archive mint the DOI, add it to your
profile, announce it. Minutes per release, not days. The stack fades
into the background and becomes what infrastructure is supposed to
be: invisible, until the day you need it — the grant application,
the priority dispute, the citation, the hard drive failure — and then
it is simply there.

That is the whole argument. The rest of this guide is procedure.
