# Figra

**Publication-Quality Scientific Figures from Excel Data**

Figra is an Excel Office Add-in that creates publication-ready scientific visualizations using R and ggplot2 — directly in your browser, with no R installation required.

For chart examples, screenshots, and full documentation, visit **[https://h20gg702.github.io/figra-pages/](https://h20gg702.github.io/figra-pages/)**.

---

## Installation

1. Open Excel
2. Go to **Insert** > **Add-ins** > **Get Add-ins**
3. Search for **Figra**
4. Click **Add**

Or sideload the manifest manually for testing — see [https://h20gg702.github.io/figra-pages/](https://h20gg702.github.io/figra-pages/) for instructions.

---

## Quick Start

1. **Select your data** in Excel (with headers)
2. **Click "Load Data"** in the Figra panel
3. **Choose a chart type** from the dropdown
4. **Map your columns** (Group, X, Y, Error as needed)
5. **Customize** colors, fonts, and themes
6. **Click "Preview"** to see your figure
7. **Click "Insert Figure"** to add it to your sheet

---

## Features

- **18+ chart types** — bar, box, violin, dot, line, grouped variants, IC50 dose-response
- **Built-in statistical analysis** — t-test, ANOVA, Kruskal-Wallis, Wilcoxon, with post-hoc tests
- **Significance markers** — brackets with *, **, *** or p-values, automatically placed
- **R code export** — generates ggplot2 code that reproduces your exact figure
- **Full customization** — fonts, colors, themes, axis scales, labels
- **Data Table Converter** — converts wide-format Excel data to long format for plotting
- **No R installation required** — runs entirely in your browser via WebAssembly

---

## How It Works

Figra uses [webR](https://webr.r-wasm.org/) to run R code directly in your browser via WebAssembly:

- **No R installation required** — runs entirely client-side
- **No server** — all processing happens locally, data never leaves your computer
- **Cross-platform** — works on Windows, Mac, and Excel Online
- **Reproducible** — export ggplot2 R code to recreate figures anywhere

---

## Author

**Yoshiaki Sato**
ORCID: [0000-0003-3375-5189](https://orcid.org/0000-0003-3375-5189)

## License

MIT License
