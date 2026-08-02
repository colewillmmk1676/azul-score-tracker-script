# Azul Score - Game Script Utility 2026

> **A browser companion for Azul matches.** Record points after every round, check totals against exact minimum and maximum ranges, and use a compact local HTML tool on desktop or mobile.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/colewillmmk1676/azul-score-tracker-script?style=flat-square)](https://github.com/colewillmmk1676/azul-score-tracker-script)

---

<p align="center">
  <a href="https://colewillmmk1676.github.io/azul-score-tracker-script/">
    <img src="https://img.shields.io/badge/Download-Azul%20Score%20Script-brightgreen?style=for-the-badge" alt="Download Azul Score Script">
  </a>
</p>

> **[Download Azul Score](https://colewillmmk1676.github.io/azul-score-tracker-script/)**

---

[Download Latest Build](https://colewillmmk1676.github.io/azul-score-tracker-script/)

---

## What It Does

Azul Score provides a focused way to record points throughout an Azul game. Enter results round by round, monitor the match as it develops, and use rules-based checks to compare scores with their exact possible ranges.

The page also performs combinatorics-based minimum and maximum score validation. Its undoable move history makes it possible to correct entries during play, while localStorage preserves the current state. Since the utility is distributed as one HTML file, it can be opened locally or used on the web without additional installation.

---

## Included Capabilities

- Record Azul scores one round at a time
- Validate minimum and maximum totals with exact combinatorics
- Consult a built-in Azul rules reference
- Undo previous log entries when a correction is required
- Automatically preserve state through browser localStorage
- Use a single-page layout suited to mobile screens
- Run the web utility from a standalone HTML file
- Follow a dedicated workflow for Azul score entry and checking

---

## Getting Started

1. Download the HTML file or build artifact from the project release location.
2. Open it in a browser, or place it on a basic web page if you want to host it.
3. Enter scores as each round finishes and run the verification checks when useful.

Example:

    open azul-score.html

When organizing the tool in a local directory or website, keep the HTML file with any associated assets so the page can resolve them properly.

---

## Available Settings

| Setting | Purpose | Notes |
| --- | --- | --- |
| Round log | Records every scoring action | Entries can be undone for corrections |
| Verification mode | Evaluates score limits | Based on exact min/max combinatorics |
| Auto-save | Keeps session information | Stored in browser localStorage |
| Rules reference | Provides Azul rules guidance | Helpful when checking scoring questions |
| Mobile layout | Adjusts the interface for small displays | Designed for phone and tablet browsers |

---

## Browser Compatibility and Constraints

Azul Score is a web-based, single-file HTML companion intended for modern browsers that support localStorage.

Known limitations:
- The utility is specifically designed for Azul scoring, not broad board game administration.
- Stored sessions are associated with the browser profile and its storage configuration.
- Clearing browser data can delete saved sessions.

---

## Common Questions

### How can I use the tool?
Open the HTML file in your browser, then enter scores as the match moves from round to round.

### Do I have to install anything?
No. The standalone HTML file can be used without an installation process.

### Will the current session remain available?
Yes. Saved state is retained in the browser through localStorage.

### How can I correct an incorrect score?
Use the undoable move history to reverse the relevant entry and make the correction.

### Does it work on phones?
Yes. The page is intended to work in mobile browsers as well as on desktop.

### Can the workflow be changed?
You can choose how the HTML file is opened, hosted, or arranged, but its built-in behavior remains focused on Azul score tracking and validation.

### Why are my saved scores gone?
Privacy controls, manual browser cleanup, or switching browser profiles can remove localStorage data.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
