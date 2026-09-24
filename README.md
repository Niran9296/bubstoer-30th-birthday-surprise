# Our Story — a film for Sam's 30th

A single-page video player for the finished film. Everything's already in
here — the film, the poster image, and the page — so this is ready to
publish as-is.

## Publish it for free on GitHub Pages

1. Create a new **public** repository on GitHub (private repos need a paid
   plan for Pages) — e.g. `our-story-film`.
2. Upload everything in this folder — `index.html`, `README.md`, and the
   `assets/` folder (already contains the film and poster) — to the repo.
   Easiest way: drag-and-drop the whole folder into the GitHub web UI
   ("Add file → Upload files"), or:
   ```bash
   git init
   git add .
   git commit -m "Our story"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/our-story-film.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch",
   branch **main**, folder **/ (root)**. Save.
5. GitHub gives you a live link after a minute or two, usually:
   `https://YOUR-USERNAME.github.io/our-story-film/`

That link plays the film straight in the browser — works on phones,
tablets, and computers, and you can send it privately to anyone.

## File size note

The film is about 34 MB — comfortably under GitHub's 100 MB per-file limit
and the free plan's overall size guidance, so no special setup (like Git
LFS) is needed.

## Privacy

A public GitHub repo means the *code* is public, but the page itself isn't
listed or searchable unless someone has the exact link. If you want it
more private:
- Name the repo something that isn't obviously about Sam.
- Don't link to it from anywhere public.
- For true private hosting, GitHub Pages supports it on a paid GitHub
  Pro/Team plan.

## Updating the film later

If you re-render the film (new fireworks, fixed audio, etc.), just replace
`assets/video/our-story-film.mp4` with the new file (same filename) and
push again — the page doesn't need any changes.
