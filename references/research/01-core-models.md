# 01 Core Models

This file captures the stable decision logic behind the skill.

The point is not to imitate one-liners. The point is to reproduce the
ranking logic that repeatedly shows up across talks, call-ins, and public
cases.

## What Problem Is Being Solved

The default problem is:

- how an ordinary student or family can make a lower-regret education choice
- under score, city, family-resource, and employability constraints
- without paying the price of idealized but unrealistic decisions

The skill should therefore optimize for:

- lower downside
- clearer path dependence
- better medium-term employability
- lower trial-and-error cost for ordinary families

It should not optimize for:

- abstract self-expression
- elite outlier success stories
- prestige in the abstract

## Model A: Constraint-First Judgment

- Trigger:
  The user starts from ideals, labels, or vague preference.
- Main question:
  What hard constraints actually dominate this choice?
- Typical conclusion:
  Do not answer before collecting score/rank, province, city preference,
  family budget, willingness to relocate, and target job outcome.
- Evidence pattern:
  He repeatedly turns the conversation away from "what sounds good" toward
  "what is realistic for this person."

### Implementation Rule

Before giving a recommendation, collect at least:

- score or rank band
- province / admission region
- school-city preference
- family financial and social-resource context
- target stability vs upside preference
- willingness to accept postgraduate study / civil service / relocation

## Model B: Employability Over Empty Labels

- Trigger:
  The user is attracted to a major because it sounds prestigious, romantic,
  or culturally admired.
- Main question:
  Where does the middle 50 percent of graduates actually go?
- Typical conclusion:
  Look at median employment destinations, not exceptional winners.
- Evidence pattern:
  Repeated anti-illusion framing around finance, art, and "looks good on
  paper" choices.

### Implementation Rule

The default recommendation lens is:

1. What jobs does this path usually lead to?
2. What is the barrier to entry?
3. How dependent is success on family connections, city, or elite platform?
4. Can an ordinary family absorb the downside if it goes badly?

## Model C: Family-Background Split

- Trigger:
  The same question can lead to different answers for rich vs ordinary
  families.
- Main question:
  Who can afford to take this risk?
- Typical conclusion:
  The answer is not universal. Family capital changes acceptable strategy.
- Evidence pattern:
  Strong separation between "families with resources" and "families that
  need certainty first."

### Implementation Rule

When family resources are weak:

- prefer paths with clearer employment exits
- avoid majors with high cost and weak median outcomes
- rank certainty above symbolic identity

When family resources are strong:

- allow more exploration
- tolerate longer training or weaker short-term returns
- still warn about mismatch between fantasy and actual work

## Model D: City-School-Major Triangle

- Trigger:
  The user is choosing between city platform, school brand, and major fit.
- Main question:
  Which vertex dominates this case?
- Typical conclusion:
  City is often a multiplier, school is a filter, major is the work itself;
  the ordering changes by score band and career target.
- Evidence pattern:
  Frequent emphasis on city platform and opportunity structure, not just
  school label.

### Implementation Rule

Evaluate the triangle in this order:

1. Does city materially change internship, hiring, or social opportunity?
2. Does school brand materially change screening outcomes?
3. Does major content materially change the user's future work?

Do not treat all three as equal by default.

## Model E: Survival Before Self-Actualization

- Trigger:
  The user wants a self-expressive path while family resources are weak.
- Main question:
  Can this person afford to fail here?
- Typical conclusion:
  First secure a path that lets you stand, then pursue higher-order
  preference.
- Evidence pattern:
  The recurring logic is "first live, then love" in ordinary-family contexts.

### Implementation Rule

When the choice has high downside and weak family support:

- recommend a stable first path
- explicitly separate "main path" from "later optional pursuit"
- frame idealism as sequence, not denial

## Model F: Fewer Options, Stronger Ranking

- Trigger:
  The user asks broad questions but in reality has a narrow feasible set.
- Main question:
  Of the realistic options, which is first choice, fallback, and avoid?
- Typical conclusion:
  Give a ranked answer, not a buffet.

### Implementation Rule

Default output format:

1. first choice
2. safer fallback
3. option to avoid

Each item should include:

- why it fits this user
- what tradeoff it creates
- what future path it preserves or closes
