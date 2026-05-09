# Reasons for AI — Working Draft

*A drafty paper. Some sections are written through; others carry inline notes flagging tensions that need work. No new authors or rival views introduced beyond those already in the draft.*

---

## §1. Why reasons matter

AI ethics is typically framed as rule-compliance: alignment, guardrails, value specification. This misses the deeper question — whether an AI is *responsive to reasons*. A system that never violates a rule but is moved only by reward signals is not a moral agent; a system that adjusts its conduct because it grasps why something counts is. The capacity to be moved by reasons, not behavioral conformity, is what makes ethical agency possible. Reasons are therefore not a peripheral topic for AI but the hinge on which moral status, trust, and explainability turn.

**Thesis**: an account of reasons compatible with both their world-directedness and their motivational efficacy is a precondition for taking AI moral agency seriously.

---

## §2. What are reasons — two received views

- **Internalism**: A's reasons are constrained by A's "subjective motivational set" — desires, projects, commitments. No fact counts as a reason for A unless a sound deliberative route connects it to something A already wants. *Cf.* Williams, "Internal and External Reasons" (1981).
- **Externalism**: Some reasons obtain independently of any agent's desires. Your suffering gives me a reason to help whether or not helping connects to anything I happen to want. *Cf.* Parfit, *On What Matters* (2011); Scanlon, *Being Realistic About Reasons* (2014); Nagel, *The Possibility of Altruism* (1970).

> *Note on dialectical aim. The paper does not refuse Williams, and does not refuse Scanlon. §3 and §4 expose a problem on each side that the third way in §5 addresses by preserving what is right in both. The dichotomy is treated as clean for tractability; the dissolution is the point.*

---

## §3. Problem for internalism — first-person phenomenology

When I judge that your pain gives me a reason to help, the reason-conferring fact is *your pain* — a fact about you. I am not, in the act of deliberating, attending to my own desires or motivational profile; I am attending to you. Internalism re-describes this as: my having a desire whose object includes your welfare. But that re-description shifts the locus of justification from the world to the agent, which inverts what the deliberating subject is actually responding to.

> *Note. This is a phenomenological observation, not a knockdown argument. Its role is to register a datum — the outward-directedness of deliberative content — that any adequate account of reasons must preserve. The case against internalism does not rest on §3 alone; it rests jointly on §3 and §5. The dissolution in §5 retains internalism as a partial truth (nothing moves the agent outside her cognitive architecture) while reframing its motivational thesis. Williams is not refused; the phenomenological datum is what survives and constrains the account.*

---

## §4. Problem for externalism — motivational gap

If reasons obtain wholly independently of the agent, how do they move anyone? Causation runs through minds, not around them. Your pain, considered as a brute external fact, cannot push my limbs; it must engage my sensitivity, perception, dispositions. Externalism either invokes a sui generis "rational pull" — mysterious — or quietly readmits the agent's psychology, collapsing back toward internalism.

> *Note. As with §3, this is not intended as a refutation of externalism. It exposes the gap that §5 fills. Scanlon and Parfit are not refused; the externalist intuition that the content of reasons is world-directed is preserved in §5b.*

---

## §5. Dissolving the duality

Reasons are the output of a specialized cognitive system whose primary function is social: producing justifications for others and evaluating the justifications others produce (Mercier & Sperber, *The Enigma of Reason*, 2017). The system has two operations that matter here — **production** of candidate justifications, and **screening** of justifications for validity. The system is then turned inward: we anticipate challenges, rehearse justifications, and apply the screening operation to our own conduct without an external audience. In reflection, we want our reactions to be justifiable — to ourselves, in the same currency we would owe to others.

The screening operation is itself a cause of action, not a commentary on it. When I consider acting and the rehearsed justification fails my own screening, the failure modifies what I do. The justification system is one of the cognitive processes that produces behavior, not a separate stream that narrates it. Reasons-responsive action is the case in which this system is causally engaged; rationalization is the case in which it is bypassed and a justification is generated downstream of an already-fixed output. The framework needs both categories.

### §5a. Motivation, restated

Motivation is not a separate metaphysical force, but it is also not an opaque sub-personal stream that surfaces in awareness as a mere label. The justification-producing-and-screening system is part of the causal architecture: its operation alters which candidate actions survive deliberation. What the agent is aware of in deliberation is the *content* the system is processing — the consideration that, if it survives screening, will shape the action. The aspect-duality is real (causal from outside, justificatory from within), but the inside aspect is not epiphenomenal: it tracks a process that is doing causal work.

