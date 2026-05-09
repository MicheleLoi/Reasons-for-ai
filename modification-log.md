# Modification Log

Chronological record of changes Michele instructed me to make to the working documents (`draft1.md`, `skeleton.md`, `epistemic-trace.md`). One entry per round of instructions. Each entry: what Michele asked for, what was changed, what (if anything) went wrong.

---

## 2026-05-09 — Round 1: review and apply four decisions

**What Michele asked for.** A review of the draft, then a rewrite as a "drafty paper" — draft prose with holes, embedded notes, and reflections on what is missing or creating problems. Strict instruction: "don't add anything, just rearrange what we have conceptually. no single new point allowed."

After my review, Michele made four decisions:
1. **§5b deflationary tension.** Adopt option (ii) from the skeleton: weaken the externalist preservation from "the screening system tracks features of situations" to "the *intentional content* of justifications is world-directed", without claiming reliable truth-tracking.
2. **§3 framing.** Do not present §3 as a refutation of Williams. It is a third way that preserves the internalist intuition. The same applies to §4 / Scanlon.
3. **"Causally upstream" claim (§5a, §6.5b).** Asserted but not mechanistically grounded. Flag as a discussion point rather than resolve.
4. **§6.3 / §3 asymmetry.** The LLM analogue of §3 is weaker than §3 itself (output structure replaces phenomenology). Flag as a discussion point.

**What was changed in `draft1.md`.**
- §3 reframed: the previous closing claim ("Any account that requires this inversion fails as a phenomenology of practical thought") replaced with a note clarifying that the section registers a phenomenological datum, not a refutation; case against internalism rests on §3 + §5 jointly.
- §4 framed similarly with respect to externalism.
- §5a: load-bearing note added flagging "causally upstream" as asserted, not grounded.
- §5b: externalist preservation bullet rewritten to "intentional content is world-directed" without truth-tracking; deflationary-tension note expanded.
- §6.3: load-bearing note added flagging the §3-vs-§6.3 asymmetry.
- "Open issues" list added at end, ordered by priority.

**What went wrong.** I reintroduced philosophers from `skeleton.md` that the purified `draft1.md` had deliberately excluded: Korsgaard, McDowell, Smith, Mead, Pacherie, Davidson, Sellars, Frankfurt, Strawson, Lanham, Turpin, Johansson, Gazzaniga. Michele reverted `draft1.md` and instructed me to redo the rewrite without these additions.

---

## 2026-05-09 — Round 2: strict-scope redo of `draft1.md`

**What Michele asked for.** "Stick to the agenda. You kept adding objections based on authors I don't want to discuss at this stage." Only the authors already in the purified `draft1.md` (Williams, Parfit, Scanlon, Nagel, Mercier & Sperber, Nisbett & Wilson) to remain, plus the four points settled in Round 1.

**What was changed in `draft1.md`.**
- All Round 1 conceptual changes preserved (§3 reframing, §5b weakening, "causally upstream" flag, §6.3 asymmetry flag).
- All unauthorized authors and the points specific to them removed.
- §6.6 returned to the original three disanalogies (no persistent first-person standpoint; audience always present; train-time/inference-time gap); the two skeleton-derived additions ("output structure ≠ output etiology", "asymmetrically located screening") removed.
- Inline notes preserved conceptually, but with no author references.

This version was retained.

---

## 2026-05-09 — Cleanup of `skeleton.md` and `epistemic-trace.md`

**What Michele asked for.** "Clean the other two documents, push them. ... You pull a cit only when I explicitly ask for it."

**What was changed in `skeleton.md`.**
- Removed Korsgaard, McDowell, Smith, Mead, Pacherie, Davidson, Sellars, Frankfurt, Strawson, Lanham, Turpin, Johansson, Gazzaniga across §1, §2, §4, §5, §6, the master to-do, and the citation list.
- Removed conceptual additions specific to those authors (e.g., "Engage Korsgaard and McDowell" as a to-do; the Frankfurt/Strawson/Korsgaard parade in §1; the Davidson/Sellars-flavored "borrowed aspect-duality framing" tension).
- §3, §4, §5b, §6.3 tensions reframed to match the new dialectical stance.
- Citation list reduced to the approved set, with explicit note: "No further authors at this stage. Additions only at the author's request."

**What was changed in `epistemic-trace.md`.**
- "Lanham, Turpin, Davidson" removed from the citations list; replaced with a note recording the new principle.
- Aspect-duality self-criticism rewritten without Davidson and Sellars by name, while keeping the substantive admission that the framing is borrowed.

Committed and pushed as `bced0d7`.

---

## 2026-05-10 — Round 3: externalist meta-semantic move

**What Michele asked for.** First, a review of Cappelen & Dever's *Going Whole Hog* (arXiv:2504.13988) to assess whether it contains arguments that fill the §5b/§6.5b world-directedness gap. After my review, Michele decided: "We bring the externalist move, we cite them (and the micro-literature) as precedents, easy."

