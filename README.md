# Wildlife Ecology Quiz Prep

A static quiz website built from the 12 Wildlife Ecology Assignment Solutions PDFs supplied for this project.

## Features
- Practice mode by assignment week, with immediate right/wrong feedback.
- Timed mock test with 20 questions and a 20-minute timer. Questions do not repeat across mock-test attempts until all 120 have been used; progress is saved in the same browser.
- All-in-one mode with all 120 questions in randomized order.
- Answer choices are shuffled on each run.
- End-of-test score and answer review.
- Responsive design for mobile and desktop.
- No server, account, API key, or build tools required.

## Run locally
Open `index.html` in a browser. All question data is embedded in the page.

## Publish with GitHub Pages
1. Sign in to GitHub and create a **public** repository (for example `wildlife-ecology-quiz`).
2. Upload `index.html` to the repository root and commit the changes.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait a minute or two. GitHub Pages will show your public website URL on the Pages settings screen.

Anyone with that URL can use the quiz. Changes are stored only in the current browser session; scores are not collected or saved to a central server.

## Important answer-key note
The supplied PDFs show questions and options but do not visibly mark correct options. The quiz includes a manually inferred answer key based on the question wording and ecology knowledge. Please review the key carefully against your official course answer key before sharing it as an authoritative exam resource.


Mock-test no-repeat tracking is stored in your browser local storage. Clearing browser site data or using another browser/device resets that tracking. Starting a test marks its 20 questions as used, even if you leave before finishing. After all 120 questions have been used, the cycle starts over.