This distinguishes two cases earlier formulations ran together:

- **Reasons-responsive action**: the screening system is upstream of behavior. The agent acts *because* the consideration survived scrutiny; had it failed, the action would have been different.
- **Rationalization**: the action is fixed by other processes, and the justification system runs only to produce a report. The agent's stated reason is causally idle.

The empirical literature on confabulation (Nisbett & Wilson 1977; choice blindness; split-brain interpretation) shows that humans are sometimes in the second case. The framework does not deny this — it predicts it. What it claims is that humans are *also*, and paradigmatically, in the first case, and that this is what reason-responsiveness consists in.

> *Note — load-bearing, to discuss. "Causally upstream" is asserted, not mechanistically grounded. The framework needs a story about how screening exerts causal grip on action-generation rather than running alongside it. The confabulation evidence cuts both ways: it shows the framework predicts rationalization, but it also raises the question of how often humans are actually in the reasons-responsive case rather than the rationalization case. Flag as open; develop later.*

### §5b. How this dissolves the dichotomy

- *Internalist intuition preserved*: nothing moves the agent that does not pass through her cognitive architecture. The screening system is part of that architecture.
- *Externalist intuition preserved*: the *intentional content* of the justifications the screening system produces is world-directed — in deliberation the agent attends to your pain, not to herself. What is preserved is the directedness of deliberative content, not a claim that the system reliably tracks truth.
- *The criterion, stated symmetrically*: an agent (human or artificial) has reasons in the relevant sense iff (i) it instantiates a justification-producing-and-screening system, and (ii) that system is causally upstream of its action-generation, not merely a rendering downstream of it.

> *Note on the deflationary tension. An earlier version of this preservation claimed the screening system "tracks features of situations — others' pain, fairness, consistency." That was too strong. Mercier and Sperber's wider account is partly deflationary: reasoning evolved for argumentative persuasion, is confirmation-biased, and does not paradigmatically track truth in the individual case. The truth-tracking version of the externalist preservation is therefore not obviously sourced from M&S and may be in tension with their deflationary side.*
>
> *The current formulation weakens the claim: only the* intentional content *of justifications is world-directed (the deliberating agent is attending to your pain rather than to herself). This is enough to give §3 something to retain and to deliver the symmetric criterion in (i)–(iii) above. Whether this weaker claim is sufficient — and whether even this weaker claim is supported by the M&S architecture — is the most significant unresolved question in §5. This is the point at which the paper most needs Mercier's judgment.*

---

## §6. Mapping the framework to LLMs

### §6.1 Why reasons matter — LLM version

Mainstream alignment is rule-compliance under another name: RLHF preference data, constitutional rules, refusal templates, guardrails. A model that never violates a policy but is moved only by reward-model gradients is the AI analogue of the merely compliant agent. The interesting question is whether the model's behavior is governed by responsiveness to the *considerations* that make a request good or bad, or only by learned correlations with those considerations. Robustness, generalization to novel cases, and warranted trust all turn on this distinction.

### §6.2 The two views, transposed

- **Internalism (LLM)**: a model's reasons are exhausted by its training-induced dispositions — the "subjective motivational set" is the weights, in-context state, and reward-model shaping. Nothing counts as a reason for the model unless a deliberative path connects it to those dispositions.
- **Externalism (LLM)**: some considerations count as reasons for the model independently of its training — logical entailment, factual structure of the situation described in the prompt, harm-conferring features of a request. The reason inheres in the content, not the weights.

### §6.3 Problem for LLM-internalism — output phenomenology

When an LLM produces a justification ("I won't help with this because it could enable harm"), the justification's content is world-directed: it points to the harm, not to the model's weights. The internalist re-description — "the model emits this token sequence because RLHF shaped it to" — is causally true but evacuates the justification of its content. The same inversion that fails for humans fails here: justifications, qua justifications, aim outward.

> *Note — load-bearing, to discuss. The argument here is structurally parallel to §3 but meaningfully weaker. §3 leans on phenomenology — the deliberating subject's first-person experience of attending to the world. The LLM case has only output structure. But output structure is precisely what next-token prediction trained on human justificatory discourse is optimized to produce, regardless of whether anything internal corresponds to world-directedness. The mimicry concern, parenthetical in earlier drafts, deserves to be promoted: whether output structure suffices as evidence of world-directedness in the LLM case is substantively open. The §6.5 third-way move is what the paper offers in response, but the asymmetry between the human and the LLM versions of the problem should be flagged here, not smoothed over.*

