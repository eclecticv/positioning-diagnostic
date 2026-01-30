# Positioning Diagnostic Framework

A deep, evidence-backed diagnostic tool for analyzing homepage positioning using frameworks from April Dunford, Fletch PMM, Geoffrey Moore, and Al Ries/Jack Trout.

## Purpose

Help marketing teams diagnose positioning problems through systematic analysis. This skill provides diagnostic insights and recommendations but does NOT rewrite copy - it guides teams to make their own informed decisions.

Works with any company that has a homepage — B2B, B2C, SaaS, services, marketplaces, and more.

## Core Frameworks

### April Dunford's 5-Component Canvas
1. Competitive Alternatives - What customers would use if your product didn't exist
2. Unique Attributes - Features/capabilities only you have
3. Value - Customer outcomes with proof points
4. Target Customers - Segments who care intensely about your value
5. Market Category - Frame of reference that makes value obvious

### Fletch PMM's 4 Positioning Questions
1. What is your product? (category or use-case)
2. Who is it for? (company type, department, use case)
3. What does it replace? (competitive alternative)
4. Why is it better? (specific differentiation)

### Geoffrey Moore's Positioning Statement Template
"For [target customer] who [statement of need], [product] is a [category] that [key benefit]. Unlike [competitive alternative], [product] [primary differentiation]."

Used in `/audit` to test whether the homepage content can fill every slot in this template. Empty slots reveal positioning gaps.

### Al Ries & Jack Trout's Competitive Framing
- Own a word in the prospect's mind
- Position against the leader, not in a vacuum
- The first mover into a category owns it; latecomers must reposition

## Available Commands

1. `/diagnose` - Quick 5-second test analysis
2. `/audit` - Comprehensive 100-point positioning audit
3. `/alignment` - Test stakeholder alignment
4. `/antipatterns` - Scan for positioning mistakes
5. `/compare` - Side-by-side competitive positioning comparison
6. `/export` - Generate downloadable markdown summary

## Scoring Rubric (100-point scale)

Clarity (25 points):
- Product identity clear in 5 seconds: 0-10
- Target audience explicitly stated: 0-5
- Problem/pain point articulated: 0-5
- Jargon-free accessible language: 0-5

Differentiation (25 points):
- Competitive alternative acknowledged: 0-10
- Specific "why better" articulated: 0-10
- Proof of differentiation provided: 0-5

Value Proposition (25 points):
- Appeal to target audience: 0-7
- Exclusivity of offer: 0-6
- Clarity of proposition: 0-6
- Credibility of claims: 0-6

Execution (25 points):
- Above-the-fold completeness: 0-8
- Visual-message alignment: 0-5
- CTA clarity and prominence: 0-5
- Social proof presence and quality: 0-7

Score Interpretation:
- 80-100: Strong positioning, minor optimization needed
- 60-79: Adequate positioning, significant improvement opportunities
- 40-59: Weak positioning, requires strategic rework
- Below 40: Critical failure, full repositioning required
