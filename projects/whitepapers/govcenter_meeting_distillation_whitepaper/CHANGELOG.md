# Changelog

## 0.2.0 - 2026-11-11 (draft for review)

- Retitled "Shared Context from Public Meetings", with the subtitle "Distilling Public Meetings into Typed and Linked Data".
- Version and status move from the subtitle to the running page header.
- Byline is now "Ryan Wold · ryan@civic.studio"; the "GovCenter, a Civic Studio research project" line is removed.
- Abstract is kept one sentence per line in `metadata.yaml`; its first sentence is open for revision in review.
- Abstract: mentions "come up repeatedly across meetings and months", and the three forms are numbered; the method is framed as making implicit connective context explicit.
- Manuscript is one sentence per line, and the build keeps those breaks in the `.tex` (`--wrap=preserve`).
- Disclosure section removed; the author's role on the commission is disclosed on each published meeting in GovCenter.

## 0.1.0 - 2026-11-02

- First public version, drawn from GovCenter's research note `docs/research/MEETING_DISTILLATION.md` and the working paper at `/admin/how-it-works`.
- Evidence: seven Vacaville Parks and Recreation Commission meetings, June 2025 to August 2026, counted from the local record on 2026-11-02.
- Figure 1 is the "Meeting parts" frame in `~/workspace/tldrawings/govcenter.tldr` (spec `tldr-helper/draw/specs/govcenter-meeting-parts.json`).
