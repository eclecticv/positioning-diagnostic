# Command: antipatterns

Scans content for specific positioning anti-patterns and bad habits.

## Usage
```
# Analyze a URL
/antipatterns <url>

# Or analyze raw text
/antipatterns "Your innovative platform..."
```

## What It Detects

### Dunford's 10 Positioning Traps
1. **Default positioning** — Stuck in original conception; market has evolved but positioning hasn't
2. **Me-too positioning** — Sounds identical to competitors; no differentiation visible
3. **Wishful thinking** — Claiming aspirational position not supported by evidence
4. **Positioning by committee** — Compromise language that tries to please everyone internally
5. **Positioning for investors** — Speaking to funding audience, not customers
6. **Stuck in the past** — Leading with legacy strengths the market no longer values
7. **Giving up on positioning** — Letting the market define you by default
8. **Trend-riding** — Positioning around a buzzword (e.g., "AI-powered") without substance
9. **Confusing positioning with messaging** — Treating taglines as strategy; no underlying framework
10. **Positioning too broadly** — Trying to be everything to everyone; no target segment focus

### Fletch's 4 Bad Habits
- **Speaking to multiple audiences at once** — Homepage tries to address different buyers simultaneously
- **Choosing the wrong champion** — Targeting the wrong persona in the buying process
- **Sharing multi-order benefits** — Benefit of a benefit of a benefit (too abstract)
- **Using vision-messaging** — Describing future state instead of current delivered value

### Language Red Flags
- Meaningless modifiers (revolutionary, innovative, cutting-edge, next-generation)
- Vague business outcomes (drive growth, unlock potential, transform your business)
- Empty tech claims (AI-powered without specifics, machine learning without mechanism)
- Buzzword compounds (end-to-end intelligent automation platform)

## Example Output

```
ANTI-PATTERN SCAN: [Company Name]
URL: [url]

═══════════════════════════════════════
DETECTED ANTI-PATTERNS
═══════════════════════════════════════

1. [Anti-pattern name] — Severity: 🔴 High / 🟡 Medium / 🟢 Low

   Source: "[quoted text from homepage]"

   Why it matters: [1-2 sentence explanation of the business
   impact of this anti-pattern]

   Framework: [Dunford Trap #X / Fletch Bad Habit / Language Red Flag]

2. [Anti-pattern name] — Severity: 🔴/🟡/🟢

   Source: "[quoted text]"

   Why it matters: [explanation]

   Framework: [source]

[... additional patterns ...]

═══════════════════════════════════════
CLEAN PATTERNS (what's working)
═══════════════════════════════════════

✓ [Positive pattern observed with evidence]
✓ [Positive pattern observed with evidence]

═══════════════════════════════════════
SUMMARY
═══════════════════════════════════════

Anti-patterns found: X
Critical (🔴): X
Medium (🟡): X
Low (🟢): X

Primary risk: [one-sentence summary of biggest positioning risk]
```

## Output
Lists detected anti-patterns with evidence from content, severity assessment, and framework attribution. Also highlights clean patterns to reinforce what's working.
