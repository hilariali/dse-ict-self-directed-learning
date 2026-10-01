# DSE ICT Self-Directed Learning System

An offline-first, self-directed study platform for the Hong Kong HKDSE
Information and Communication Technology (ICT) curriculum.

## Coverage

- Aligned to the EDB *Information and Communication Technology Curriculum
  and Assessment Guide* (final edition)
- 8 modules (5 compulsory + 3 electives), 24 topics, 134 learning objectives
- 787 original DSE-style practice questions (5 per learning objective)
- Multimedia study unit per objective: explanation, video, reading,
  listening cue, active-recall interaction, concept map
- See–Think–Wonder thinking routine opens every learning package
- Knowledge mind-map of the whole curriculum (nodes light up as you pass)
- Quick (10 MC) and Full (40 MC) cross-topic diagnostic tests
- Progress tracking, revision queue, timed mocks, teacher dashboard

## Run it

This is a fully static site. Open `index.html` in any modern browser —
no server or build step needed.

- `index.html` — the whole platform (single file)
- `assets/*.mp3` — 24 narrated topic overviews (listening mode)

Everything except YouTube videos and external reading links works offline.

## Deploy (GitHub Pages)

1. Upload the contents of this folder to a public repo
   (e.g. `dse-ict-self-directed-learning`)
2. Repo Settings → Pages → Deploy from branch → `main` / `/ (root)`
3. The site goes live at
   `https://<username>.github.io/dse-ict-self-directed-learning/`

Built with care for ICT students in Hong Kong.
