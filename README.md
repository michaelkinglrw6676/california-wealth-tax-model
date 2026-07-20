# California wealth tax fiscal impact calculator

> **A browser-based calculator for evaluating the fiscal effects of a proposed California billionaire wealth tax under multiple assumption sets, with shareable scenarios and a current static web app build.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/michaelkinglrw6676/california-wealth-tax-model?style=flat-square)](https://github.com/michaelkinglrw6676/california-wealth-tax-model)

---

<p align="center">
  <a href="https://michaelkinglrw6676.github.io/california-wealth-tax-model/">
    <img src="https://img.shields.io/badge/Download-California%20wealth%20tax%20fiscal%20impact%20calculator%20Latest-brightgreen?style=for-the-badge" alt="Download California wealth tax fiscal impact calculator">
  </a>
</p>

> **[Direct Download - California wealth tax fiscal impact calculator v](https://michaelkinglrw6676.github.io/california-wealth-tax-model/)**

---

[Download Latest Build](https://michaelkinglrw6676.github.io/california-wealth-tax-model/)

---

## Overview

California wealth tax fiscal impact calculator is a single-page static web application created to explore fiscal outcomes associated with a proposed California billionaire tax. It lets users tune assumptions, compare cases, and see how estimated results evolve over time without any complicated setup.

The app is well suited to policy review, research demonstrations, and quick what-if analysis. It pairs a PolicyEngine-backed California income-tax lookup with charts so the core assumptions, annual trends, and summary effects are easier to examine together.

---

## Capabilities

- One-page interactive calculator for rapid scenario testing
- Shareable scenario URLs for saving and exchanging inputs
- Annual return-hazard migration model for year-by-year behavior
- Year-by-year cash-flow chart for tracking estimated changes over time
- Discounted summary output for compact fiscal interpretation
- Waterfall chart visualization for component-level comparison
- PolicyEngine-backed California income-tax lookup
- Static web app structure for simple browser-based access

---

## Getting Started

The project is distributed as a static web app, so the fastest path is to open the published build in a browser.

To run it from source locally:

1. Clone the repository
2. Open the project folder
3. Serve the files with any static web server, or open the HTML entry point in a browser if your environment supports it

Example:

git clone https://github.com/michaelkinglrw6676/california-wealth-tax-model.git
cd california-wealth-tax
python -m http.server 8000

Then visit `http://localhost:8000` in your browser.

---

## How to Use

1. Open the calculator in your browser.
2. Adjust the policy and assumption inputs for the scenario you want to test.
3. Review the cash-flow chart, waterfall view, and discounted summary.
4. Copy or share the scenario URL if you want to revisit the same configuration later.
5. Compare alternate assumptions by editing the inputs and observing how the outputs change.

The layout keeps the full scenario in one place, making it easier to move between assumptions, modeled behavior, and results.

---

## Configuration Notes

Most settings are controlled from the page interface and, when supported by the app, stored in the encoded scenario state.

If you are running the project locally, configuration is usually handled in the static app files plus any embedded script or data assets used by the calculator. In practice, that means:

- Scenario inputs are adjusted in the browser
- Shared links preserve the current calculation state
- Tax lookup logic relies on the bundled PolicyEngine-backed data path

If you need to change behavior, inspect the HTML and any linked script or data sources in the project folder.

---

## Requirements

- A modern web browser
- Static file hosting or a local HTTP server for development
- Internet access if you are loading the published build from the hosted URL
- A browser environment capable of rendering charts and handling shareable URLs

---

## FAQ

**How do I get the latest version?**  
Use the download link above to open the current hosted build.

**Can I share a calculation with someone else?**  
Yes. The app supports shareable scenario URLs so you can send a configured case to another person.

**Where are the results shown?**  
The calculator presents a cash-flow chart, a waterfall chart, and a discounted summary directly in the page.

**What if the page does not load correctly?**  
Try a current browser, clear the cache, and confirm that any local files are being served through a static web server rather than opened in a restricted file context.

**How are California tax values determined?**  
The calculator uses PolicyEngine-backed California income-tax lookup logic as part of the scenario workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
