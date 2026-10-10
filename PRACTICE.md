# The practice of shaping

**Working proposal, v0.1 — 10 October 2026**

Shaping is an activity, not a specific app, model architecture, or training technique. It turns human intention into progressively more reliable machine-intelligence behaviour.

## Seven movements

| Movement | The shaper does | Evidence or artefact |
| --- | --- | --- |
| **Intend** | Names the capability or behaviour they want | Goal, constraints, success criteria |
| **Demonstrate** | Shows what good and bad behaviour look like | Examples, counterexamples, preferences |
| **Experiment** | Changes something that might affect behaviour | Experiment record, configuration, intervention |
| **Observe** | Interacts with the result | Traces, outputs, feedback |
| **Evaluate** | Tests whether the result approaches the intention | Comparisons, failure cases, regressions |
| **Refine** | Revises direction or implementation | Change and rationale |
| **Preserve** | Saves what was learned and built | Versioned Creation and evidence |

These movements can overlap and recur. The work is experimental rather than strictly linear.

## An example: shaping a study companion

Imagine a person wants an AI study companion that **explains a physics concept clearly, identifies misunderstandings without shaming students, and never pretends to know whether a student truly understands**.

The shaper:

1. Describes the intended teaching behaviour and its boundaries.
2. Supplies examples of helpful explanations and unhelpful responses.
3. Tests the companion against easy questions, misconceptions, and ambiguous answers.
4. Changes its prompting, model choice, examples, tools, or training, as appropriate.
5. Looks not just at successful explanations but at situations where it confidently misjudges understanding.
6. Records what improved, which regressions appeared, and what remains unknown.
7. Preserves the evolving study companion as a **Creation**, with versions and evidence.

The shaper may know nothing about gradient descent. The infrastructure might still use sophisticated model-engineering techniques. Making the activity accessible does **not** remove the need for technical quality, privacy, or safety.

## An example: shaping an evaluation specialist

A more technical shaper wants a model or agent to identify security-sensitive support requests without misrouting them.

An intervention increases the number of correctly handled examples but introduces one severe misroute. The shaper should be able to **reject** the change despite the headline improvement, preserve the record of the failure, and try a different intervention.

Shaping concerns *what an intelligence is becoming*, including what it must **not** become.

This is a hypothetical illustration, not a benchmark claim.

## The Creation record

A practical Creation could retain:

- **Identity:** title, description, creator, collaborators, versions.
- **Intention:** desired capabilities, target context, success criteria.
- **Material:** examples, demonstrations, permitted datasets, preferences.
- **Composition:** models, weights or adapters if any, prompts, tools, routing, retrieval, configuration.
- **Boundaries:** disallowed behaviours, human oversight requirements, privacy conditions.
- **Evidence:** tests, observations, human evaluations, failures, regressions, uncertainty.
- **Provenance:** origins, licences, dependencies, experiments, change history.
- **Distribution:** exportable artefacts, deployment requirements, limitations.

Not every Creation needs every field. No universal schema is established in this version.

## What makes shaping creative?

The creative decisions are not only technical: what to value, which examples to present, which behaviours matter, what trade-offs are acceptable, and when a result feels faithful to its intended purpose.

That subjective judgment can guide shaping, but it does not replace empirical checks. The creator's question — *Is this becoming what I had in mind?* — should coexist with the engineer's question — *Did this change work?*

## What shaping is not

Shaping does not require training a new neural network for each Creation. A system may be shaped through configuration and composition without updating model parameters. Nor does every conversation or prompt automatically count as a sustained creative practice.

The point is **intentional, iterative development of intelligent behaviour into a persistent work**.

## Questions to test

- Can novices form meaningful Creations without requiring them to learn a model-engineering toolchain?
- Does preserving evaluation evidence change how people refine their Creations?
- Can creators share Creations with reproducible boundaries and provenance?
- Which parts of a Creation should remain portable between models and providers?
- What must be visible to prevent a persuasive demonstration from being mistaken for a reliable capability?

These are questions for prototypes and research, not settled promises.
