# שאלוני בחינה — תזונה (Nutrition Exam Quizzes)

Interactive Hebrew (RTL) self-test app for 13 nutrition exam questionnaires
(618 questions incl. True/False).

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
