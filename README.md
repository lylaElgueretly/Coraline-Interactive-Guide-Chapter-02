# Coraline, Chapter 2: The Mist and the Warning

A browser-based, 3D comprehension activity for *Coraline* by Neil Gaiman, Chapter 2. Built for personal classroom use alongside a Chapter 2 reading questions worksheet and vocabulary sheet, not for commercial distribution.

Students walk a small 3D house and garden as Coraline, meet the characters from the chapter, and answer comprehension, vocabulary, and inference questions tied to what they find at each location. No login, no install, no data collection: everything runs client-side in the browser and nothing is saved once the page is closed.

## Live link

Once GitHub Pages is switched on for this repository (see below), the game will be available at:

```
https://<your-github-username>.github.io/<repository-name>/
```

Share that link directly with students. It works on a computer, Chromebook, tablet, or phone with a modern browser; no download or account needed.

## How to publish this with GitHub Pages

1. Create a new repository on GitHub and upload `index.html`, `README.md`, and `robots.txt` to it (or push them with git).
2. Go to the repository's **Settings** tab, then **Pages** in the left sidebar.
3. Under **Build and deployment**, set **Source** to "Deploy from a branch."
4. Set **Branch** to `main` (or `master`) and the folder to `/ (root)`, then **Save**.
5. Wait a minute or two, then refresh the Pages settings page; it will show the live URL.

## What's in this repository

| File | Purpose |
|---|---|
| `index.html` | The entire game: 3D scene, all questions, vocabulary checks, and the Notebook. Everything is in this one file, no other files are required for it to run. |
| `robots.txt` | Asks search engines not to index the page. GitHub Pages sites are public to anyone with the link by default; this just keeps it out of search results. It does not restrict who can open the link directly. |
| `README.md` | This file. |

## What it covers

- 7 comprehension clues matched to the Chapter 2 reading questions answer key (prediction, fact vs opinion, figurative language, sequencing, cause and effect, retrieval, inference)
- A "Story so far" plain-English recap for students who need the gist quickly
- A character traits and atmosphere/mood reflection section
- Vocabulary: `parlor` and `mantelpiece` as clickable checks placed inside the parlour, where those words belong in the story; `flyblown` and `distorted` (carried over from Chapter 1) reviewed in a separate "Vocabulary: all in one go" screen
- Read-aloud support on story quotes, and a "Tricky words" glossary, for weaker readers

## Known limitations

- **Public by default.** Anyone with the link can open this, GitHub Pages does not support private, login-gated pages on a free account. `robots.txt` keeps it out of search engines but does not password-protect it.
- **Requires an internet connection** the first time it loads (to fetch the page from GitHub), and a browser with WebGL support for the 3D view. If a device can't run WebGL, the page still loads and every question is still answerable through the Notebook, just without the 3D scene.
- **Nothing is saved.** Student writing and progress live only in the browser tab for that session. If the page is refreshed or closed, answers are lost. Have students copy written answers elsewhere (or screenshot the Notebook) before closing the tab, if you need a record.
- **Not tested on every device.** This was built and checked with automated script tests, not a manual walkthrough on a classroom Chromebook or tablet. Test on one student device before rolling out to a full class.

## Licence and use

This is a personal teaching resource built around a copyrighted novel (*Coraline*, Neil Gaiman, 2002). It references characters, settings, and short quoted lines from the book for educational, non-commercial comprehension practice, in the same spirit as a printed study guide. It is not affiliated with or endorsed by Neil Gaiman, HarperCollins, or Focus Features. Please keep this to personal/classroom use rather than public redistribution.
