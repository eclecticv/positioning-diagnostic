# Quick Start Guide

## Installation

```bash
# 1. Create directory
mkdir -p ~/.claude/skills/positioning-diagnostic

# 2. Copy files (from wherever you downloaded them)
cp *.md ~/.claude/skills/positioning-diagnostic/

# 3. Verify
claude skills list
# You should see "positioning-diagnostic" in the list
```

## Your First Diagnostic

In a Claude Code session, type:

```
/diagnose https://yourcompany.com
```

This tells you immediately:
- ✓ or ✗ Can visitors understand what you do?
- ✓ or ✗ Can they tell who it's for?
- ✓ or ✗ Can they see why to choose you?
- MECLABS score (/20)
- Top 3 red flags

## All 6 Commands

| Command | Use Case |
|---------|----------|
| `/diagnose <url>` | Quick 5-second test + MECLABS score |
| `/audit <url>` | Comprehensive 100-point diagnostic |
| `/alignment` | Test team agreement on positioning |
| `/antipatterns <url>` | Scan for specific positioning mistakes |
| `/compare <url1> <url2>` | Side-by-side competitive comparison |
| `/export <url>` | Generate shareable markdown report |

## What You Get

- Specific scores (not just "needs work")
- Evidence-based findings (quotes from your homepage)
- Framework violations (which traps you've fallen into)
- Predicted symptoms (business pain this causes)
- Prioritized fixes (what to tackle first)

## What You DON'T Get

- Rewritten homepage copy
- Positioning statements written for you
- Decisions made for you

This is a diagnostic tool. It tells you what's broken and why. You fix it.

## Example Output

```
POSITIONING DIAGNOSTIC: Acme Corp

5-SECOND TEST:
✗ What they do: FAIL - "Innovative platform" too vague
✓ Who it's for: PASS - "Mid-market SaaS" is clear
✗ Why choose them: FAIL - No differentiation visible

MECLABS SCORE: 9/20 (Weak)

TOP 3 RED FLAGS:
1. Meaningless modifiers: "innovative" appears 3 times
2. Vague outcome: "Drive 10x productivity" with no mechanism
3. Multiple audiences: Speaking to developers AND executives

RECOMMENDED FOCUS:
Fix Product Identity. Critical question: What job does
your product do that alternatives don't?
```

## Recommended Workflow

```
/diagnose <url>       # Quick read: is there a problem?
/audit <url>          # Deep analysis: what exactly and why?
/alignment            # Internal check: does the team agree?
/antipatterns <url>   # Language scan: where are the bad habits?
/compare <url> <url>  # Competitive: how do you stack up?
/export <url>         # Package it all for stakeholders
```
