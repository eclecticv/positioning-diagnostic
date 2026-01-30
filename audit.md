# Command: audit

Comprehensive 100-point positioning audit across all framework dimensions.

## Usage
```
/audit <url>
```

## What It Does

1. Analyzes homepage against Dunford's 5 components
2. Evaluates Fletch's 4 positioning questions
3. Tests Moore's positioning statement template (can every slot be filled?)
4. Scores 100-point rubric (Clarity/Differentiation/Value/Execution)
5. Identifies framework violations
6. Maps symptoms to likely positioning causes
7. Recommends prioritized fixes

## Output Structure

- Overall Score: X/100
- Dunford's 5 Components breakdown
- Fletch's 4 Questions (answered or unanswerable)
- Moore's Template Test (which slots are empty?)
- Detailed scoring across all dimensions
- Framework violations detected
- Predicted business symptoms
- Prioritized recommendations (highest priority, quick wins, strategic work)

## Example Output

```
POSITIONING AUDIT: [Company Name]
URL: [url]
Overall Score: X/100 — [interpretation]

═══════════════════════════════════════
SCORING BREAKDOWN
═══════════════════════════════════════

| Dimension          | Score | Max |
|--------------------|-------|-----|
| Clarity            | X     | 25  |
| Differentiation    | X     | 25  |
| Value Proposition  | X     | 25  |
| Execution          | X     | 25  |

CLARITY (X/25):
• Product identity (5-sec test): X/10 - [assessment]
• Target audience stated: X/5 - [assessment]
• Problem articulated: X/5 - [assessment]
• Jargon-free language: X/5 - [assessment]

DIFFERENTIATION (X/25):
• Competitive alternative acknowledged: X/10 - [assessment]
• "Why better" articulated: X/10 - [assessment]
• Proof of differentiation: X/5 - [assessment]

VALUE PROPOSITION (X/25):
• Appeal: X/7 - [assessment]
• Exclusivity: X/6 - [assessment]
• Clarity: X/6 - [assessment]
• Credibility: X/6 - [assessment]

EXECUTION (X/25):
• Above-the-fold completeness: X/8 - [assessment]
• Visual-message alignment: X/5 - [assessment]
• CTA clarity: X/5 - [assessment]
• Social proof: X/7 - [assessment]

═══════════════════════════════════════
DUNFORD'S 5-COMPONENT CANVAS
═══════════════════════════════════════

| Component              | Status    | Evidence |
|------------------------|-----------|----------|
| Competitive Alternatives | ✅/⚠️/✗ | [evidence] |
| Unique Attributes      | ✅/⚠️/✗   | [evidence] |
| Value                  | ✅/⚠️/✗   | [evidence] |
| Target Customers       | ✅/⚠️/✗   | [evidence] |
| Market Category        | ✅/⚠️/✗   | [evidence] |

═══════════════════════════════════════
FLETCH'S 4 QUESTIONS
═══════════════════════════════════════

| Question             | Answer              | Grade |
|----------------------|---------------------|-------|
| What is it?          | [answer or "unclear"] | ✅/⚠️/✗ |
| Who is it for?       | [answer or "unclear"] | ✅/⚠️/✗ |
| What does it replace?| [answer or "unclear"] | ✅/⚠️/✗ |
| Why is it better?    | [answer or "unclear"] | ✅/⚠️/✗ |

═══════════════════════════════════════
MOORE'S POSITIONING STATEMENT TEST
═══════════════════════════════════════

"For [target customer] who [need], [product] is a [category]
that [benefit]. Unlike [alternative], [product] [differentiator]."

Filled slots: X/6
Empty slots: [list which are missing]

═══════════════════════════════════════
FRAMEWORK VIOLATIONS
═══════════════════════════════════════

[List of violations with severity and evidence]

═══════════════════════════════════════
PREDICTED BUSINESS SYMPTOMS
═══════════════════════════════════════

1. [Symptom] — caused by [positioning gap]
2. [Symptom] — caused by [positioning gap]

═══════════════════════════════════════
RECOMMENDATIONS (PRIORITIZED)
═══════════════════════════════════════

HIGHEST PRIORITY:
1. [recommendation]

QUICK WINS:
2. [recommendation]

STRATEGIC WORK:
3. [recommendation]
```
