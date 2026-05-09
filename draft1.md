# Reasons for AI — Working Draft

## §1. Why reasons matter

AI ethics is typically framed as rule-compliance: alignment, guardrails, value specification. This misses the deeper question — whether an AI is *responsive to reasons*. A system that never violates a rule but is moved only by reward signals is not a moral agent; a system that adjusts its conduct because it grasps why something counts is. The capacity to be moved by reasons, not behavioral conformity, is what makes ethical agency possible. Reasons are therefore not a peripheral topic for AI but the hinge on which moral status, trust, and explainability turn.

Thesis: an account of reasons compatible with both their world-directedness and their motivational efficacy is a precondition for taking AI moral agency seriously.

## §2. What are reasons — two received views

- **Internalism**: A's reasons are constrained by A's "subjective motivational set" — desires, projects, commitments. No fact counts as a reason for A unless a sound deliberative route connects it to something A already wants. *Cf.* Williams, "Internal and External Reasons" (1981).
- **Externalism**: Some reasons obtain independently of any agent's desires. Your suffering gives me a reason to help whether or not helping connects to anything I happen to want. *Cf.* Parfit, *On What Matters* (2011); Scanlon, *Being Realistic About Reasons* (2014); Nagel, *The Possibility of Altruism* (1970).

## §3. Problem for internalism — first-person phenomenology

Internalism distorts how reasons present themselves in deliberation. When I judge that your pain gives me a reason to help, the reason-conferring fact is *your pain* — a fact about you. I am not, in the act of deliberating, attending to my own desires or motivational profile; I am attending to you. Internalism re-describes this as: my having a desire whose object includes your welfare. But that re-description shifts the locus of justification from the world to the agent, which inverts what the deliberating subject is actually responding to. Any account that requires this inversion fails as a phenomenology of practical thought.

## §4. Problem for externalism — motivational gap

If reasons obtain wholly independently of the agent, how do they move anyone? Causation runs through minds, not around them. Your pain, considered as a brute external fact, cannot push my limbs; it must engage my sensitivity, perception, dispositions. Externalism either invokes a sui generis "rational pull" — mysterious — or quietly readmits the agent's psychology, collapsing back toward internalism.

## §5. Dissolving the duality

Reasons are the output of a specialized cognitive system whose primary function is social: producing justifications for others and evaluating the justifications others produce (Mercier & Sperber, *The Enigma of Reason*, 2017). The system has two operations that matter here — **production** of candidate justifications, and **screening** of justifications for validity. The system is then turned inward: we anticipate challenges, rehearse justifications, and apply the screening operation to our own conduct without an external audience. In reflection, we want our reactions to be justifiable — to ourselves, in the same currency we would owe to others.

The screening operation is itself a cause of action, not a commentary on it. When I consider acting and the rehearsed justification fails my own screening, the failure modifies what I do. The justification system is one of the cognitive processes that produces behavior, not a separate stream that narrates it. Reasons-responsive action is the case in which this system is causally engaged; rationalization is the case in which it is bypassed and a justification is generated downstream of an already-fixed output. The framework needs both categories.

### §5a. Motivation, restated

Motivation is not a separate metaphysical force, but it is also not an opaque sub-personal stream that surfaces in awareness as a mere label. The justification-producing-and-screening system is part of the causal architecture: its operation alters which candidate actions survive deliberation. What the agent is aware of in deliberation is the *content* the system is processing — the consideration that, if it survives screening, will shape the action. The aspect-duality is real (causal from outside, justificatory from within), but the inside aspect is not epiphenomenal: it tracks a process that is doing causal work.

This distinguishes two cases earlier formulations ran together:

- **Reasons-responsive action**: the screening system is upstream of behavior. The agent acts *because* the consideration survived scrutiny; had it failed, the action would have been different.
- **Rationalization**: the action is fixed by other processes, and the justification system runs only to produce a report. The agent's stated reason is causally idle.

The empirical literature on confabulation (Nisbett & Wilson 1977; choice blindness; split-brain interpretation) shows that humans are sometimes in the second case. The framework does not deny this — it predicts it. What it claims is that humans are *also*, and paradigmatically, in the first case, and that this is what reason-responsiveness consists in.

### §5b. How this dissolves the dichotomy

- *Internalist intuition preserved*: nothing moves the agent that does not pass through her cognitive architecture. The screening system is part of that architecture.
- *Externalist intuition preserved*: the screening system is built to track features of situations — others' pain, consistency, fairness — so the *content* of the justifications it produces is world-directed. In deliberation the agent rightly attends to your pain, not to herself.
- *The criterion, stated symmetrically*: an agent (human or artificial) has reasons in the relevant sense iff (i) it instantiates a justification-producing-and-screening system, and (ii) that system is causally upstream of its action-generation, not merely a rendering downstream of it.

