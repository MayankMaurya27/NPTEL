# Fieldnotes · Environmental Justice

A responsive, local-first quiz experience for all 247 questions across Weeks 0–12.

## Run

Open `index.html` from a local static server so the browser can load the question bank:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Features

- Week-by-week curriculum with topic search and completion filters
- Graded practice with submission score and full answer review
- Non-graded practice with immediate answer feedback
- Unlimited retakes; best score, completion, and attempt count persist in the browser
- Responsive layout for desktop and mobile

The bundled `public/nptel.json` contains all questions from the supplied JSON, normalized from nested sections while preserving the original question records and answers.
# NPTEL-exam-
