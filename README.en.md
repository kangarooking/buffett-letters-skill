# Buffett Letters Skill

A ready-to-use AI skill pack — 20 composable investment reasoning modules distilled from Warren Buffett's 60+ years of shareholder letters.

This is not a book summary page. The book is the source; these skills are the product.

## What Problems Do These Skills Solve

- A stock is surging and you don't know whether to chase or run
- You want to judge real business quality, not just P/E ratios and growth rates
- You're unsure whether you're making decisions inside your "circle of competence"
- You want to distinguish real conservatism from conservatism that only looks the part
- You need a structured investment decision framework instead of gut feelings and fragmented information

## What Was Distilled

20 triple-verified skills extracted from Buffett's shareholder letters (1957-2023), covering five dimensions:

- **Investment Philosophy**: `circle-of-competence`, `mr-market`, `business-picker`, `real-conservatism`
- **Valuation & Pricing**: `aesop-three-questions`, `margin-of-safety`, `look-through-earnings`, `three-asset-categories`
- **Business Quality**: `economic-moat`, `cigar-butt-vs-great-business`, `float-thinking`
- **Behavior & Psychology**: `fear-and-greed`, `institutional-imperative`, `hold-forever`
- **Capital Allocation & Risk**: `first-law-of-capital-allocation`, `compounding-thinking`, `no-leverage`, `never-issue-shares`, `ceo-as-risk-officer`, `partner-with-admired`

The extraction process started with 40 deduplicated candidate units and achieved a ~50% pass rate.

## Effect Examples

### Example 1: Facing a Surging Stock

**User Question**

"A stock has gone up 80% in three months. Everyone is talking about it. Should I get in now?"

**Skill Judgment**

- Trigger `mr-market` — is this Mr. Market's quote or a real change in business value?
- Trigger `fear-and-greed` — check if you're being driven by FOMO
- Call `circle-of-competence` — do you genuinely understand this company?
- Finish with `margin-of-safety` — does the current price still offer a safety cushion?

**Response Example**

> 80% in three months — first ask: what has changed about this business in those three months? If the answer is "not much," then that 80% is Mr. Market's quote, not business value growth. Mr. Market gives you quotes every day, not to tell you the truth, but to give you a chance to exploit his mood. Then ask yourself: are you afraid of missing out, or do you actually understand this company? If you can't explain how it makes money, you're not in your circle of competence — you're in a casino. Finally, look at the price: if it's already far above any value you can calculate, the margin of safety is gone, and this isn't an investment decision — it's a speculation.

### Example 2: Should You Use Leverage?

**User Question**

"I'm confident in my judgment. Should I use some leverage to amplify my returns?"

**Skill Judgment**

- Trigger `no-leverage` — Buffett's consistent stance and reasoning on leverage
- Supplement with `margin-of-safety` — are safety margins and leverage logically contradictory?
- If insurance/float scenarios are involved, add `float-thinking` to distinguish "others pay you to use their money" from "borrowing to放大 bets"

**Response Example**

> Buffett's position over decades is clear: don't use leverage. The reason isn't that leverage can't amplify returns — it's that leverage strips away your time optionality. A correct judgment wiped out by a forced liquidation makes being correct meaningless. The core logic of margin of safety is leaving room for error; the logic of leverage is amplifying errors. These two things are contradictory at the foundation. If you're truly confident in your judgment, compounding will give you sufficient returns without leverage. If your confidence needs leverage to prove itself, that confidence deserves a second look.

## How These Skills Were Generated

These skills were produced using the **cangjie-skill** RIA-TV++ pipeline, a six-stage process:

1. **Whole-Book Comprehension (Adler Analysis)** — Structural, interpretive, critical, and applicability analysis of the entire book, producing `BOOK_OVERVIEW.md`
2. **Parallel Extraction** — Five specialized extractors (frameworks, principles, cases, counter-examples, glossary) run simultaneously to pull candidate units from the source text
3. **Triple Verification** — Each candidate must pass three checks: at least 2 independent supporting passages in the book (cross-domain), ability to answer a novel question not explicitly addressed (predictive power), and non-commonsense uniqueness. Pass rate is typically 25-50%
4. **RIA++ Construction** — Verified content is structured into six dimensions: R (original quote) / I (own-words reconstruction) / A1 (book cases) / A2 (future trigger scenarios) / E (executable steps) / B (boundaries & blind spots)
5. **Zettelkasten Linking** — Dependency, contrast, and composition relationships between skills are identified, producing `INDEX.md` with a reference graph
6. **Pressure Testing** — Test prompts including bait questions are designed for each skill; failures go back to Stage 4 for full reconstruction

Every `SKILL.md` is a real output of this process. `candidates/` and `rejected/` directories are preserved as a complete audit trail.

## Generated by Cangjie Skill

This repository was generated by [cangjie-skill](https://github.com/kangarooking/cangjie-skill) — an open-source toolchain that distills books into executable AI skills.

Built on the RIA-TV++ methodology, cangjie-skill extracts methodologies, frameworks, and principles from books into atomic skills that AI agents can invoke in real-world scenarios.

## Repository Structure

```text
buffett-letters-skill/
├── README.md              ← You are here
├── README.en.md           ← English version
├── README.ja.md           ← Japanese version
├── LICENSE                ← MIT
├── BOOK_OVERVIEW.md       ← Stage 0 output: full-book Adler analysis
├── INDEX.md               ← Stage 3 output: skill overview + reference graph
├── candidates/            ← Stage 1 output: raw candidate units
├── rejected/              ← Stage 1.5 output: rejected units + reasons
├── verified.md            ← 20 units that passed triple verification
└── */SKILL.md             ← 20 skills, each with test-prompts.json
```

## How to Use

1. Browse `INDEX.md` for the full skill map and dependency relationships
2. Find the `*/SKILL.md` relevant to your current problem and use its trigger conditions and execution steps
3. Integrate skills into your agent framework, or use prompts as standalone tools
4. Validate with `test-prompts.json` — skills should trigger in the right scenarios and stay silent in the wrong ones

## Source

- Material: Berkshire Hathaway annual shareholder letters
- Author: Warren Buffett
- Period: 1957-2023

## More Skills

- [Poor Charlie's Almanack Skill](https://github.com/kangarooking/poor-charlies-almanack-skill) — 12 decision-making and judgment skills from Charlie Munger's core thinking methods
- [No Rules Rules Skill](https://github.com/kangarooking/no-rules-rules-skill) — 10 organizational design skills from Netflix's culture of freedom and responsibility

## License

MIT. See [LICENSE](./LICENSE).
