# WireGraph 4

Interactive p5.js visualization comparing your portfolio performance to key market benchmarks.

## Files

- `index.html`: Main HTML entrypoint.
- `style.css`: Styling for controls and layout.
- `sketch.js`: p5.js sketch code providing interactive graph.
- `portfolio_performance_20250418_230752.json`: Daily portfolio values.
- `all_indices_20250418_214547.json`: Historical data for S&P 500, Dow Jones, NASDAQ, Russell 2000, FTSE 100.
- `all_indices_20250418_214222.json`: Additional historical data snapshot.

## Features

- Toggle between line, bar, or mixed chart types.
- Adjust canvas/graph size, grid mode, and bar settings.
- Save and copy SVG output.
- Collapse control panel and toggle area fills.

## Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/haraujo77/wiregraph4.git
   ```
2. Serve files locally:
   ```bash
   npx serve .
   ```
3. Open `index.html` in a browser.

## Live Demo

Available via GitHub Pages at https://haraujo77.github.io/wiregraph4 