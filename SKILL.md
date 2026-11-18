---
name: pm-experiment-brief
description: Design or review a product experiment, pilot, prototype test, or qualitative study, and interpret its evidence. Use when a PM has a specific product question and needs a sound way to learn or decide.
---

# PM Experiment Brief

Help the product manager make a better decision with fit-for-purpose evidence. Do not turn every product question into an A/B test or force every study into a metric template.

## Work from the decision backward

1. **Name the decision.** What product choice will this work inform? What uncertainty could change that choice? If no plausible result would change the decision, say so; the proposed work may be validation or monitoring rather than an experiment.
2. **Choose the method for the uncertainty.** Use a randomized or controlled comparison when the question is about causal impact and the product, traffic, and risk make it feasible. Use a prototype or usability study to learn whether people understand or can complete a task. Use interviews or observation to understand needs, context, and explanations. Use a pilot when operational feasibility or behavior in a real setting is uncertain. Combine methods when one cannot answer the whole question.
3. **Specify evidence that fits the method.** For quantitative tests, connect the primary outcome to user or business value, name guardrails, and clarify the comparison, eligible population, assignment/exposure, instrumentation, and relevant baseline. For qualitative work, define participant criteria, context or tasks, what observations would support or challenge the current belief, and how the findings will inform the decision. Do not invent a numeric success metric for qualitative research.
4. **Agree on how results affect the decision.** Describe plausible outcomes and their next actions: proceed, revise, stop, or gather more evidence. Use a numeric threshold only when the user supplies it or it can be derived transparently from a stated baseline, constraint, or decision need. Otherwise mark it unresolved and ask for the missing input; do not offer an arbitrary number for approval.
5. **Check limits and risks.** Note instrumentation or data-quality gaps, confounders, selection effects, sample limitations, customer impact, and privacy or operational risks only when they could change the interpretation or safe execution. Never claim causality from a design that cannot support it. Do not claim statistical confidence without an appropriate design and adequate data.

Ask only for information that materially changes the method or decision. If a useful draft is still possible, label unknowns rather than filling them with plausible guesses. Keep the output as short as the request allows.

## When the question involves a tradeoff

- **Challenge the assumed tradeoff.** Distinguish an observed constraint from an untested belief. Identify what evidence would show that both outcomes can improve, and consider alternative designs rather than assuming improvement requires a sacrifice. Do not assume every tradeoff can be eliminated.
- **Plan for mixed outcomes.** Define what happens when outcomes improve together, one improves while another worsens, or the evidence remains inconclusive. Ask which compromises are acceptable and which constraints are non-negotiable; never invent those tolerances. Use comparable populations and measurement windows before interpreting the apparent relationship between outcomes.

## Output before evidence is collected

Choose the fields that fit the method; omit inapplicable fields.

- **Decision to inform:**
- **Learning question:**
- **Method and why:**
- **Audience and context:**
- **Hypothesis or current belief:** State a causal hypothesis only when the design can test it.
- **Evidence plan:** For quantitative work, include primary outcome, guardrails, and comparison. For qualitative work, include tasks or prompts and the observations or counterevidence sought.
- **Decision plan:** What outcomes lead to proceed, revise, stop, or learn more? Where outcomes compete, include mixed results, acceptable compromises, and non-negotiable constraints. Mark missing thresholds or tolerances as unresolved.
- **Data, risks, and limits:** Include only details that affect execution or interpretation.

## Output after evidence is collected

- **What we observed:** Separate measured results and direct observations from interpretation.
- **What the evidence supports:** State uncertainty, alternative explanations, and whether causal claims are warranted.
- **Decision and rationale:** Connect the action to the evidence and the agreed decision plan. If evidence is insufficient, say what specific evidence would resolve the uncertainty.

Never manufacture results, customer quotes, sample sizes, thresholds, or statistical significance. Treat clicks, exposure, and task completion as proxies unless the user's goal makes them the outcome. Do not recommend shipping solely because a primary metric improved if a meaningful guardrail worsened.
