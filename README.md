# Red Alert: CVE Alert Dashboard Google Chrome Extension

![Chrome](https://img.shields.io/badge/Chrome-Extension-red) ![NVD API](https://img.shields.io/badge/NVD-API-blue)

Real-time CVE tracking dashboard pulling live data from the NIST NVD API — filter, paginate, and export vulnerabilities without leaving your browser.

---

## Features

- Fetches latest CVEs live from the NIST NVD API
- Filter by severity (Critical / High / Medium / Low) and date range
- Paginated results to keep the UI fast on large query sets
- One-click CSV export of current filtered results
- Animated severity indicators with CSS gradient transitions

---

## Built with

HTML | CSS | JavaScript | Chrome Extensions API (Manifest V3) | NIST NVD API v2.0

---

## Installation + Quick Start

This version of the extension is not yet on the Chrome Web Store. To run locally:

1. Clone or download this repo
```bash
git clone https://github.com/kosmickaiju/red-alert-extension
```
2. Open Chrome and navigate to `chrome://extensions`
3. Enable **Developer mode** (toggle, top right)
4. Click **Load unpacked** and select the repo folder
5. The extension will automatically load on next browser startup

> No API key required. Rate limit is 5 requests/30s unauthenticated; the extension respects this automatically.

---

## Usage

1. The extension will automatically load on browser startup
2. Use the severity filter and date range to narrow results
3. Scroll through paginated CVE cards
4. Hit **Refresh** to refresh dashboard and display newer CVE reports
5. Hit **Export CSV** to download the current filtered set
