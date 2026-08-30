# Ruhaan Gupta — Athlete Profile Site

A single-page site built from your NRAI/Doon School shooting record. Dark,
range-inspired design; the hero target diagram plots your four headline
results as actual "shots." Everything is in `index.html` (styles and
script are embedded), plus `favicon.svg`, `robots.txt`, and `sitemap.xml`
for search engines.

## 1. Before you publish — edit these 3 things

1. **Your GitHub Pages URL** — replace `https://your-username.github.io/`
   in three places: `index.html` (the `<link rel="canonical">`, the two
   `og:url` / JSON-LD `url` fields), `robots.txt`, and `sitemap.xml`.
   Once you know your real URL (step 3 below), a find-and-replace across
   these files takes a minute.
2. **Contact email** — in `index.html`, search for `ruhaan@example.com`
   and swap in a real address (or delete the Contact section if you'd
   rather not list one).
3. **A photo (optional)** — the site currently uses no photography, only
   the SVG target diagram. If you want a real photo on the range, add an
   `<img>` in the hero and I'm happy to help place it.

## 2. Publish with GitHub Pages

1. Create a new repository on GitHub — e.g. `ruhaan-gupta-shooting`
   (or name it `your-username.github.io` if you want it at the bare
   root of your GitHub domain instead of a subpath).
2. Upload the contents of this folder to the repository (drag-and-drop
   on github.com works, or via git — see below).
3. In the repo, go to **Settings → Pages**. Under "Build and
   deployment," set **Source** to "Deploy from a branch," branch
   `main`, folder `/ (root)`. Save.
4. GitHub gives you a live URL within a minute or two, typically:
   - `https://your-username.github.io/ruhaan-gupta-shooting/` (project repo), or
   - `https://your-username.github.io/` (if the repo is named `your-username.github.io`)
5. Go back and do the find-and-replace from step 1 with your real URL,
   commit, and the site updates automatically.

### Via git (command line)

```bash
git init
git add .
git commit -m "Launch athlete profile site"
git branch -M main
git remote add origin https://github.com/your-username/ruhaan-gupta-shooting.git
git push -u origin main
```

Then enable Pages as in step 3 above.

## 3. Getting found by Google and AI search

Publishing the page is step one — indexing and AI-answer visibility take
a bit longer and aren't fully in your control, but these move it faster:

- **Submit the URL to Google Search Console** (search.google.com/search-console).
  Add your site as a property, verify ownership, then submit
  `sitemap.xml`. This is the single biggest lever for getting indexed
  in days rather than weeks.
- **Get it linked from somewhere else** — a mention in a Doon School
  page, an NRAI results page, an Instagram bio link, a LinkedIn profile.
  Search engines (and the crawlers behind AI answers) weight pages more
  when other real pages point to them.
- **Structured data is already in place** — the page includes a
  schema.org `Person` block (name, awards, team, school) in the page
  `<head>`. This is what lets Google's rich results and AI systems parse
  "who is this and what have they done" reliably rather than guessing
  from prose.
- Realistically: expect indexing within days to a couple of weeks after
  submission, and it can take longer for AI-generated answers
  specifically to pick it up, since those often lag standard search
  indexing.

## Files

```
index.html    — the site (HTML + CSS + JS in one file)
favicon.svg   — browser tab icon, same target mark as the header logo
robots.txt    — tells crawlers the site is open to indexing
sitemap.xml   — tells crawlers what pages exist
```
