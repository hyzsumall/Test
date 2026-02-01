# CLAUDE.md

## Project Overview

This is a **NAND & DRAM Price Trend Dashboard** - a single-page web application that visualizes memory chip price trends and growth rates for 2025.

## Tech Stack

- **Frontend**: Pure HTML/CSS/JavaScript (no build tools required)
- **Charting**: Chart.js (loaded via CDN)
- **Language**: Chinese (zh-CN)

## Project Structure

```
/
├── nand-dram-dashboard.html   # Main dashboard (self-contained)
└── CLAUDE.md                  # This file
```

## Running the Project

Simply open `nand-dram-dashboard.html` in a web browser. No server or build process required.

## Features

- Price trend comparison charts (NAND vs DRAM)
- Monthly growth rate bar charts
- Cumulative growth rate visualization
- Detailed data table with all monthly figures
- Responsive design with dark theme
- Stats cards showing current prices and annual growth

## Data

The dashboard uses simulated/demo data for 2025:
- **NAND prices**: $3.00 - $3.85/GB (28.3% annual growth)
- **DRAM prices**: $2.16 - $2.92/GB (35.2% annual growth)

## Development Notes

- All styles are inline within the HTML file
- Chart.js is loaded from CDN (`cdn.jsdelivr.net`)
- Data calculations (growth rates, cumulative growth) are done client-side
- Mobile responsive with breakpoint at 768px