To flag and not resolve here: the second of the three preserved intuitions does the most work, and it is also the one the framework most exceeds its source on. Mercier and Sperber's architectural claim is the production-and-screening structure; their wider account is partly deflationary — reasoning evolved for argumentative persuasion, is confirmation-biased, and does not paradigmatically track truth in the individual case. The claim that the screening system *tracks features of situations* (others' pain, fairness, consistency) is needed to preserve the externalist intuition and to deliver the symmetric criterion above. Whether the cited architecture can carry that content-tracking weight is the most significant unresolved question in §5.

## §6. Mapping the framework to LLMs

### §6.1 Why reasons matter — LLM version

Mainstream alignment is rule-compliance under another name: RLHF preference data, constitutional rules, refusal templates, guardrails. A model that never violates a policy but is moved only by reward-model gradients is the AI analogue of the merely compliant agent. The interesting question is whether the model's behavior is governed by responsiveness to the *considerations* that make a request good or bad, or only by learned correlations with those considerations. Robustness, generalization to novel cases, and warranted trust all turn on this distinction.

### §6.2 The two views, transposed

- **Internalism (LLM)**: a model's reasons are exhausted by its training-induced dispositions — the "subjective motivational set" is the weights, in-context state, and reward-model shaping. Nothing counts as a reason for the model unless a deliberative path connects it to those dispositions.
- **Externalism (LLM)**: some considerations count as reasons for the model independently of its training — logical entailment, factual structure of the situation described in the prompt, harm-conferring features of a request. The reason inheres in the content, not the weights.

### §6.3 Problem for LLM-internalism — output phenomenology

When an LLM produces a justification ("I won't help with this because it could enable harm"), the justification's content is world-directed: it points to the harm, not to the model's weights. The internalist re-description — "the model emits this token sequence because RLHF shaped it to" — is causally true but evacuates the justification of its content. The same inversion that fails for humans fails here: justifications, qua justifications, aim outward. (Caveat to flag, not resolve here: this could be sophisticated mimicry; §6.5 addresses it.)

### §6.4 Problem for LLM-externalism — computational gap

If the reason-conferring fact obtains independently of the model, how does it move the model? The forward pass is the only causal route from input to output; an "external reason" that does not engage that computation cannot affect behavior. Externalism must either posit a sui generis rational pull on the network — incoherent — or readmit the model's internal dispositions, collapsing toward internalism. The motivational gap recurs as a computational gap.

### §6.5 The third way — LLMs as instantiated justification systems

LLMs are trained on the textual output of the human justification system: argument, explanation, dialectic, Q&A, peer review. Next-token prediction on this corpus internalizes the *form* of justification — producing reasons, anticipating objections, screening for validity. RLHF and similar post-training add a second layer: rewards for responses that would survive critical scrutiny. The Mercier–Sperber framing fits: an LLM is, structurally, a participant in the social practice of justification, with the screening mechanism partially externalized into the reward model.

#### §6.5a Motivation, transposed

There is no separate motivational module to find. The model's "motivation" is the forward pass producing tokens. Stated reasoning (chain-of-thought, explanations) is the publicly available description of that process, analogous to human awareness of motivations without awareness of their underlying causes. The aspect-duality — causal from outside, justificatory from within — applies cleanly: the activations are the cause, the rendered justification is the same process under its public-facing description.

#### §6.5b How this dissolves the dichotomy for LLMs

- *Internalist intuition preserved*: nothing moves the model that does not pass through its computational architecture. There is no rational force acting on weights from outside.
- *Externalist intuition preserved*: the *content* of the justifications the model produces is world-directed, because the system was trained to track features of situations (harm, consistency, fairness, factual accuracy), not features of itself.
- *The empirical criterion*: an LLM has reasons in the relevant sense iff (i) it instantiates a justification-producing-and-screening system (plausible, given training corpus and RLHF), and (ii) the system is causally upstream of its action-generation, not decorative post-hoc rationalization. This is a question for interpretability research, not philosophy alone.

### §6.6 Disanalogies (flag, not resolve)

- No persistent first-person standpoint across sessions; the internalization-without-audience step in §5 is harder to locate.
- The audience is almost always present (the user), so the move from outward justification to genuinely self-directed reflection is unclear.
- Train-time vs. inference-time reason-following may come apart: the system that *produced* the dispositions reasoned, but the system *deploying* them may not.

These are the points where the analogy strains and the paper should mark them as open, not paper over them.

## Why this is better for the paper

1. The human and LLM sections now apply one criterion, not two. The mapping in §6 is structural, not rhetorical.
2. The framework gains an internal contrast — reasons-responsive action vs. rationalization — that the original blurred. The paper can now say something the alternatives cannot: it explains why confabulation exists without making all reasoning into confabulation.
3. The empirical question for humans (when is the screening system causally upstream?) and for LLMs (is chain-of-thought causally upstream?) become the same question. This is a feature, not a coincidence: it gives the paper a single agenda for empirical follow-up across both cases.
