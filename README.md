# KT · Investment Case 2025

**A structured, brutally honest cost–benefit analysis for hiring Kathan Talati as an intern.**

> Every number has a derivation. Every gap is named. Nothing is inflated.

🔗 **Live site:** [kt-10-ai.github.io/kt-investment-case](https://kt-10-ai.github.io/kt-investment-case)

---

## What This Is

This is a single-page interactive CBA (cost–benefit analysis) built from scratch to make the case for an internship hiring decision — without vanity metrics or inflated claims.

Three scenarios are modelled. The bear case is shown upfront. The full benefit methodology is documented line-by-line with confidence ratings. Work samples are linked, not just mentioned.

---

## Key Numbers

| Scenario | BCR | Net Value | Breakeven |
|----------|-----|-----------|-----------|
| **Bear** | 1.4× | ₹1.0L surplus | Month 4–5 |
| **Base** | 2.7× | ₹4.15L surplus | Month 3 |
| **Bull** | 3.9× | ₹7.22L surplus | Month 2 |

**Cost (all scenarios):** ₹2.49L — ₹12,500/mo stipend + ₹98,600 overhead (mentoring, ops, review)

**CBA Quality Score:** 80/100 — rated on rigour of the analysis itself, not how impressive it sounds. Gaps are documented.

---

## Sections

| Section | What It Does |
|---------|-------------|
| **Score** | Rates the quality of this CBA on 7 dimensions. Honest about weak lines. |
| **Metrics** | Base case headline numbers with a 3-scenario toggle (Bear / Base / Bull) |
| **Methodology** | Full line-item derivation table — every benefit value, its source, and its confidence level |
| **Simulator** | Live stipend slider — drag to see how cost changes cascade through BCR and net value |
| **Benefits** | 6 value categories, each with a derivation note and confidence rating |
| **Work Samples** | 6 actual deliverables — linked to GitHub/LinkedIn, not just described |
| **Timeline** | 4-phase ramp from onboarding to positive ROI, with bear case timing |
| **Risks** | 5 named risks, each with its BCR impact if it materialises |
| **Decision** | Recommendation with the senior rate sensitivity named explicitly |

---

## Tech

Built entirely in **vanilla HTML, CSS, and JavaScript** — no framework, no build step, no dependencies.

- **Fonts:** Syne (headings) · Inter (body) · JetBrains Mono (data/labels) via Google Fonts
- **Animations:** CSS keyframes + IntersectionObserver-driven reveal system
- **Canvas:** Interactive particle field with mouse attraction (vanilla `requestAnimationFrame`)
- **Interactivity:** Live scenario toggle, stipend simulator, animated score dial, scroll progress bar, active nav tracking, copy-email button
- **Cursor:** Custom cursor with CSS `mix-blend-mode: screen`

No Tailwind. No React. No bundler. Opens directly in a browser.

---

## Candidate

**Kathan Talati**  
CS & Business Systems · K.J. Somaiya Institute of Management, Mumbai  
GPA: 8.96/10 · EY Scholarship National Finalist · KEN Competition Top 50/300+

**Stack:** FastAPI · React · OpenAI API · Python · NumPy · Pytest · SQL · Figma

📧 kathantalati20@gmail.com  
🔗 [linkedin.com/in/kathantalati](https://linkedin.com/in/kathantalati)  
💻 [github.com/kt-10-ai](https://github.com/kt-10-ai)  
📞 +91 77389 98226

---

## Honest Limitations

The analysis self-declares four known gaps:

1. Senior hourly rate (₹400/hr) is an internal estimate — no external salary data cited. If the real rate is ₹300/hr, base BCR drops to ~2.3×.
2. The 5-agent pipeline and Monte Carlo work are cited but not independently verifiable within this document.
3. Long-term conversion value is probability-weighted at 30%, but that figure is itself an assumption.
4. Process standardisation benefit (₹35K) is the weakest line — hard to isolate from general contribution.

These are not footnotes. They are in the main body.

---

## Running Locally

```bash
# Any static server works — no build needed
npx serve .
# → http://localhost:3000
```

Or just open `index.html` directly in a browser.

---

## License

MIT. Use the structure, not the numbers — those are specific to this candidate and engagement.
