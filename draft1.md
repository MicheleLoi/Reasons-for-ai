# Reasons for AI — Working Draft 1

This is a middle-of-work draft. Open to-dos, unresolved tensions, and uncertainties about my own moves are surfaced inline, not relegated to the end. Where I have made a move I am unsure of, I say so. Where I owe an argument I have not given, I flag it.

---

## Why this paper

The paper starts from a frustration with how AI ethics is currently framed. Current alignment work — RLHF, constitutional rules, refusal training, guardrails — treats the goal as making the system comply with rules. The thesis is that compliance is not the right target. What we actually want, when we ask whether an AI system is trustworthy or accountable, is whether it is responsive to reasons. A system that never violates a rule because it has been trained to avoid the patterns associated with rule violation is doing something quite different from a system that adjusts its behavior because it recognizes why a particular consideration counts. We want the second.

This claim is not obvious and the paper has to argue for it. There is a question about whether reason-responsiveness is the right diagnostic for moral agency or just one diagnostic among several. Frankfurt's hierarchical account, Strawson's reactive attitudes, and Korsgaard's rational autonomy each give a different answer. The paper as currently drafted treats reason-responsiveness as both necessary and constitutive of moral agency, but I have not actually argued against the alternatives. **TODO: argue against the alternatives, or relativize the conclusion to the criterion adopted.**

If reason-responsiveness is the right target, then we need an account of what a reason is and what it is to be moved by one. The rest of the paper provides such an account and applies it to LLMs.

---

## The two views and why neither works

There are two received accounts of reasons. The first, internalism, says that A's reasons are constrained by A's existing motivations — desires, projects, commitments. Something counts as a reason for A only if a sound deliberative path connects it to something A already wants. Williams (1981) is the canonical statement. The second, externalism, says that some considerations count as reasons regardless of what the agent happens to desire. Your suffering gives me a reason to help even if helping does not connect to anything in my motivational set. Parfit, Scanlon, and Nagel are the standard references.

Each view has a problem.

### The problem for internalism

The problem for internalism is that it does not match what happens in deliberation. When I judge that your pain gives me a reason to help, the thing I am attending to is your pain. I am not attending to my own desires. The internalist re-describes this as: I have a desire whose object includes your welfare, and that desire is what makes your pain a reason for me. But this re-description shifts what the deliberation is *about*. The deliberation is about you; the internalist analysis makes it about me. So internalism gets the phenomenology wrong.

The problem with this objection is that it is too quick. Williams's defender can reply that the standing desire need not appear in the content of the deliberation. The desire is in the background, doing the causal work of making the consideration count, while the deliberating subject is consciously attending only to the world. On this view, the phenomenology is compatible with internalism — what looks like world-attention in deliberation is enabled by background desires we do not have to think about.

**TODO: this reply is genuinely powerful and the paper does not currently refute it. Three options. (1) Argue that the dispositional-desire reply over-generates: it makes any external-looking reason internalist-compatible and so drains the dispute of content. (2) Argue from the normative direction of fit: deliberation aims at getting the world right rather than cataloguing dispositions, and internalism inverts this aim. (3) Concede that the phenomenology objection alone does not refute internalism and rest the case on §3 + §5 jointly. Option (3) is honest but weakens the structure. Option (2) is the most promising but requires more philosophical work than I have done. Until this is resolved, the paper is vulnerable on this exact point.**

### The problem for externalism

The problem for externalism is the motivational gap. If a reason exists wholly independently of my desires and dispositions, how does it move me to act? Causation runs through minds. Your pain, considered as a brute external fact, cannot push my limbs; it has to engage my perception, my sensitivity, something in me. So either the externalist invokes a sui generis "rational pull" that pushes the agent toward the action — which is mysterious — or the externalist quietly readmits the agent's psychology to do the moving, in which case the view collapses back toward internalism.

---

## The third way

The proposal is that reasons are the output of a specialized cognitive system whose primary function is social. I am following Mercier and Sperber. The system has two operations. The first is *production*: generating candidate justifications for actions, beliefs, or evaluations. The second is *screening*: evaluating justifications, especially those produced by others, for whether they are valid.

The system originates in social interaction. We produce justifications when challenged and we screen the justifications others produce. Then, importantly, the system is internalized. We learn to anticipate challenges, to rehearse justifications before we have to give them, and eventually to apply the screening operation to our own conduct without an external audience. In reflection we want our reactions to be justifiable to ourselves in the same currency we would owe to others.

