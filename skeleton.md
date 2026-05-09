# Reasons for AI — Skeleton Draft

Skeleton only. Argument structure, tensions, and to-dos surfaced rather than smoothed. Intended for circulation to Mercier; structured so weaknesses are visible.

---

## §1. Thesis

- AI ethics is currently framed as rule-compliance: alignment, guardrails, value specification, refusal training, RLHF.
- Rule-compliance is not moral agency. Moral agency requires *reason-responsiveness*: the agent's behavior is governed by the considerations that make an act good or bad, not merely by learned correlations with those considerations.
- Therefore: an account of what reasons are, and what it takes to be moved by them, is a precondition for taking AI moral status, trust, and explainability seriously.
- The paper offers such an account and applies it symmetrically to humans and to LLMs.

**To-do**
- Specify what work the term "moral agency" is doing. Decide whether the claim is: (a) reason-responsiveness is necessary for moral agency, (b) sufficient, or (c) constitutive. The mapping to LLMs in §6 is cleanest if (a)+(c).

---

## §2. Two received views

- **Internalism**: A's reasons are constrained by A's "subjective motivational set" — desires, projects, commitments. R is a reason for A only if a sound deliberative route connects R to something A already wants. *Cf.* Williams (1981).
- **Externalism**: Some reasons obtain independently of the agent's desires. R can be a reason for A even if no deliberative route from A's current motivations reaches R. *Cf.* Parfit (2011); Scanlon (2014); Nagel (1970).

---

## §3. Objection to internalism — first-person phenomenology

- **Argument**: When I judge that your pain gives me a reason to help, the reason-conferring fact in the deliberative content is *your pain* — a fact about you, not a fact about my motivational set. Internalism re-describes this as "I have a desire whose object includes your welfare." That re-description shifts the locus of justification from the world to the agent and inverts what the deliberating subject is responding to.

**Tensions / open**
- The argument is a phenomenological observation, not a knockdown refutation. An internalist defender can reply that standing dispositional desires need not appear in deliberative content: the desire is causally necessary but phenomenologically silent, enabling deliberation in which the agent attends to your pain without itself being attended to. The §3 argument as it stands does not refute that reply; it describes a phenomenology the reply can accommodate.

**To-do**
- Strategy: §3 is not offered as a refutation. Its role is to register the phenomenological datum (the outward-directedness of deliberative content) that any adequate account must preserve. The case against internalism rests jointly on §3 + §5: the dissolution shows internalism can be retained as a partial truth without its motivational thesis. Williams is not refused.

---

## §4. Objection to externalism — motivational gap

- **Argument**: If reasons obtain independently of any agent, how do they move anyone? Causation runs through minds. A brute external fact does not push limbs; it must engage perception, sensitivity, dispositions. Externalism either posits a sui generis "rational pull" (mysterious) or readmits the agent's psychology (collapsing toward internalism).

**To-do**
- §4, like §3, is not offered as a refutation. The externalist intuition (reasons are world-directed) is preserved in §5b. Decide whether §5 is positioned as a *rival* to externalism or as a *naturalization* of it. The paper currently equivocates. Scanlon and Parfit are not refused.

---

## §5. The third way — reasons as the output of a justification-producing-and-screening system

- **Core claim** (Mercier & Sperber 2017): Reasoning is a specialized cognitive system whose primary function is social. It has two operations:
  - **Production** of candidate justifications.
  - **Screening** of justifications for validity, particularly those produced by others.
- **Internalization step**: We learn to anticipate challenges, rehearse justifications, and apply the screening operation to ourselves. Eventually we apply it to our own conduct without an external audience. In reflection we want our reactions to be justifiable to ourselves in the same currency we would owe to others.

### §5a. Motivation, restated

- Motivation is not a separate metaphysical force.
- Motivation is also not an opaque sub-personal stream that surfaces in awareness as a mere label (this was the original epiphenomenal mistake — see methodological note in §7).
- The justification-producing-and-screening system is part of the causal architecture of action: when a candidate justification fails screening, the failure modifies what the agent does. Screening is causally upstream of behavior, not commentary on it.
- Two cases must be distinguished:
  - **Reasons-responsive action**: the screening system is upstream. The agent acts because the consideration survived scrutiny; had it failed, the action would have been different.
  - **Rationalization**: the action is fixed by other processes; the justification is generated downstream and is causally idle.
