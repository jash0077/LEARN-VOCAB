# SSC Vocab Pro

A responsive, browser-only SSC English study app based on the supplied standalone HTML. It includes a 100-word vocabulary library, quizzes, 3D flashcards, progress tracking, and a 12-tense grammar lab.

## Run locally

No package installation is required. From the repository root, run:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

Then open `http://localhost:3000`.

## Progress and privacy

Study progress, theme, and quiz preferences are stored in the browser's `localStorage`; there is no account, server, or database. Pronunciation uses the browser's Web Speech API when available.

## Deploy

The site is plain static HTML and can be deployed to any static host. `index.html` is at the repository root for simple static-host configuration.