### §6.4 Problem for LLM-externalism — computational gap

If the reason-conferring fact obtains independently of the model, how does it move the model? The forward pass is the only causal route from input to output; an "external reason" that does not engage that computation cannot affect behavior. Externalism must either posit a sui generis rational pull on the network — incoherent — or readmit the model's internal dispositions, collapsing toward internalism. The motivational gap recurs as a computational gap.

### §6.5 The third way — LLMs as instantiated justification systems

LLMs are trained on the textual output of the human justification system: argument, explanation, dialectic, Q&A, peer review. Next-token prediction on this corpus internalizes the *form* of justification — producing reasons, anticipating objections, screening for validity. RLHF and similar post-training add a second layer: rewards for responses that would survive critical scrutiny. The Mercier–Sperber framing fits: an LLM is, structurally, a participant in the social practice of justification, with the screening mechanism partially externalized into the reward model.

#### §6.5a Motivation, transposed

There is no separate motivational module to find. The model's "motivation" is the forward pass producing tokens. Stated reasoning (chain-of-thought, explanations) is the publicly available description of that process, analogous to human awareness of motivations without awareness of their underlying causes. The aspect-duality — causal from outside, justificatory from within — applies cleanly: the activations are the cause, the rendered justification is the same process under its public-facing description.

#### §6.5b How this dissolves the dichotomy for LLMs

- *Internalist intuition preserved*: nothing moves the model that does not pass through its computational architecture. There is no rational force acting on weights from outside.
- *Externalist intuition preserved*: the *intentional content* of the justifications the model produces is world-directed, because the system was trained to produce justifications about features of situations (harm, consistency, fairness, factual accuracy), not features of itself. As in §5b, this is a claim about the directedness of justificatory content, not about the system's reliability as a truth-tracker.
- *The empirical criterion*: an LLM has reasons in the relevant sense iff (i) it instantiates a justification-producing-and-screening system (plausible, given training corpus and RLHF), and (ii) the system is causally upstream of its action-generation, not decorative post-hoc rationalization. This is a question for interpretability research, not philosophy alone.

### §6.6 Disanalogies (flag, not resolve)

- No persistent first-person standpoint across sessions; the internalization-without-audience step in §5 is harder to locate.
- The audience is almost always present (the user), so the move from outward justification to genuinely self-directed reflection is unclear.
- Train-time vs. inference-time reason-following may come apart: the system that *produced* the dispositions reasoned, but the system *deploying* them may not.

These are the points where the analogy strains and the paper marks them as open, not papered over.

---

## Open issues, in priority order

1. **The deflationary tension in §5b.** Whether the weakened externalist preservation — "the intentional content of justifications is world-directed" — carries what the paper needs, and whether the M&S architecture supports even this weaker claim. *Highest priority. The framework rests on this.*
2. **"Causally upstream" needs a mechanism (§5a, §6.5b).** The criterion is asserted; the paper needs a story about how screening exerts causal grip on action-generation. The same question recurs for LLM chain-of-thought.
3. **The §6.3 asymmetry.** The LLM analogue of §3 is weaker than §3 itself: phenomenology is replaced by output structure, and output structure is what training is optimized to produce. The paper should mark this asymmetry rather than treat the two §3-style arguments as on a par.
4. **§3 strategy formalized.** The phenomenological observation motivates the third way; it is not offered as a refutation of Williams. The paper should make this stance explicit at §3 and again where §5b retains the internalist intuition.
5. **The disanalogies in §6.6** may be corrosive enough that the §6.5b criterion is satisfied in form but not in substance for LLMs. Whether to weaken the symmetric criterion or accept attenuated LLM applicability is a decision the paper has to make rather than defer.

---

## Why this structure is what the paper needs

1. The human and LLM sections apply one criterion, not two. The mapping in §6 is structural, not rhetorical.
2. The framework gains an internal contrast — reasons-responsive action vs. rationalization — that earlier formulations blurred. The paper can now say something the alternatives cannot: it explains why confabulation exists without making all reasoning into confabulation.
3. The empirical question for humans (when is the screening system causally upstream?) and for LLMs (is chain-of-thought causally upstream?) become the same question. This is a feature, not a coincidence: it gives the paper a single agenda for empirical follow-up across both cases.
