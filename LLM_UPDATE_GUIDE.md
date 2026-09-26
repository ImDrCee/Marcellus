# Handoff instructions for future LLM updates

## Purpose

Continue the reconstruction of Marcellus's Consistent Compounders Portfolio (CCP) when a later Marcellus newsletter or other relevant evidence becomes available. The goal is an auditable, careful mapping of anonymized stock clues to likely listed companies, with estimates clearly separated from disclosed facts.

## Read these files first

1. `README.md` for the project scope and caveats.
2. `marcellus_ccp_reconstruction.html` for the current interactive table, hypotheses, citations, weights, and original creation stamp.
3. The latest newsletter and linked exhibit images. Verify that you are using the correct portfolio strategy, date, and exhibits before updating anything.

## Current working assumptions

- The source portfolio is Marcellus CCP, April 2026. It contains 19 anonymized rows in Exhibits 2 and 3.
- Exhibit 2 supplies a row number, market-cap bucket, consensus revision, and business/sector clue. Exhibit 3 supplies anonymized Q3FY26 EBITDA growth, pre-exceptional EPS growth, FY25 RoCE, and FY23–25 reinvestment rate.
- April 2026 article coverage reports 19 stocks, more than 40% in the top five, and 51% large-cap exposure. This project assumes 30% mid-cap and 19% small-cap only to complete an estimated allocation model; those splits are not disclosed facts.
- Estimated row weights sum to 100%. Current top five guessed weights sum to 41.5%; neither the selected identities nor the individual weights are confirmed.
- The app's created month is September 2026. When making an update, preserve that original created date, and separately change the “Last reviewed” or “Updated” date. Change the portfolio-period label only when the evidence being added actually applies to a new portfolio period.
- Browser-local edits are not committed into the HTML automatically. Save durable project updates into the HTML/source files, then commit them. CSV export can preserve a working copy of table rows, but it is not a substitute for updating the source file and documenting evidence.

## Current best-fit mapping

These are hypotheses, not confirmed CCP constituent identities:

| # | Current best fit | Confidence | Estimated weight |
|---:|---|---|---:|
| 1 | Tube Investments of India Ltd. | Medium-high | 4.5% |
| 2 | Trent Ltd. | High | 9.0% |
| 3 | Divi's Laboratories Ltd. | High | 9.0% |
| 4 | Narayana Health (Narayana Hrudayalaya Ltd.) | High | 7.0% |
| 5 | Eicher Motors Ltd. | High | 9.0% |
| 6 | Asian Paints Ltd. | Medium | 4.0% |
| 7 | Info Edge (India) Ltd. | High | 3.0% |
| 8 | Astral Ltd. | Medium-high | 4.5% |
| 9 | CMS Info Systems Ltd. | High | 4.5% |
| 10 | Tata Consumer Products Ltd. | Medium | 3.0% |
| 11 | Dr. Lal PathLabs Ltd. | Medium-high | 4.5% |
| 12 | Kotak Mahindra Bank Ltd. | Medium | 7.5% |
| 13 | Escorts Kubota Ltd. | High | 4.5% |
| 14 | Metro Brands Ltd. | High | 5.0% |
| 15 | ICICI Lombard General Insurance Co. Ltd. | Medium | 4.5% |
| 16 | CarTrade Tech Ltd. | High | 5.0% |
| 17 | Cholamandalam Investment and Finance Co. Ltd. | High | 3.5% |
| 18 | Vijaya Diagnostic Centre Ltd. | High | 5.0% |
| 19 | Pidilite Industries Ltd. | Medium-high | 3.0% |

Important weak points:

- #11 Dr. Lal PathLabs is currently favored over Krsnaa Diagnostics because its business footprint and planned radiology expansion fit the clue, and its ~16.3% pre-exceptional Q3FY26 EBITDA growth and ~31% FY25 RoCE are close to Exhibit 3. Its Q3 EPS growth does not cleanly fit, and a small-cap label would need independent verification. Marcellus's historic position in Dr. Lal is evidence of interest, not proof of April 2026 CCP inclusion.
- #18 Vijaya Diagnostic Centre has an unusually close result match: Q3FY26 EBITDA growth ~28.2% and EPS growth ~22.5% versus Exhibit 3's 28% and 23%. The exact 30% RoCE has not been verified. Marcellus discussed Vijaya in Little Champs material; that does not establish it as CCP #18.
- #12 Kotak is a thematic guess for the large bank clue. The clue is generic, and the public evidence does not uniquely identify Kotak.
- The “High” confidence label means the clue/evidence is relatively distinctive within this reconstruction, not that Marcellus confirmed the stock name.

## Research procedure for each new update