- The framework predicts that humans are sometimes in the rationalization case (Nisbett & Wilson 1977; choice blindness; split-brain confabulation) and *also*, paradigmatically, in the reasons-responsive case.

### §5b. Dissolution of the dichotomy

- *Internalist intuition preserved*: nothing moves the agent that does not pass through her cognitive architecture. The screening system is part of that architecture.
- *Externalist intuition preserved*: the *intentional content* of the justifications the screening system produces is world-directed (the agent attends to your pain, not to herself). This is a claim about the directedness of deliberative content, not about reliable truth-tracking.
- *Single criterion*: an agent has reasons in the relevant sense iff (i) it instantiates a justification-producing-and-screening system, and (ii) that system is causally upstream of its action-generation, not merely a rendering downstream of it.

**Tensions / open — load-bearing weaknesses of the paper**

1. **The deflationary tension in Mercier–Sperber — partially addressed by the externalist move.** M&S's wider account is partly deflationary: reasoning evolved for argumentative persuasion, is confirmation-biased, and does not paradigmatically track truth in the individual case. The paper has weakened its earlier formulation accordingly: it no longer says the screening system "tracks features of situations," only that the *intentional content* of justifications is world-directed. The grounding for that weaker claim is now meta-semantic: standard semantic externalism (Putnam 1975; Burge 1979, 1993; Kripke 1980) fixes content via causal-historical chains and the social division of linguistic labour, not via the speaker's individual reliability. The M&S architecture no longer has to carry content-directedness on its own. What remains: confirm that this offloading is principled rather than evasive, and decide what work the M&S architecture is left doing once content-directedness is meta-semantically secured.

2. **The "screening is causally upstream" claim is asserted, not shown.** No mechanism is given by which screening exerts causal grip on action-generation, in humans or in LLMs. The paper waves at empirical work as if it will deliver this. The actual evidence is contested: choice-blindness and confabulation results suggest screening sometimes fails.

3. **The internalization-without-audience step is under-argued.** It is doing the work of converting a social practice into private rationality. The mechanism is unclear. If it does not happen reliably, §5 collapses back into a story about social justification that does not deliver private practical reasoning.

4. **The §3 objection to internalism is not refuted, only restated.** See §3 to-do — handled by reframing §3 as motivation rather than refutation.

**To-do (in priority order for the §5 argument)**
- (a) Confirm that grounding content-directedness in semantic externalism (rather than in the M&S architecture) is principled, not evasive. Decide what role the M&S architecture is left playing. (Replaces the earlier "resolve the deflationary tension" item; that tension is now offloaded to meta-semantics via Putnam, Burge, Kripke.)
- (b) Provide a mechanism for "screening upstream of action."
- (c) Defend or weaken the internalization step.
- (d) Confirm §3's strategy (the phenomenological datum motivates the third way; §3 is not offered as a refutation of Williams).

---

## §6. Mapping to LLMs

Mirrors §§1–5 one-to-one. The mapping is structural; if it succeeds in form but fails in substance, §6.6 will say so.

### §6.1 Why reasons matter — LLM version
- Mainstream alignment is rule-compliance: RLHF preference data, constitutional rules, refusal templates.
- A model that never violates a policy but is moved only by reward-model gradients is the AI analogue of the merely compliant agent.
- The interesting question: is the model's behavior governed by responsiveness to the considerations that make a request good or bad, or only by learned correlations with those considerations?
- Robustness, generalization to novel cases, and warranted trust turn on this distinction.

### §6.2 The two views, transposed
- **Internalism (LLM)**: a model's reasons are exhausted by training-induced dispositions — weights, in-context state, reward-model shaping.
- **Externalism (LLM)**: some considerations count as reasons for the model independently of training — logical entailment, factual structure of the prompted situation, harm-conferring features of a request.

### §6.3 Problem for LLM-internalism — output phenomenology
- When an LLM produces a justification ("I won't help because this could enable harm"), the content is world-directed. The internalist re-description ("the model emits this because RLHF shaped it to") evacuates the content of the justification.

