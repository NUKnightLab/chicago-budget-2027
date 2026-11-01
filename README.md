# Chicago's $882 Million Question

Three news interactives about Chicago's projected $882.4 million budget gap for 2027. They tell the same story in increasingly playful ways, as a demo for a news interactives class.

| | Page | What it is |
|---|---|---|
| 1 | [`/quiz/`](quiz/) | A straight news quiz: five multiple-choice questions, each with an explanation and source |
| 2 | [`/ballpark/`](ballpark/) | **Ballpark!**, a game-show-style quiz: guess real budget figures on a slider and score points by how close you get |
| 3 | [`/game/`](game/) | **Gap City**, an isometric 3D simulation built with three.js: close the gap, win 26 City Council votes, and watch 2027 play out |

**Live site:** https://nuknightlab.github.io/chicago-budget-2027/

## How it's built

Plain HTML, CSS and JavaScript with no build step. The game loads [three.js](https://threejs.org/) r160 from jsDelivr, and all of its sound effects and music are synthesized in the browser with the Web Audio API. Each page is one self-contained `index.html`.

These pages were built with an AI coding agent (Claude Code) to show students what that kind of tool can produce.

## Sources

- City of Chicago, [2027 Budget Forecast press release](https://www.chicago.gov/city/en/depts/mayor/press_room/press_releases/2026/september/fy27-budget-forecast.html), Sept. 3, 2026
- WTTW News, [Chicago Faces $882M Budget Gap in 2027](https://news.wttw.com/2026/09/03/chicago-faces-882m-budget-gap-2027-johnson-touts-smaller-expected-election-year), Sept. 3, 2026
- WTTW News, [Mayor Johnson Again Proposes Corporate Tax Hikes to Bridge Budget Gap](https://news.wttw.com/2026/10/20/mayor-johnson-again-proposes-corporate-tax-hikes-bridge-budget-gap-says-city-must-borrow), Oct. 20, 2026
- WTTW News, [Chicago Police Department Overspent Its Budget By $520.5M From 2023-2025](https://news.wttw.com/2026/10/28/chicago-police-department-overspent-its-budget-5205m-2023-2025-data), Oct. 28, 2026

In the game, a few dollar figures are labeled "Game estimate" and show how they were derived from sourced numbers. The game's effects on the city's meters, the council vote counts and the simulated headlines are simplified game mechanics, not predictions.
