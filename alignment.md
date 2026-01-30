# Command: alignment

Tests whether your organization is aligned on core positioning.

## Usage
```
# Generate survey
/alignment

# Analyze responses
/alignment analyze
```

## What It Does

### Mode 1: Generate Survey
Outputs Fletch's 4 positioning questions as a survey template to send to stakeholders. Each person answers independently without seeing others' responses.

### Mode 2: Analyze Responses
When given stakeholder responses:
1. Measures alignment percentage for each question
2. Identifies misalignment patterns
3. Maps to Dunford's components
4. Diagnoses root cause
5. Recommends alignment exercises

## Alignment Scoring
- 80-100%: Strong alignment
- 60-79%: Moderate alignment
- 40-59%: Weak alignment
- Below 40%: Misalignment (critical problem)

## Example Output — Mode 1 (Generate)

```
POSITIONING ALIGNMENT SURVEY
════════════════════════════

Send these 4 questions to each stakeholder independently.
They should answer in 1-2 sentences without conferring.

Recommended participants: CEO, VP Marketing, Head of Sales,
Product Lead, Customer Success Lead

───────────────────────────────────────
QUESTION 1: What is our product?
Define the product category or primary use case.
(e.g., "A project management tool" or "An automated testing platform")

QUESTION 2: Who is it for?
Name the target company type, department, or persona.
(e.g., "Engineering teams at mid-market SaaS companies")

QUESTION 3: What does it replace?
Name the competitive alternative or current behavior.
(e.g., "Replaces manual spreadsheet tracking" or "Replaces Jira")

QUESTION 4: Why is it better?
State the primary differentiation in one sentence.
(e.g., "50% faster setup with no-code configuration")
───────────────────────────────────────

Collect responses, then run:
/alignment analyze
```

## Example Output — Mode 2 (Analyze)

```
POSITIONING ALIGNMENT ANALYSIS
═══════════════════════════════

Overall Alignment: X% — [interpretation]

───────────────────────────────────────
Q1: "What is our product?"
───────────────────────────────────────
Alignment: X%

• CEO: "[response]"
• VP Marketing: "[response]"
• Head of Sales: "[response]"
• Product Lead: "[response]"

Assessment: [Aligned / Divergent on category vs. use-case framing]
Dunford component affected: Market Category

───────────────────────────────────────
Q2: "Who is it for?"
───────────────────────────────────────
Alignment: X%

[same structure]

Assessment: [Aligned / Divergent on persona vs. company type]
Dunford component affected: Target Customers

───────────────────────────────────────
Q3: "What does it replace?"
───────────────────────────────────────
Alignment: X%

[same structure]

Assessment: [Aligned / Divergent on named competitor vs. behavior]
Dunford component affected: Competitive Alternatives

───────────────────────────────────────
Q4: "Why is it better?"
───────────────────────────────────────
Alignment: X%

[same structure]

Assessment: [Aligned / Divergent on feature vs. outcome framing]
Dunford component affected: Unique Attributes + Value

═══════════════════════════════════════
ROOT CAUSE DIAGNOSIS
═══════════════════════════════════════

[Analysis of where and why the team diverges]

═══════════════════════════════════════
RECOMMENDED EXERCISES
═══════════════════════════════════════

1. [Specific alignment exercise with instructions]
2. [Follow-up action]
```