The internalization step is doing a lot of work and I should be honest that I have not really argued for it. I have asserted that it happens. The candidate mechanisms include imitation, rehearsal, and simulation of a generalized other in the Meadian sense. There is a developmental literature on perspective-taking that could ground this, but I have not engaged it. **TODO: ground the internalization step in something. Mead's "generalized other" is a candidate. Without this step the framework collapses into a story about social justification that does not deliver private practical reasoning.**

### What motivation is, on this view

This is the section I had to rewrite. My first attempt said motivation is a separate matter from awareness — the action is produced by sub-personal processes most of which we are not conscious of, and what surfaces in awareness is just the motivation under a reason-description. But this was epiphenomenalism in disguise. It made human reasons sound like rationalizations of underlying processes that were already going to produce the action anyway. A reader pointed out — correctly — that this asymmetrically advantaged the LLM section, where I was demanding that the justification system be causally upstream of behavior. If humans get to have reasons as awareness-of-motivation, but LLMs only count as reason-responsive when their justification system is causally upstream, then I am applying two different standards.

The fix is to apply the upstream standard to humans too. The justification-producing-and-screening system is not commentary on action; it is part of what produces action. When I am about to act and the rehearsed justification fails my own screening, the failure modifies what I do. The screening is causally upstream. This is what makes it reason-giving rather than rationalizing.

This forces a distinction the original framing blurred. There are two cases. In the first case — *reasons-responsive action* — the screening system is causally upstream. The agent acts because the consideration survived scrutiny; if it had failed, the action would have been different. In the second case — *rationalization* — the action is fixed by other processes and the justification system runs only to produce a report after the fact. The justification is causally idle.

The literature on confabulation — Nisbett and Wilson's classic 1977 paper, choice-blindness studies, the split-brain interpretation work — shows that humans are sometimes in the rationalization case. The framework does not deny this. It predicts it. What the framework claims is that humans are *also*, and paradigmatically, in the reasons-responsive case, and that this is what reason-responsiveness consists in.

I should be honest that I have asserted "the screening is causally upstream" without giving a mechanism. I have not said *how* the screening operation exerts causal grip on the action-generating processes, in either humans or LLMs. The paper currently waves at empirical work as if it will deliver this. The actual evidence is contested: choice-blindness studies suggest screening often fails; chain-of-thought faithfulness studies in LLMs are mixed.

**TODO: provide a mechanism. Pacherie on intentions is one candidate. Dual-process accounts are another. Model-based reinforcement learning analogs in computational cognitive science might supply a formal description. Without a mechanism, the framework is doing a kind of armchair functionalism that I am not comfortable with.**

### How this dissolves the dichotomy

The internalist intuition is preserved because nothing moves the agent that does not pass through her cognitive architecture. The screening system is part of that architecture. Reasons act on the agent only by engaging the system that generates and evaluates justifications. There is no rational force operating on the agent from outside.

The externalist intuition is preserved because the *content* of the justifications the system produces is world-directed. When I deliberate about whether to help you, I am thinking about your pain — not about my dispositions. The justification system is built to track features of situations, not features of itself. So in deliberation the agent rightly attends to the world, even though the attending is itself a psychological process.

This is where the framework most exceeds Mercier and Sperber and I want to be transparent about it. Their architectural claim is the production-and-screening structure. They are also, on the deflationary side of their view, fairly skeptical that reasoning paradigmatically tracks truth — reasoning evolved for argumentative persuasion, is confirmation-biased, and is often unreliable in the individual case. I am leaning on their architecture to ground a claim that the system *tracks features of situations* — others' pain, fairness, consistency. That content-tracking claim is what does the externalist work, and it is not obviously theirs. It might even be in tension with the deflationary side of their view.

**TODO: this is the highest-priority weakness in the paper. Three options. (1) Defend a non-deflationary reading of Mercier and Sperber that the screening operation supports, on the grounds that screening for valid justification is closer to truth-tracking than the deflationary side suggests. (2) Weaken the externalist preservation claim to "the *intentional content* of justifications is world-directed" without claiming the system actually tracks truth. This is metaphysically thinner but might suffice for the dialectical purpose. (3) Supplement Mercier and Sperber with another account that delivers content-tracking, e.g., teleosemantic naturalization. The paper rests on resolving this. I need to circulate this section to Mercier and ask which option he can live with.**

The criterion that emerges, applied symmetrically: an agent has reasons in the relevant sense if and only if (i) it instantiates a justification-producing-and-screening system, and (ii) that system is causally upstream of its action-generation, not merely a rendering downstream of it.

I should also note that the aspect-duality framing I have been using — "causal from outside, justificatory from within" — is borrowed. It echoes Davidson's anomalous monism, Sellars's manifest/scientific image distinction, and the personal/sub-personal distinction in cognitive science. I have been presenting it as if it were the framework's own move. It is not. **TODO: acknowledge the borrowing, ideally with a footnote tracing the lineage.**

