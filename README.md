# Marcellus CCP reconstruction

An interactive reconstruction of the anonymized stock clues in Marcellus's April 2026 Consistent Compounders Portfolio (CCP) newsletter.

## Open the table

[Open the interactive CCP table](https://imdrcee.github.io/Marcellus/) (Ctrl/Cmd-click or middle-click to open in a new tab).

The [HTML source file](./marcellus_ccp_reconstruction.html) is also available in this repository; GitHub's source-code view shows the markup rather than rendering it. To run it locally, download the HTML file and open it in a modern browser. The page works without a server and provides:

- All 19 anonymized stock clues, proposed best-fit and alternate companies, evidence notes, confidence labels, and estimated weights.
- Search, confidence filtering, and sortable columns.
- Editable company names, estimated weights, and evidence notes. Edits persist in browser local storage on that device.
- CSV export and reset-to-original controls.

## Important interpretation

The newsletter does not disclose the current stock names or individual weights in its exhibits. Stock matches are hypotheses, not confirmed holdings. Individual weights are model estimates. The weight model targets 51% large-cap allocation (reported in contemporaneous coverage), with an assumed 30% mid-cap / 19% small-cap split, and totals 100%. Do not treat it as Marcellus-reported data or investment advice.

The HTML's original snapshot was created in September 2026. For research method, current working hypotheses, and instructions for future updates by another LLM, see [`LLM_UPDATE_GUIDE.md`](./LLM_UPDATE_GUIDE.md).

## Primary references

- [Marcellus April 2026 newsletter](https://marcellus.in/newsletter/consistent-compounders/diversification-in-a-concentrated-portfolio-of-compounders/)
- [Moneycontrol April 2026 coverage of portfolio changes](https://www.moneycontrol.com/news/business/markets/marcellus-rejigs-portfolio-exits-from-it-makes-healthcare-bet-amid-continued-consumption-slowdown-13895169.html)
- [Moneycontrol CCP performance and contributor coverage](https://www.moneycontrol.com/news/business/markets/marcellus-ccp-astral-and-divis-join-eicher-as-top-contributors-as-portfolio-tilts-further-toward-healthcare-and-exports-13975792.html)
