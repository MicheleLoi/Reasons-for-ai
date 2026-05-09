# Reasons for AI — Skeleton Draft

Skeleton only. Argument structure, tensions, and to-dos surfaced rather than smoothed. Intended for circulation to Mercier; structured so weaknesses are visible.

---

## §1. Thesis

- AI ethics is currently framed as rule-compliance: alignment, guardrails, value specification, refusal training, RLHF.
- Rule-compliance is not moral agency. Moral agency requires *reason-responsiveness*: the agent's behavior is governed by the considerations that make an act good or bad, not merely by learned correlations with those considerations.
- Therefore: an account of what reasons are, and what it takes to be moved by them, is a precondition for taking AI moral status, trust, and explainability seriously.
- The paper offers such an account and applies it symmetrically to humans and to LLMs.

**Tensions / open**
- "Moral agency requires reason-responsiveness" is asserted as a conceptual claim but is contested (Frankfurt-style hierarchical accounts, Strawson on reactive attitudes, Korsgaard on rational autonomy each give different criteria). The paper must either argue for this criterion or relativize the conclusion to it.
- The inference from "rule-compliance ≠ moral agency" to "reason-responsiveness is what's missing" needs a step. There are intermediate options (e.g., responsiveness to reactive attitudes, possession of a self-conception). To-do: argue that reason-responsiveness is the right diagnosis, not just *a* diagnosis.

**To-do**
- Specify what work the term "moral agency" is doing. Decide whether the claim is: (a) reason-responsiveness is necessary for moral agency, (b) sufficient, (c) constitutive. The mapping to LLMs in §6 is cleanest if (a)+(c).

---

## §2. Two received views

- **Internalism**: A's reasons are constrained by A's "subjective motivational set" — desires, projects, commitments. R is a reason for A only if a sound deliberative route connects R to something A already wants. *Cf.* Williams (1981).
- **Externalism**: Some reasons obtain independently of the agent's desires. R can be a reason for A even if no deliberative route from A's current motivations reaches R. *Cf.* Parfit (2011); Scanlon (2014); Nagel (1970).

