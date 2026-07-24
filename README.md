# Gaurav Luthra — Personal Website

A static personal site built from your CV: hero intro with key stats, About,
a career-log style timeline, Areas of Expertise, Credentials (certifications,
education, awards), and Contact. No build step — just HTML, CSS, and JS.

## 1. Remaining personalization

Everything from your CV is already filled in. Two things are still
placeholders:
- **Photo** — add a file named `photo.jpg` in this same folder (crops to a
  260x320 frame; a portrait-oriented photo works best). Until you add one,
  a clean placeholder box shows instead, so the site never breaks.
- **LinkedIn link** — in `index.html`, find the Contact section and replace
  `https://www.linkedin.com/in/yourusername` with your real profile URL.

Everything else (bio, dates, titles, skills, certifications, education,
awards, email, phone) was pulled from your CV — skim it once to make sure
nothing needs adjusting.

## 2. Preview it locally

Just open `index.html` in a browser — no server needed for a first look.

## 3. Put it on GitHub Pages

1. Create a new GitHub repo. If you want it at `https://<username>.github.io`,
   name the repo exactly `<username>.github.io`. Otherwise any name works and
   it'll be published at `https://<username>.github.io/<repo-name>`.
2. Push these files to the repo's default branch (usually `main`):
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch",
   choose `main` and `/ (root)`, then save.
5. Wait a minute or two, then visit the URL GitHub shows on that same page.

That's it — no server, no build tools, no cost.