1. **Identify the actual document.** Capture newsletter title, publication date, portfolio period, relevant exhibit numbers, source URL, and any image/PDF URLs. Avoid mixing CCP with Little Champs, Rising Giants, Kings of Capital, or another product.
2. **Transcribe before interpreting.** Record every row's clue and market-cap bucket exactly. Separately transcribe any unlabeled growth, EPS, RoCE, reinvestment, or weight figures. Recheck row numbers against the exhibit image; row-shift errors have occurred before.
3. **Search Marcellus primary sources first.** Search newsletters, presentations, portfolio snapshots, interviews, and direct management commentary for exact company names, addition/removal timing, sector rationale, and older public constituent names.
4. **Use contemporaneous coverage only as corroboration.** Prefer company filings/results, Marcellus material, exchange filings, and established financial press. Search-results snippets or generated portfolio lists are not sufficient evidence.
5. **Cross-check financial fingerprints.** Compare each candidate with the exact metric, fiscal quarter, accounting basis (consolidated/standalone; reported/adjusted; pre/post exceptional items), and date stated in the exhibit. State the metric and source precisely; do not claim a match based on a nearby value or different basis.
6. **Separate evidence from inference.** For each row retain: direct clue match; financial match; Marcellus/media evidence; alternative candidates; confidence and why. A Marcellus holding in a different strategy is not proof of CCP membership.
7. **Record dates.** If a public source reports when a stock was added or removed, record the date and source explicitly. Do not infer an exact quarter from a vague phrase such as “last summer”; identify fiscal/calendar conventions.
8. **Re-estimate weights transparently.** Use newly published actual data where available. Otherwise preserve an explicit market-cap bucket model and constraints from the article. State assumptions, normalize total only if the method requires it, and never label estimated weights as reported allocations.
9. **Update the artifact.** Modify the HTML table and its “Last reviewed” date. Keep “Created: September 2026” unchanged. Add links for new evidence in the affected rows, update confidence and alternates, and revise the notes if previous assumptions are no longer valid.
10. **Validate before saving.** Confirm there are 19 rows unless the source says otherwise, row numbers are unique and complete, weights are numeric and total 100% (or clearly state why not), search/filter/sort/edit/CSV/reset still work, and every evidence link opens to the cited source. Review the rendered file in a browser.
11. **Summarize changes.** State which rows changed, what source caused each change, which conclusions remain uncertain, and whether the update changed estimated weights or methodology. Do not make investment recommendations.

## Suggested prompt for a future LLM

> Continue this project's evidence-led reconstruction of Marcellus CCP from the latest newsletter I provide. First read `README.md`, `LLM_UPDATE_GUIDE.md`, and `marcellus_ccp_reconstruction.html`. Preserve the September 2026 creation date; update only the last-reviewed date. Verify the exact strategy and portfolio period; inspect and transcribe every exhibit row before mapping names. Search primary Marcellus sources and reliable contemporaneous company/financial sources. Compare the exhibit's exact quarter, metric definitions, financial basis, market-cap bucket, and business clue against candidate companies. Distinguish disclosed facts from hypotheses; a company held by another Marcellus strategy is not proof of CCP membership. Keep alternatives and explain confidence row by row. Do not present guessed weights as actual allocations. If weights remain estimates, state all assumptions and maintain a transparent 100% model with the disclosed concentration and market-cap constraints. Update the HTML and citations, test its interactive functions, and provide a concise changelog listing revised rows, evidence, remaining uncertainties, and weight/methodology changes.

## Primary and row-level source links

The interactive table contains row-level source links. Core portfolio references:

- [Marcellus April 2026 CCP newsletter](https://marcellus.in/newsletter/consistent-compounders/diversification-in-a-concentrated-portfolio-of-compounders/)
- [Moneycontrol, April 2026: portfolio changes and IT exit](https://www.moneycontrol.com/news/business/markets/marcellus-rejigs-portfolio-exits-from-it-makes-healthcare-bet-amid-continued-consumption-slowdown-13895169.html)
- [Moneycontrol: CCP contributors/detractors and sector tilts](https://www.moneycontrol.com/news/business/markets/marcellus-ccp-astral-and-divis-join-eicher-as-top-contributors-as-portfolio-tilts-further-toward-healthcare-and-exports-13975792.html)
- [Marcellus on lenders gaining from the crisis](https://marcellus.in/newsletter/consistent-compounders/the-lenders-in-our-portfolio-will-gain-from-the-ongoing-crisis/)
- [Marcellus's Vijaya Diagnostic spotlight (Little Champs; not CCP confirmation)](https://marcellus.in/newsletter/little-champs/little-champs-spotlighting-vijaya-diagnostic/)
- [CNBC-TV18 interview discussing Marcellus's diagnostic holdings](https://www.cnbctv18.com/market/stocks/why-saurabh-mukherjea-thinks-diagnostic-stocks-vijaya-diagnostics-metropolis-healthcare-are-little-champs-17665251.htm)
