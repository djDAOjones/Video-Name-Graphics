# Decisions

<!-- Newest first. Never edit an old entry; supersede it. Rule 1 reads
     exactly the latest ten entries' heading, Decision line and Deferred
     line, newest first. The Decision line states the what and its
     one-line why; Rationale holds evidence and detail, read on demand.
     The slice fails at close over 1,000 words. Grammar:
     ## YYYY-MM-DD — ID — title
     **Decision:** what was decided and its one-line why.
     **Rationale:** evidence and detail, in the terms another session
     would need.
     **Supersedes:** YYYY-MM-DD — ID — title, or "none".
     Optional **Deferred:** comma-separated target IDs, or "none".
     A PLAN-N entry also has **Items:** with its phase IDs; a later
     PLAN-N Items list replaces the whole list and supersedes the
     earlier; a closed phase is checked against the list no other
     supersedes. Optional **Retired:** names items retired unshipped.
     Budget 45 live entries: when the validator warns, tools/archive.mjs
     moves the oldest entries verbatim to project/decisions-{YYYY-MM}.md
     and adds one line to project/archive-index.md. -->

## 2026-11-05 — PLAN-1 — Phases 1 and 2: the seed, the brand packs and the output format, then one graphic end to end

**Decision:** Phase 1 is VNG-1 to VNG-4, the seed, the brand packs, the output spike and the three languages; Phase 2 is VNG-5 to VNG-7, one graphic end to end; the release items VNG-8 and VNG-9 follow — because the owner approved this order on 2026-11-05.

**Rationale:** The output format carries the project's one real technical risk: Clipchamp's help pages list MP4, MOV and WebM as accepted formats but say nothing about transparency (searched 2026-11-05), so the format is settled by a spike a person checks in Clipchamp before any style is drawn. The brand seam comes before the first style so that no style is written against one brand. VNG-7 waits for the owner's design source; the owner's earlier lower-third projects sit in `2_Projects/Side Projects/` (2016-10-17 UoN Lower Third, 2017-09-09 UoN New Branding Lower 3rd AE) and may be it.

**Items:** VNG-1, VNG-2, VNG-3, VNG-4

**Supersedes:** none

## 2026-11-05 — INTAKE — Video Name Graphics founded as the UoN Video Finisher's sibling: its own repository, code copied and owned, brands as build-time packs

**Decision:** a new repository, djDAOjones/Video-Name-Graphics, with its own pm-next v3.1 ledger at PM-Skills lab 4ab66b5 and IDs `VNG-n`; code is copied from the Finisher at a named commit and owned here, not forked or shared; brands are packs chosen at build time, the neutral build the default — because the owner chose this approach on 2026-11-05.

**Rationale:** The owner asked for a sibling to the Finisher that makes lower thirds, keeps its simple, accessible form and look, and ports to a non-UoN context. A separate repository keeps the Finisher's brief ("a conveyor with one cut… nothing else") and its pending Xerte release untouched, and makes "carries no UoN branding" provable in a default build. A fork would carry the Finisher's history, record, media pipeline and EBU suite; a shared package or monorepo is premature with two consumers and would add a dependency to both. Copied files name their Finisher commit (27f51dd at founding); a shared package is reconsidered when a third app needs one. Installed from the lab's `lab/next-v31` at 4ab66b5 by `git archive`, its tools and verbs byte-identical to the Finisher's. The owner's answers in session: Handoff, Network, Secrets and standards as the Finisher's; signatures delegated, not reviewed, until the owner signs. Digests: carbon, nielsen, node and wcag-2.2-aaa are the lab's at 4ab66b5, each dated by its own header, not re-fetched; carbon gains the brand-pack typeface rule; house-conventions is the Finisher's at 27f51dd with its DSP and loudness rules dropped. The Session line is the template's 350k, which the Finisher's later planning also used. Settings: `.claude/settings.json` is the Finisher's, the session hooks only, as its own decision of October left it after the sandbox blocked Chrome and local ports; `.claude/settings.intake.json` is `tools/harness.mjs`'s; the Codex profile and hooks and the post-commit hook carry absolute paths, so they are regenerated in each checkout and ignored, not committed.

**Supersedes:** none
