# Command: export

Generates a downloadable 1-page markdown positioning audit report.

## Usage
```
/export <url>
```

## What It Does

1. Fetches homepage content and runs a full positioning analysis
2. Formats results as structured 1-page markdown
3. Includes scores, findings, and recommendations
4. Saves to current directory as `[company]-positioning-export.md`
5. Optimized for sharing with stakeholders

## Notes
- Can run standalone — performs the full analysis internally
- If an `/audit` was already run in the same session, builds on that context

## Output File Structure
- Executive Summary
- Scoring Breakdown (table format)
- Key Findings (top 3 weakest components)
- Framework Violations
- Predicted Business Symptoms
- Recommendations (prioritized)
- Next Steps

## Example Output

```
# Positioning Audit Report: [Company]

**Date:** [date]
**Analyzed URL:** [url]
**Frameworks:** Dunford · Fletch PMM · Moore · MECLABS · Ries/Trout

---

## Executive Summary

[2-3 sentence summary of positioning strength, key differentiator,
and primary weakness.]

**Overall Score: X/100** — [interpretation]

---

## Scoring Breakdown

| Dimension | Score | Max | Details |
|-----------|-------|-----|---------|
| Clarity | X | 25 | |
| Differentiation | X | 25 | |
| Value Proposition | X | 25 | |
| Execution | X | 25 | |

[... full breakdown with sub-scores ...]

## Recommendations (Prioritized)

### Highest Priority
1. [recommendation]

### Quick Wins
2. [recommendation]

### Strategic Work
3. [recommendation]
```

## Use Cases
- Sharing with leadership/stakeholders
- Documenting positioning state before/after changes
- Creating paper trail for positioning decisions
- Onboarding new marketing team members