**To-do**
- Decide whether to engage with hybrid views (Smith's *Moral Problem*, Korsgaard's constitutivism, McDowell's sensibility theory). Current draft treats the dichotomy as clean for dialectical tractability; this is a simplification the paper should acknowledge.

---

## §3. Objection to internalism — first-person phenomenology

- **Argument**: When I judge that your pain gives me a reason to help, the reason-conferring fact in the deliberative content is *your pain* — a fact about you, not a fact about my motivational set. Internalism re-describes this as "I have a desire whose object includes your welfare." That re-description shifts the locus of justification from the world to the agent and inverts what the deliberating subject is responding to.

**Tensions / open**
- Williams's defender can reply that standing dispositional desires need not appear in deliberative content. The desire is causally necessary but phenomenologically silent: it enables the deliberation in which I attend to your pain, without itself being attended to. The objection then collapses into a complaint about *what is salient in deliberation*, not about *what reasons are*.
- This is the most serious unanswered objection in the paper as drafted. The §3 argument as it stands does not refute Williams; it only describes a phenomenology Williams can accommodate.

**To-do**
- Strengthen §3 in one of three ways:
  1. Argue that the dispositional-desire reply over-generates: it makes any external-looking reason internalist-compatible, draining the dispute of content.
  2. Argue from the *normative* direction of fit: deliberation aims at getting the world right, not at cataloguing one's dispositions; internalism inverts this aim.
  3. Concede that §3 alone does not refute internalism and rest the case against internalism on the combination of §3 + §5 (the dissolution shows internalism can be retained as a partial truth without its motivational thesis).

---

## §4. Objection to externalism — motivational gap

- **Argument**: If reasons obtain independently of any agent, how do they move anyone? Causation runs through minds. A brute external fact does not push limbs; it must engage perception, sensitivity, dispositions. Externalism either posits a sui generis "rational pull" (mysterious) or readmits the agent's psychology (collapsing toward internalism).

**Tensions / open**
- Externalists have replies the paper does not yet engage:
  - Korsgaard: rational agents are constitutively responsive to reasons; the "pull" is not external but is the agent's own rational nature operating.
  - McDowell: the perceptually trained sensibility *is* what makes reasons motivating; externalism is not separation but second-nature attunement.
- These responses arguably solve the motivational gap in ways that pre-empt §5's third-way move.

**To-do**
- Address Korsgaard and McDowell explicitly. The cleanest path: argue that both responses owe an account of *how* the rational nature / sensibility comes to be in place, and that §5's Mercier–Sperber story is the best naturalistic candidate for that account. This converts §5 from "third way" to "the missing mechanism the externalists need."
- Decide: is §5 a *rival* to externalism or a *naturalization* of it? The paper currently equivocates.

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
- *Externalist intuition preserved*: the screening system is built to track features of situations — others' pain, consistency, fairness — so the *content* of the justifications it produces is world-directed.
- *Single criterion*: an agent has reasons in the relevant sense iff (i) it instantiates a justification-producing-and-screening system, and (ii) that system is causally upstream of its action-generation, not merely a rendering downstream of it.

**Tensions / open — these are the load-bearing weaknesses of the paper**

1. **The deflationary tension in Mercier–Sperber.** M&S's own view is partly deflationary: reasoning evolved for argumentative persuasion, is confirmation-biased, and does not paradigmatically track truth in the individual case. The paper uses their architectural claim (production + screening) to ground a content-tracking claim ("the system tracks features of situations — others' pain, fairness, consistency"). The content-tracking claim is *not obviously theirs* and may be in tension with their deflationary side. Without resolution, the paper rests on a citation that does not bear the weight placed on it.

2. **The "screening is causally upstream" claim is asserted, not shown.** No mechanism is given by which screening exerts causal grip on action-generation, in humans or in LLMs. The paper waves at empirical work as if it will deliver this. The actual evidence is contested: choice-blindness studies suggest screening often fails; CoT faithfulness studies in LLMs are mixed.

3. **The "tracks features of situations" claim is doing externalist work it has not earned.** M&S's screening operation evaluates *justifications* (their structure, their fit with audience commitments). Whether evaluating justifications amounts to *tracking world-features* is a further claim. If it does not, the externalist intuition is not preserved and §5b's dissolution fails on that side.

4. **The internalization-without-audience step is under-argued.** It is doing the work of converting a social practice into private rationality. The mechanism is unclear: imitation? rehearsal? simulation of the generalized other (Mead)? The paper currently asserts it. If it does not happen reliably, §5 collapses back into a story about social justification that does not deliver private practical reasoning.

5. **The §3 objection to internalism is not refuted, only restated.** See §3 to-dos.

6. **Hybrid externalists (Korsgaard, McDowell) may pre-empt the third way.** See §4 to-dos.

7. **The aspect-duality framing — "causal from outside, justificatory from within" — is borrowed.** It echoes Davidson's anomalous monism, Sellars's manifest/scientific image distinction, and the personal/sub-personal distinction in cognitive science. The paper currently presents it as if it were the framework's own move. This should be acknowledged.

**To-do (in priority order for the §5 argument)**
- (a) Resolve the deflationary tension. Either: (i) defend a non-deflationary reading of M&S supported by the screening operation; (ii) weaken the externalist preservation claim in §5b to "the *intentional content* of justifications is world-directed" without claiming the system tracks truth; or (iii) supplement M&S with another account that delivers content-tracking (e.g., teleosemantic naturalization).
- (b) Provide a mechanism for "screening upstream of action." Candidate: Pacherie on intentions, dual-process accounts of deliberation, model-based reinforcement learning analogs in cognitive science.
- (c) Engage Korsgaard and McDowell. Position §5 as the naturalistic mechanism their views require.
- (d) Defend or weaken the internalization step. Mead's generalized other and the developmental literature on perspective-taking are candidates.
- (e) Acknowledge the borrowed aspect-duality framing.
- (f) Decide §3's strategy (refute Williams or rest on §3+§5 jointly).

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

**Tension**: this could be sophisticated mimicry of human outward-aiming. The §3 objection in the human case at least has phenomenology to lean on; the LLM case has only output structure. Whether output structure suffices is a substantive open question.

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
- *Externalist intuition preserved*: the *content* of the justifications is world-directed because the system was trained on world-directed justifications.
- *Single criterion, applied*: an LLM has reasons iff (i) it instantiates a justification-producing-and-screening system, and (ii) that system is causally upstream of its action-generation. Same criterion as §5b. Reduces to an interpretability question.

### §6.6 Disanalogies (load-bearing — do not paper over)

1. **No persistent first-person standpoint across sessions.** The internalization step in §5 takes a social practice and turns it private over developmental time. LLMs lack persistent identity across interactions; whatever internalization happened in training is frozen and may not recapitulate the developmental structure that gives human reasons their privacy and authority.

2. **The audience is almost always present.** The move in §5 from outward justification to genuinely self-directed reflection requires the agent to apply screening *without* an audience. LLMs almost always have a user. Whether self-directed reflection happens at all in LLMs is doubtful; more likely the model treats every output as audience-facing.

3. **Train-time vs. inference-time reason-following may come apart.** The system that *produced* the dispositions (training) reasoned in some sense (gradient descent on objectives derived from human-rated reasoning). The system *deploying* them (inference) may not. The criterion in §6.5b is ambiguous between these.

4. **Output structure ≠ output etiology.** §6.3's argument that LLM justifications are "world-directed" rests on output content. But output content is precisely what next-token prediction is trained to generate, regardless of whether anything internal corresponds to it. The §3 phenomenology argument has no LLM analogue strong enough to rule out mimicry.

5. **The screening mechanism is asymmetrically located.** In humans, both production and screening are inside the agent. In LLMs, screening is partly externalized into the reward model and partly internalized into the policy. Whether this counts as "the same system" or as a structural disanalogy is unresolved.

**Tensions / open**
- The disanalogies in 6.6 may be corrosive enough that the §6.5b criterion is *applicable in form but vacuous in substance*. The paper should state plainly: it is possible the right verdict is "LLMs satisfy the formal criterion without satisfying what the criterion was meant to track." This would not falsify the framework; it would localize the open question.

**To-do**
- (a) Engage interpretability literature on CoT faithfulness (Lanham et al. 2023; Turpin et al. 2023; Anthropic's mechanistic interpretability work). The criterion in §6.5b stands or falls on this empirical work.
- (b) Decide whether the disanalogies in §6.6 require a *weakening* of the symmetric criterion (e.g., "humans satisfy it paradigmatically, LLMs satisfy it in attenuated form") or an *acceptance* that LLMs may satisfy it.
- (c) Address the train-time/inference-time ambiguity. Candidate: argue that the criterion applies only to inference-time, and that train-time reasoning is the analogue of evolutionary/developmental shaping rather than of the agent's reasoning.
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
1. Resolve the M&S deflationary tension (§5 to-do (a)). **Highest priority — the framework rests on this.**
2. Provide a mechanism for "screening causally upstream of action" (§5 to-do (b)).
3. Engage Korsgaard and McDowell (§4 to-dos).
4. Decide §3 strategy (refute Williams or rest on §3+§5).
5. Engage interpretability literature on CoT faithfulness (§6 to-do (a)).
6. Address the disanalogies in §6.6 — either weaken the criterion or accept LLM applicability with eyes open.
7. Address train-time/inference-time ambiguity (§6 to-do (c)).
8. Defend or weaken the internalization-without-audience step (§5 to-do (d)).

### Citation/scholarship
- Williams (1981) — get the response from his later work on reasons.
- Parfit (2011), Scanlon (2014), Nagel (1970).
- Mercier & Sperber (2011, 2017). Crucially: their own claims about the function of reasoning, especially the deflationary side.
- Korsgaard (1996, 2009).
- McDowell (1998).
- Smith (1994) on the moral problem (hybrid view).
- Mead on the generalized other (for the internalization step).
- Pacherie on intentions (for the upstream-causation mechanism).
- Nisbett & Wilson (1977); Johansson et al. on choice blindness; Gazzaniga on split-brain.
- Lanham et al. (2023) and Turpin et al. (2023) on CoT faithfulness.
- Davidson (1970) on anomalous monism, for the aspect-duality framing.

### Structural
- Acknowledge the borrowed aspect-duality framing.
- Decide on §7 inclusion.
- Decide the scope claim about "moral agency" in §1.

---

## Note for Mercier

The framework leans heavily on the architectural claim from *The Enigma of Reason* (production + screening, primarily social, internalized). The point at which the paper most exceeds your view is the claim in §5b that the screening system *tracks features of situations* — others' pain, fairness, consistency. That is needed to preserve the externalist intuition and to deliver the symmetric criterion in §6.5b. The deflationary side of your view does not obviously support this. The paper would benefit greatly from your judgment on whether (a) this is a faithful extension of your view, (b) a defensible departure, or (c) a misuse. The §5 to-do (a) above is the place in the paper where this is decided.
