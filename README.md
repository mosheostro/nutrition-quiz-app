# שאלוני בחינה — תזונה (Nutrition Exam Quizzes)

Interactive Hebrew (RTL) self-test app for 11 nutrition exam questionnaires
(440 questions: 30 general + 10 clinical-case each).

- **Practice mode** — instant feedback and explanation after each question.
- **Exam mode** — answer everything, get a score and full review at the end.
- Multi-answer questions require an exact match (all correct letters, only those).
- Scores are shown to the student only; nothing is stored or sent anywhere.

## Structure
`index.html` — a single, self-contained static page. All quiz data is embedded
(gzip + base64, decoded in the browser), so there are no external dependencies
and it works offline.

## Deploy (Vercel)
Static site, no build step. Import the repo in Vercel and deploy with defaults:
Framework preset **Other**, no build command, output directory = repo root.
