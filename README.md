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
| **Base** | 1.06× | ₹0.15L surplus | Month 3 |
| **Bull** | 3.9× | ₹7.22L surplus | Month 2 |

**Cost (all scenarios):** ₹2.49L — ₹12,500/mo stipend + ₹98,600 overhead (itemised below)

**Base benefit (methodology table total):** ₹2.64L — six line items, each with a derivation and confidence rating. Conversion optionality (₹90K) is excluded from the headline BCR.

> ⚠️ Bear and bull BCRs are driven by different hours and rate assumptions (not the same line items as the base methodology table). The base BCR of 1.06× is the honest figure that traces directly to the table.

**CBA Quality Score:** 80/100 — rated on rigour of the analysis itself, not how impressive it sounds. Score is the calculated weighted average of 7 criteria: Evidence Quality (88), Financial Rigour (84), Scenario Coverage (90), Output Credibility (88), Benefit Methodology (78), Conversion Weighting (75), External Benchmarking (58).

---

## Overhead Itemisation — ₹98,600

| Line | Derivation | Amount |
|------|-----------|--------|
| Workspace / hot desk | ₹4,000/month × 12 | ₹48,000 |
| HR & admin time | 2 hrs/month × ₹400/hr × 12 | ₹9,600 |
| Onboarding (one-time) | Fixed one-time cost | ₹5,000 |
| Equipment amortisation | Prorated annual share | ₹15,000 |
| Software licences | Tooling seat costs | ₹6,000 |
| Ramp supervision | Senior time during weeks 1–3 | ₹15,000 |
| **Total** | | **₹98,600** |

---

## Sections

| Section | What It Does |
|---------|-------------|
| **Score** | Rates the quality of this CBA on 7 dimensions. Dial displays the actual calculated weighted average (80). |
| **Metrics** | Base case headline numbers with a 3-scenario toggle (Bear / Base / Bull) |
| **Methodology** | Full line-item derivation table — every benefit value, its source, and confidence level. Includes overhead itemisation and discount rate note. |
| **Simulator** | Live stipend slider — drag to see how cost changes cascade through BCR and net value |
| **Benefits** | 6 value categories, each with a derivation note and confidence rating |
| **Work Samples** | 6 actual deliverables — linked to GitHub/LinkedIn, not just described |
| **Timeline** | 4-phase ramp from onboarding to positive ROI, with bear case timing |
| **Risks** | 5 named risks, each with its BCR impact if it materialises |
| **Decision** | Recommendation with the senior rate sensitivity named explicitly |

---

## Fixes Applied (v2)

Five corrections made to reconcile all numbers end-to-end:

1. **Benefit Reconciliation** — Headline benefit corrected from ₹6.64L → ₹2.64L (the actual methodology table total). Base BCR corrected from 2.7× → 1.06× (₹2.64L ÷ ₹2.49L). Net value corrected from ₹4.15L → ₹0.15L. Every headline number now traces to a table row.
2. **Overhead Itemisation** — ₹98,600 overhead broken down explicitly: Workspace ₹48K + HR/admin ₹9.6K + Onboarding ₹5K + Equipment ₹15K + Software ₹6K + Ramp supervision ₹15K = ₹98,600.
3. **Ramp Inconsistency** — Note added in methodology table: "40 productive weeks excludes 8 weeks as a conservative buffer for ramp, exam periods, and unexpected friction — not just the 3-week base ramp."
4. **Discount Rate Gap** — Note added under methodology: no discount rate applied; a revised version would model BCR at 8%, 12%, and 15% hurdle rates.
5. **Score Dial** — Fixed to compute and animate to the actual calculated weighted average (80) from the 7 criteria scores. Added a fallback viewport trigger so the dial always fires even if the element is already visible on page load.

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

The analysis self-declares five known gaps:

1. Senior hourly rate (₹400/hr) is an internal estimate — no external salary data cited. If the real rate is ₹300/hr, base BCR narrows further.
2. The 5-agent pipeline and Monte Carlo work are cited but not independently verifiable within this document.
3. Long-term conversion value is probability-weighted at 30%, but that figure is itself an assumption.
4. Process standardisation benefit (₹35K) is the weakest line — hard to isolate from general contribution.
5. No discount rate applied — a revised model would test at 8%, 12%, and 15% hurdle rates.

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
