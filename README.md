# שאלוני בחינה — תזונה (Nutrition Exam Quizzes)

Interactive Hebrew (RTL) self-test app for 14 topics (13 subjects + final exam)
(698 questions incl. True/False).

- **Practice mode** — instant feedback and explanation after each question.
- **Exam mode** — answer everything, get a score and full review at the end.
- Multi-answer questions require an exact match (all correct letters, only those).
- Scores are shown to the student only; nothing is stored or sent anywhere.

## Structure
`index.html` — a single, self-contained static page. All quiz data is embedded
directly as inline JSON, so there are no external data dependencies and the
app works offline (aside from the optional Google Fonts stylesheet, which
falls back to a system font if unavailable).

## Deploy (Vercel)
Static site, no build step. Import the repo in Vercel and deploy with defaults:
Framework preset **Other**, no build command, output directory = repo root.