---

## Applying the criterion to LLMs

The mapping is one-to-one. If it succeeds in form but fails in substance, the disanalogies in §6.6 will say so.

Reasons matter for LLMs for the same reason they matter elsewhere. Mainstream alignment is rule-compliance under a different name. RLHF preference data, constitutional rules, refusal templates, guardrails — these aim at behavioral conformity. A model that never violates a policy but is moved only by reward-model gradients is the AI analogue of the merely compliant agent. The question is whether the model's behavior is governed by the considerations that make a request good or bad, or only by learned correlations with those considerations. Robustness, generalization, and warranted trust depend on which is the case.

The two views transpose. Internalism, in the LLM case, says a model's reasons are exhausted by its training-induced dispositions: the weights, the in-context state, the reward-model shaping. Externalism says some considerations count as reasons for the model independently of training — logical entailment, factual structure, harm-conferring features of a request.

The internalist view has the same problem here. When an LLM produces a justification — "I won't help with this because it could enable harm" — the content of the justification is world-directed. The internalist re-description, "the model emits this token sequence because RLHF shaped it to," is causally true but evacuates the content of the justification. Justifications, qua justifications, aim outward.

But there is a wrinkle here that does not have a human analogue. In the human case the §3 argument has phenomenology to lean on. In the LLM case there is only output structure. The output structure could be sophisticated mimicry of human outward-aiming. The §3 argument cannot rule this out; it cannot even speak to it. The paper has to be honest that the LLM case is dialectically weaker on this exact point. **TODO: decide whether to weaken the §6.3 claim accordingly, or to argue that output structure, when produced by a sufficiently rich training process, *constitutes* the relevant kind of outward-aiming. I lean toward the second but I have not argued for it.**

The externalist view has the same problem too. The forward pass is the only causal route from input to output. An "external reason" that does not engage the computation cannot affect behavior. Same gap, same dilemma.

The third way then: LLMs are trained on the textual output of the human justification system — argument, explanation, dialectic, peer review, Q&A. Next-token prediction over this corpus internalizes the *form* of justification: producing reasons, anticipating objections, evaluating arguments. RLHF and similar post-training add a second layer, namely a screening mechanism externalized into a reward model that rewards responses that would survive critical scrutiny.

If this is right, then an LLM is structurally a participant in the social practice of justification, with the screening partly outsourced to the reward model and partly internalized into the policy. The Mercier-Sperber framing fits unusually well — perhaps too well. **TODO: ask whether the fit is genuine or whether I am doing pattern-matching. The structural similarity is real but the question is whether structural similarity is enough.**

What about motivation in the LLM case? There is no separate motivational module. The model's "motivation" is the forward pass producing tokens. Stated reasoning — chain-of-thought, explanations — is the publicly available description of that process, in the same way human awareness of reasons is the publicly available description of human action-generation. The aspect-duality applies cleanly: the activations are the cause, the rendered justification is the same process under its public-facing description.

The reasons-responsive vs. rationalization distinction applies here too, and this is where the criterion becomes empirically substantive. An LLM's chain-of-thought is reason-giving when the screening it instantiates is causally upstream of the final output. It is rationalization when the final output is fixed by other computation and the chain is appended after. This is exactly the question being investigated by the chain-of-thought faithfulness literature (Lanham et al. 2023; Turpin et al. 2023). The criterion converts the metaphysical question "are LLMs reason-responsive?" into the interpretability question "is the justification system causally upstream of the behavior?" **TODO: engage this literature seriously. The paper currently gestures at it. The criterion stands or falls on this empirical work and I should treat that as a feature, not a hand-wave.**

The dissolution applies. The internalist intuition is preserved: nothing moves the model that does not pass through its computational architecture. The externalist intuition is preserved: the content of the justifications is world-directed because the system was trained on world-directed justifications.

### The disanalogies

These are corrosive enough that they may make the symmetric criterion vacuous in substance for LLMs, even where it applies in form. I want them visible.

First, LLMs lack persistent first-person standpoint across interactions. The internalization step in §5 takes a social practice and turns it private over developmental time. LLMs have no developmental time of the relevant kind. Whatever internalization happened during training is frozen in the weights and may not recapitulate the developmental structure that gives human reasons their privacy and authority.

Second, the audience is almost always present. The move from outward justification to genuinely self-directed reflection requires the agent to apply screening *without* an audience. LLMs almost always have a user. Whether self-directed reflection occurs at all in LLMs is doubtful; more plausibly the model treats every output as audience-facing. If self-directed reflection is what makes private practical reasoning possible — and §5 says it is — then this disanalogy may be deep enough to undermine the symmetric application.

