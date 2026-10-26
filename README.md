# MindMachine.io — AI Learning Lab

A static, responsive Artificial Intelligence quiz site for AI Units I and II. Built with plain HTML, CSS and JavaScript so it can be hosted on GitHub Pages without a build step, API key or backend.

## Features
- Quick Challenge (12 randomized questions, 15-minute timer)
- Full Exam Mode (50 questions, 40-minute timer)
- Instant feedback in both modes, with answer explanations
- One hint and one 50:50 lifeline per question
- Question navigator, answered-state tracking and flags for review
- Countdown timer, progress, streak tracking and final review
- Searchable/filterable question bank with answers, hints and explanations
- Light premium theme, optional dark theme, responsive layout
- Recent results saved locally in the browser to guide future Quick Challenge topic selection
- Keyboard shortcuts: 1–6 select answers; left/right arrows navigate answered questions

## Run locally
Open `index.html` in a modern browser. No install or build step is required.

## Deploy to GitHub Pages
1. Create a GitHub repository, for example `mindmachine-io`.
2. Upload `index.html`, `styles.css`, `app.js`, `questions.js` and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for the Pages deployment to finish and open the published URL.

## Question bank
The bank includes 68 questions across multiple choice, true/false, assertion–reason, fill in the blanks, matching, scenario/application and problem-solving formats. It contains real-world scenarios and search/state-space calculations. Correct options are stored as zero-based indexes in `questions.js`.

## Notes
- This is a client-side educational project. It has no accounts or online leaderboard.
- Scores and recent topic performance are stored in the current browser's local storage. They are not synced across devices.
- External Google Fonts are used when a network connection is available; system fallbacks remain available.
- The website has not been deployed to a live GitHub Pages URL from this package.