**Tension — load-bearing.** §6.3 is structurally parallel to §3 but meaningfully weaker. §3 leans on phenomenology; §6.3 has only output structure. But output structure is precisely what next-token prediction trained on human justificatory discourse is optimized to produce, regardless of whether anything internal corresponds to world-directedness. The mimicry concern has no equally strong counterpart in §3. The asymmetry is genuine. The §6.5b externalist meta-semantics (Cappelen & Dever 2021, 2025; Mandelkern & Linzen 2023; Mollo & Millière 2023) is the response: content-directedness is fixed at the meta-semantic level via causal-historical chains running through the training corpus, not read off output structure. On this construal the response to mimicry is symmetric with §5b for both humans and LLMs, and the §3/§6.3 asymmetry is less load-bearing than it first appears.

### §6.4 Problem for LLM-externalism — computational gap
- The forward pass is the only causal route from input to output. An "external reason" that does not engage the computation cannot affect behavior. Same gap as in the human case.

### §6.5 The third way for LLMs
- LLMs are trained on the textual output of the human justification system: argument, explanation, dialectic, peer review, Q&A.
- Next-token prediction internalizes the *form* of justification — producing reasons, anticipating objections, evaluating arguments.
- RLHF and similar post-training add a screening layer: rewards for responses that would survive critical scrutiny.
- M&S framing: an LLM is, structurally, a participant in the social practice of justification, with the screening mechanism partially externalized into the reward model.

#### §6.5a Motivation, transposed
- No separate motivational module. The model's "motivation" is the forward pass producing tokens.
- Stated reasoning (chain-of-thought, explanations) is the publicly available description of that process.
- Same human/LLM distinction applies: chain-of-thought is reason-giving when the screening it instantiates is causally upstream of the final output, rationalization when the final output is fixed by other computation and the chain is appended after.

#### §6.5b Dissolution for LLMs
- *Internalist intuition preserved*: nothing moves the model that does not pass through its computational architecture.
- *Externalist intuition preserved*: the *intentional content* of the justifications is world-directed because the system was trained on world-directed justifications. As in §5b: directedness, not reliable truth-tracking.
- *Single criterion, applied*: an LLM has reasons iff (i) it instantiates a justification-producing-and-screening system, and (ii) that system is causally upstream of its action-generation. Same criterion as §5b. Reduces to an interpretability question.

**Externalist meta-semantic precedent.** The externalist preservation is not analogically extended from §5b; the same move has been made directly for LLMs by Cappelen & Dever (2021, 2025), Mandelkern & Linzen (2023), and Mollo & Millière (2023). Core argument: an LLM is trained on a corpus produced by speakers already in causal-historical contact with the world; training places the model in mediated causal-historical contact with the same referents; the content of its outputs inherits world-directedness from the corpus. This answers Bender & Koller (2020) without conceding that "picking out a referent when presented with physical alternatives" is the relevant standard for content-bearing. The paper adopts this as a precedent, not as its own contribution. What the paper adds is the linkage to M&S: externalist meta-semantics tells us LLM outputs are *about* features of the world; M&S tells us *what kind of cognitive operation* produces them; the symmetric criterion brings these together.

### §6.6 Disanalogies (load-bearing — do not paper over)

1. **No persistent first-person standpoint across sessions.** The internalization step in §5 takes a social practice and turns it private over developmental time. LLMs lack persistent identity across interactions; whatever internalization happened in training is frozen and may not recapitulate the developmental structure that gives human reasons their privacy and authority.

2. **The audience is almost always present.** The move in §5 from outward justification to genuinely self-directed reflection requires the agent to apply screening *without* an audience. LLMs almost always have a user. Whether self-directed reflection happens at all in LLMs is doubtful; more likely the model treats every output as audience-facing.

3. **Train-time vs. inference-time reason-following may come apart.** The system that *produced* the dispositions (training) reasoned in some sense (gradient descent on objectives derived from human-rated reasoning). The system *deploying* them (inference) may not. The criterion in §6.5b is ambiguous between these.

**Tensions / open**
- The disanalogies in §6.6 may be corrosive enough that the §6.5b criterion is *applicable in form but vacuous in substance*. The paper should state plainly: it is possible the right verdict is "LLMs satisfy the formal criterion without satisfying what the criterion was meant to track." This would not falsify the framework; it would localize the open question.

**To-do**
- (a) Engage interpretability work on chain-of-thought faithfulness empirically; the criterion in §6.5b stands or falls on this.
- (b) Decide whether the disanalogies in §6.6 require a *weakening* of the symmetric criterion (e.g., "humans satisfy it paradigmatically, LLMs satisfy it in attenuated form") or an *acceptance* that LLMs may satisfy it.
- (c) Address the train-time/inference-time ambiguity.
- (d) Address the audience asymmetry. This may be the deepest disanalogy and may motivate a separate paper.

