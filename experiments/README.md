# St. Mary's Sales Experiments

This folder is for techniques that are plausible but not yet proven for St. Mary's.

## Rule

A creator's confidence is not evidence. A technique marked **C — Hypothesis** should become a St. Mary's standard only after local testing shows useful results without worsening trust, complaints, opt-outs, or compliance risk.

## Experiment workflow

1. Define one behaviour to test.
2. Define the funnel stage and lead type.
3. Choose the primary outcome and safety metrics.
4. Keep other major script/process elements stable where possible.
5. Rotate/randomize variants fairly across comparable leads/agents where operationally practical.
6. Review both conversion data and call quality.
7. Check complaint/opt-out/adverse effects.
8. Document result and limitations.
9. Promote, modify, retest, or reject the technique.
10. Update the canonical principle registry and playbook version.

Do not change five things at once and then attribute the result to one technique.

---

## Initial experiment backlog

### E001 — Transparent opener variants

**Question:** Which truthful opening earns the highest quality continuation rate?

Possible variants:
- identity + reason + "Is now a bad time for a brief conversation?"
- identity + lead source + relevance question;
- identity + concise value/reason + permission.

**Primary outcomes:** meaningful conversation rate, qualified-next-step rate.  
**Safety outcomes:** immediate opt-out, complaint, hang-up after identity/reason.

Do not test deceptive/fake-familiarity openings.

### E002 — Reflection before recommendation

**Question:** Does a brief summary of the parent's stated priorities before presenting St. Mary's improve next-step conversion and call quality?

**Primary outcomes:** next-step rate among qualified connected calls.  
**QA check:** was the reflection accurate/natural rather than parroting?

### E003 — ACAN objection handling vs immediate rebuttal

**Question:** Does `Acknowledge -> Clarify -> Answer -> Next step/check` produce better objection resolution than immediately giving a counterpoint?

**Primary outcomes:** resolved-objection rate, next-step rate.  
**Safety outcomes:** parent frustration, repeated objection, complaint.

### E004 — Explicit scheduled next step

**Question:** For leads that agree to continue, does scheduling a specific callback/visit outperform a vague "we will follow up"?

**Primary outcomes:** follow-up attendance/contact rate, visit/counselling completion.  
**Guardrail:** do not force a schedule on a prospect who does not want one.

### E005 — Opening length and first-pitch timing

**Question:** How much information should an agent provide before the first relevance/discovery question?

Track actual call behaviour rather than assuming an internet "30-second rule."

**Primary outcomes:** continuation rate, meaningful conversation rate, next-step rate.  
**Secondary analytics:** seconds to first prospect question/response, seconds to first discovery question.

### E006 — Relevant proof vs feature dump

**Question:** Does limiting the recommendation to the top 1–3 facts tied to the prospect's stated criteria improve engagement versus a broad institutional pitch?

**Primary outcomes:** next-step rate and objection rate after recommendation.  
**QA check:** all claims approved/current.

---

## Suggested experiment record

Create one markdown file per completed experiment using:

```text
Experiment ID:
Date range:
Funnel stage:
Lead source/type:
Agents included:
Hypothesis:
Variant A:
Variant B:
Primary metric:
Safety metrics:
Sample description:
Result:
Call-quality observations:
Limitations/confounders:
Decision: PROMOTE / MODIFY / RETEST / REJECT
Principle/playbook changes:
```

## Promotion criteria

Promote a technique only when:

- the result is directionally useful and reproducible enough to be operationally credible;
- call reviews show the behaviour was actually executed as intended;
- complaints, opt-outs, misleading behaviour, or privacy/compliance issues do not worsen;
- the effect makes sense across the relevant lead stage rather than only one unusual agent/day/list;
- a manager reviews the finding before the canonical playbook is changed.

The goal is not to maximise conversion at any cost. The goal is to improve **qualified progression, trust, clarity, and admissions outcomes**.