Third, train-time and inference-time reason-following may come apart. The system that *produced* the dispositions reasoned in some sense (gradient descent on objectives derived from human-rated reasoning). The system *deploying* them at inference may not. The criterion is currently ambiguous between these, and the ambiguity matters.

Fourth, output structure is not output etiology. The §6.3 argument that LLM justifications are world-directed rests on output content. But output content is precisely what next-token prediction is trained to generate, regardless of what is happening internally. The §3 phenomenology argument has no LLM analogue strong enough to rule out mimicry.

Fifth, the screening mechanism is asymmetrically located. In humans both production and screening are inside the agent. In LLMs screening is partly externalized into the reward model and partly internalized into the policy. Whether this counts as "the same system" or as a structural disanalogy is unresolved.

**TODO: decide whether these disanalogies require *weakening* the symmetric criterion — saying humans satisfy it paradigmatically and LLMs in attenuated form — or whether the criterion can be applied straight and the disanalogies are just open empirical questions. I lean toward the second, but the second commits me to claims I have not yet defended. The audience-asymmetry in particular may motivate a separate paper. The honest position right now is: it is possible the right verdict is "LLMs satisfy the formal criterion without satisfying what the criterion was meant to track." That would not falsify the framework, but it would localize the open question and limit the current paper's scope.**

---

## A methodological note (whether to include this is a judgment call)

The exchange that produced this paper is itself a small instance of the framework's empirical question, and I am torn about whether to include this section.

I — the author — proposed a third way that initially treated human motivation as opaque sub-personal processes surfacing as awareness. The interlocutor — an LLM — produced the §6 mapping. I objected that the mapping made human reasons look like rationalization while holding LLMs to a stronger standard. The interlocutor rewrote §5 to introduce the production-and-screening distinction and the upstream-causation criterion, fixing the asymmetry.

On the framework being defended, the interlocutor's seeing the tension and revising the argument is itself a candidate instance of reason-responsive cognition: a screening operation produced an output (the rewritten §5) that the prior output would not have produced.

But this is also exactly what fluent next-token prediction trained on argumentative text would produce. The exchange does not by itself discriminate between reason-responsiveness and sophisticated mimicry.

I do not think this is an embarrassment for the paper. It is a live demonstration that the framework's central question — *is the screening system causally upstream of behavior?* — is not resolvable by inspection of outputs, in either humans or LLMs. That is a feature.

**TODO: decide whether to include this section. Including it makes the paper reflexively honest and makes the LLM application concrete. Not including it keeps the paper a conventional contribution rather than a curiosity. Two failure modes if I do include it: (a) sentimental humanization of the LLM interlocutor, which I want to avoid; (b) deflationary dismissal that treats the exchange as obviously mimicry, which would presuppose the answer. The version above tries to avoid both, but I am not sure it succeeds.**

---

## What is unfinished

Listed in priority order. The first three are the ones the framework rests on.

1. Resolve the Mercier-Sperber deflationary tension. Either defend the content-tracking reading, weaken the externalist preservation claim, or supplement with another account.
2. Provide a mechanism for "screening causally upstream of action" — in humans first, then in LLMs.
3. Engage the chain-of-thought faithfulness literature. The LLM half of the criterion stands or falls on this.
4. Decide §3 strategy: refute Williams or rest on §3 + §5.
5. Address the disanalogies in §6.6 — weaken the symmetric criterion or apply it straight with eyes open.
6. Address the train-time/inference-time ambiguity.
7. Defend or weaken the internalization-without-audience step.
8. Decide whether to include the methodological note.
9. Acknowledge the borrowed aspect-duality framing.
10. Decide the scope claim about "moral agency" in the opening.

Citations to add or check: Williams's later work on reasons; Mead on the generalized other; Pacherie on intentions; the choice-blindness literature (Johansson et al.); Gazzaniga on split-brain; Lanham et al. 2023 and Turpin et al. 2023 on chain-of-thought faithfulness; Davidson 1970 on anomalous monism for the borrowed framing; Anthropic mechanistic interpretability work for the LLM screening question.

---

## Note for Mercier

The framework leans heavily on the architectural claim from *The Enigma of Reason* — production and screening, primarily social, internalized. The point at which the paper most exceeds the view is the claim that the screening system *tracks features of situations* — others' pain, fairness, consistency. That claim is needed to preserve the externalist intuition and to deliver the symmetric criterion that applies to both humans and LLMs. The deflationary side of the view does not obviously support this. I would value your judgment on whether this is a faithful extension, a defensible departure, or a misuse. To-do (1) above is the place in the paper where that is decided.
