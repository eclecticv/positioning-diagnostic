# Command: diagnose

Quick positioning diagnostic using the 5-second test and MECLABS framework.

## Usage
```
/positioning:diagnose <url>
```

## What It Does

1. Fetches the homepage content
2. Applies 5-second test (what/who/why questions)
3. Scores MECLABS framework (Appeal/Exclusivity/Clarity/Credibility)
4. Identifies top 3 red flags
5. Provides actionable next steps

## Example Output

```
POSITIONING DIAGNOSTIC: Company Name
URL: https://example.com

5-SECOND TEST:
✓/✗ What they do: [assessment]
✓/✗ Who it's for: [assessment]  
✓/✗ Why choose them: [assessment]

MECLABS SCORE: X/20
• Appeal: X/5 - [one sentence why]
• Exclusivity: X/5 - [one sentence why]
• Clarity: X/5 - [one sentence why]
• Credibility: X/5 - [one sentence why]

TOP 3 RED FLAGS:
1. [specific finding with example]
2. [specific finding with example]
3. [specific finding with example]

RECOMMENDED FOCUS:
The weakest positioning component is [Component]. 
First improvement to test: [concrete action].
```