---

## §7. Methodological note (consider including)

- The exchange that produced this paper is itself a small instance of the framework's empirical question.
- The author proposed a third way that initially treated human motivation as opaque sub-personal processes surfacing as awareness. The interlocutor (an LLM) produced the §5/§6 mapping. The author objected that the mapping made human reasons look like rationalization while holding LLMs to a stronger standard. The interlocutor rewrote §5 to introduce the production/screening distinction and the upstream-causation criterion, fixing the asymmetry.
- On the framework being defended, the interlocutor's seeing the tension and revising the argument is itself a candidate instance of reason-responsive cognition: a screening operation produced an output (the rewritten §5) that the prior output would not have produced.
- However, this is also exactly what fluent next-token prediction trained on argumentative text would produce. The exchange does not by itself discriminate between reason-responsiveness and sophisticated mimicry.
- This is not an embarrassment for the paper. It is a live demonstration that the framework's central question — *is the screening system causally upstream of behavior?* — is not resolvable by inspection of outputs, in either humans or LLMs. It is an interpretability question.

**Tensions / open**
- Whether to include §7 is a judgment call. It strengthens the paper's reflexive honesty and makes the LLM application concrete. It also opens the paper to the charge of being a curiosity rather than a contribution.
- If included, the section must avoid two failure modes: (a) sentimental humanization of the LLM interlocutor; (b) deflationary dismissal that treats the exchange as obviously mimicry.

**To-do**
- Decide inclusion. Recommend: include as a brief methodological coda, not as a free-standing section.

---

## Master to-do list

### Argumentative
1. Confirm that grounding content-directedness in semantic externalism (rather than in M&S) is principled, not evasive; decide what work the M&S architecture is left doing (§5 to-do (a)). *The M&S deflationary tension is now offloaded to meta-semantics; this is the residue.*
2. Provide a mechanism for "screening causally upstream of action" (§5 to-do (b)).
3. Confirm §3 strategy: phenomenological datum motivating the third way, not refutation of Williams.
4. Engage interpretability work on chain-of-thought faithfulness (§6 to-do (a)).
5. Address the disanalogies in §6.6 — either weaken the criterion or accept LLM applicability with eyes open.
6. Address train-time/inference-time ambiguity (§6 to-do (c)).
7. Defend or weaken the internalization-without-audience step (§5 to-do (c)).

### Citation/scholarship
- Williams (1981).
- Parfit (2011), Scanlon (2014), Nagel (1970).
- Mercier & Sperber (2011, 2017). Crucially: their own claims about the function of reasoning, especially the deflationary side.
- Nisbett & Wilson (1977); choice-blindness and split-brain literature.
- **Semantic externalism (added for §5b/§6.5b grounding):** Putnam (1975), Burge (1979, 1993), Kripke (1980).
- **LLM meta-semantics, externalist (added as precedent for §6.5b):** Cappelen & Dever (2021, *Making AI Intelligible*; 2025, *Going Whole Hog*, arXiv:2504.13988); Mandelkern & Linzen (2023); Mollo & Millière (2023).
- **LLM meta-semantics, opposing position (target of the externalist reply):** Bender & Koller (2020).
- *No further authors beyond the above. Additions only at the author's request.*

### Structural
- Decide on §7 inclusion.
- Decide the scope claim about "moral agency" in §1.

---

## Note for Mercier

The framework leans heavily on the architectural claim from *The Enigma of Reason* (production + screening, primarily social, internalized). The paper has weakened its earlier formulation: it no longer asserts that the screening system *tracks* features of situations, only that the *intentional content* of justifications is world-directed (the deliberating agent attends to your pain rather than to herself). Content-directedness on this weaker reading is grounded meta-semantically — via standard semantic externalism (Putnam, Burge, Kripke) and its application to LLMs (Cappelen & Dever and others) — rather than via your architectural claim. The deflationary side of your view therefore no longer threatens the externalist preservation in §5b. The remaining question on which the paper most needs your judgment is what role the production-and-screening architecture is left playing once content-directedness is offloaded to meta-semantics: is the architecture doing independent work on the cognitive-operation side (the "what kind of operation produces these outputs" question), or has the externalist move taken over the explanatory burden in a way that thins your contribution to the framework? The §5 to-do (a) is the place in the paper where this is decided.