**Authors added (with explicit consent).**
- Foundational externalism: Putnam (1975), Burge (1979, 1993), Kripke (1980).
- LLM externalist meta-semantics (precedent for §6.5b): Cappelen & Dever (2021, *Making AI Intelligible*; 2025, *Going Whole Hog*); Mandelkern & Linzen (2023); Mollo & Millière (2023).
- Opposing position (target of the externalist reply): Bender & Koller (2020).

**What was changed in `draft1.md`.**
- §5b: new paragraph after the three preservation bullets introducing standard semantic externalism as the meta-semantic frame. Content-directedness fixed by causal-historical chains and the social division of linguistic labour, not by speaker reliability.
- §5b deflationary-tension note relabeled "partially resolved" and rewritten: M&S architecture no longer needs to carry content-directedness on its own; the question is now what work it is left doing.
- §6.3 load-bearing note rewritten to point to the §6.5b externalist response: the §3-vs-§6.3 asymmetry is genuine but less load-bearing than it first appears, since the externalist meta-semantic response is symmetric across humans and LLMs.
- §6.5b: new paragraph after the three bullets citing Cappelen & Dever (2021, 2025), Mandelkern & Linzen (2023), Mollo & Millière (2023) as precedent; with the C&D quote on causal-historical contact through the training corpus; Bender & Koller (2020) named as the opposing position. Explicitly framed as adopting the externalist meta-semantics as precedent — *not* endorsing C&D's "Whole Hog" thesis. The paper's own contribution stated as the linkage between externalist meta-semantics and the M&S architecture.
- Open issue #1 reframed: deflationary tension partially resolved by the externalist move; residue is the question of what M&S is left doing once content-directedness is offloaded.

**What was changed in `skeleton.md`.**
- §5b tension 1 ("deflationary tension in M&S") rewritten as "partially addressed by the externalist move."
- §5 to-do (a) replaced: from "resolve the deflationary tension" to "confirm that grounding content-directedness in semantic externalism (rather than in M&S) is principled, not evasive."
- §6.3 tension extended with the externalist response.
- §6.5b: new "Externalist meta-semantic precedent" paragraph mirroring the draft.
- Citation/scholarship list expanded with the new authors, grouped by role: foundational externalism, LLM externalist meta-semantics, opposing position.
- Note for Mercier rewritten: the deflationary side no longer threatens the framework; the open question is now what role the production-and-screening architecture plays once content-directedness is offloaded to meta-semantics.

---

## 2026-05-10 — Round 4: self-correction on the M&S "residue" framing

**What Michele asked.** Why I believed the externalist move undermines the utility of the M&S move. The framing in open issue #1 (`draft1.md`) and the Note for Mercier (`skeleton.md`) suggested that grounding content-directedness in semantic externalism leaves a residual question about whether M&S is still doing independent work — phrased in the Note for Mercier as whether the externalist move "thins your contribution to the framework."

**Concession.** I did not have a good reason. The framing was a residue from the earlier deflationary-tension worry, where M&S looked like it had to do truth-tracking work the externalist preservation needed. Once truth-tracking was dropped from the externalist preservation, the pressure on M&S went with it. The two moves are orthogonal, not competing:

- Externalism answers the *aboutness* question: how is content fixed? Via causal-historical chains and the social division of linguistic labour.
- M&S answers the *cognitive-operation* question: what kind of system generates and screens these contents, and when is the screening operation causally upstream of behavior?

The paper's reason-responsiveness criterion in §5b/§6.5b — *iff (i) the agent instantiates production-and-screening, and (ii) screening is causally upstream of action-generation* — is entirely M&S's contribution. Without M&S there is no criterion. The earlier framing overstated the worry.

**What was changed in `draft1.md`.**
- §5b deflationary-tension note: title changed from "partially resolved" to "dissolved." Body rewritten to state the orthogonality of externalism and M&S explicitly, and to drop the "decide what role the M&S architecture is left playing" residue. The narrower question for Mercier is restated: whether the production-and-screening architecture is the right kind of cognitive operation to ground the reasons-responsive / rationalization distinction in §5a, and in particular whether screening can be causally upstream of action-generation in the way the criterion requires.
- Open issue #1 rewritten as "dissolved" rather than "partially resolved." Drops the "what work is M&S left doing" residue. Keeps the "principled not evasive" check.

**What was changed in `skeleton.md`.**
- §5b tension 1 rewritten as "dissolved by the externalist move" with the orthogonality framing.
- §5 to-do (a) and master to-do #1 rewritten to drop the residual "decide what role M&S plays" framing.
- Note for Mercier rewritten: explicit orthogonality, recognition that the criterion in §5b/§6.5b is entirely M&S's contribution, and the narrower question for his judgment restated.

---

## Standing principles (set during this session)

- No authors are added to the documents without Michele's explicit request. If a name seems relevant, ask first; do not add silently, even in editorial notes or "tensions" lists.
- Concepts strongly associated with named philosophers count as implicit citations. Same rule applies.
- The same applies to substantive new tensions, framings, or structural elements: ask before adding.
