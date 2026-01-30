# Command: compare

Side-by-side competitive positioning comparison of two homepages.

## Usage
```
/compare <url1> <url2>
```

## What It Does

1. Fetches both homepages
2. Runs a `/diagnose`-level analysis on each (5-second test + MECLABS)
3. Compares across all positioning dimensions
4. Identifies where each site is stronger or weaker
5. Highlights positioning gaps and overlaps
6. Recommends differentiation opportunities

## When to Use

- Competitive analysis before a positioning rework
- Comparing your site against a direct competitor
- Evaluating two versions of your own site (e.g., before/after)
- Reviewing acquisition targets or partnership candidates

## Example Output

```
POSITIONING COMPARISON
═══════════════════════════════════════

Site A: [Company A] — [url1]
Site B: [Company B] — [url2]

═══════════════════════════════════════
5-SECOND TEST
═══════════════════════════════════════

| Dimension       | Site A | Site B |
|-----------------|--------|--------|
| What they do    | ✅/✗   | ✅/✗   |
| Who it's for    | ✅/✗   | ✅/✗   |
| Why choose them | ✅/✗   | ✅/✗   |

═══════════════════════════════════════
MECLABS COMPARISON
═══════════════════════════════════════

| Factor      | Site A | Site B | Edge    |
|-------------|--------|--------|---------|
| Appeal      | X/5    | X/5    | A / B / Tie |
| Exclusivity | X/5    | X/5    | A / B / Tie |
| Clarity     | X/5    | X/5    | A / B / Tie |
| Credibility | X/5    | X/5    | A / B / Tie |
| **Total**   | X/20   | X/20   | A / B / Tie |

═══════════════════════════════════════
FLETCH'S 4 QUESTIONS
═══════════════════════════════════════

| Question             | Site A            | Site B            |
|----------------------|-------------------|-------------------|
| What is it?          | [answer/unclear]  | [answer/unclear]  |
| Who is it for?       | [answer/unclear]  | [answer/unclear]  |
| What does it replace?| [answer/unclear]  | [answer/unclear]  |
| Why is it better?    | [answer/unclear]  | [answer/unclear]  |

═══════════════════════════════════════
POSITIONING OVERLAP
═══════════════════════════════════════

Shared claims: [list any claims both sites make — signals
weak differentiation for both]

Unique to Site A: [what A claims that B doesn't]
Unique to Site B: [what B claims that A doesn't]

═══════════════════════════════════════
HEAD-TO-HEAD VERDICT
═══════════════════════════════════════

Stronger positioning: [Site A / Site B]
Key advantage: [1 sentence on what gives the winner the edge]

Site A's biggest gap vs. B: [specific weakness]
Site B's biggest gap vs. A: [specific weakness]

═══════════════════════════════════════
DIFFERENTIATION OPPORTUNITIES
═══════════════════════════════════════

For Site A:
1. [Opportunity to differentiate against B]

For Site B:
1. [Opportunity to differentiate against A]
```
