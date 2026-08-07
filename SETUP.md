# Instructor setup — publishing this repository

Everything below is one-time. Budget about 30 minutes. No build tools, no
command line required for the site itself — GitHub Pages serves the Markdown
directly and Docsify renders it in the browser.

---

## 1. Create the repository

1. Go to [github.com/new](https://github.com/new).
2. Name it `mit103-parsu`.
3. Set it **Public**. A public repo is required for free GitHub Pages, and it
   also means students can read the site without an account.
4. Do **not** add a README, `.gitignore` or licence — this folder already has them.

## 2. Push these files

```bash
cd mit103-parsu
git init
git add .
git commit -m "Initial course scaffold for AY 2026-2027"
git branch -M main
git remote add origin https://github.com/<your-username>/mit103-parsu.git
git push -u origin main
```

Prefer a graphical tool? [GitHub Desktop](https://desktop.github.com) does the
same thing: *Add local repository* → *Publish repository*.

## 3. Turn on GitHub Pages

**Settings → Pages → Build and deployment**

- Source: **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Save.

Two minutes later the site is live at
`https://<your-username>.github.io/mit103-parsu/`

The `.nojekyll` file in this folder is what stops GitHub from trying to process
the site with Jekyll. Do not delete it.

## 4. Find and replace two placeholders

| Placeholder | Where | Replace with |
| --- | --- | --- |
| `<instructor-username>` | `CONTRIBUTING.md` | your GitHub username |
| `<your-username>` | `CONTRIBUTING.md`, `index.html` | your GitHub username |

Also update the class schedule and Google Classroom code in `README.md` once
they are finalised — the syllabus leaves both blank.

## 5. Post it to Google Classroom

Create a single pinned post with the site URL and a one-line explanation, and
keep it pinned all semester. Every subsequent Classroom post links back to a week
page rather than repeating its content.

Suggested wording:

> **Course site:** https://\<your-username\>.github.io/mit103-parsu/
>
> Readings, weekly activities, rubrics and templates live there. Announcements,
> deadlines and grades stay here in Classroom. Bookmark both.

---

## Running it during the semester

**To edit any page:** open the file on GitHub, click the pencil icon, edit,
commit. The site updates in about a minute. You never need to touch a terminal
for content changes.

**To add slides:** drop the PDF or PPTX in `slides/` and link it from the week
page. Do not upload third-party PDFs badged <span class="badge badge-free">FREE</span>
in the resource list — link to the source instead. See [LICENSING](LICENSING.md).

**To accept student work:** review the pull request, comment inline, then either
merge it or leave it open with feedback. Merging is not the grade — record grades
in Classroom as usual.

**To create the submissions folder structure:** add
`submissions/.gitkeep` before the semester starts so students have somewhere to
put their folders.

---

## If Git is a barrier for this cohort

A reasonable fallback: publish the site as above, but collect submissions through
Google Classroom instead of pull requests. You keep the readable, maintainable,
legally-clean site and lose only the f.2 collaboration evidence.

Middle option: use Classroom for Deliverables 1–2 while students find their feet,
then switch to pull requests from Deliverable 3 (Week 7) onward, once the Week 2
Git lab has had time to settle.

---

## Refresh checklist for next semester

- [ ] Update the AY, semester and schedule in `README.md`
- [ ] Re-check every link in `resources.md` — the list recommends a per-semester review
- [ ] Check [Open Textbook Library](https://open.umn.edu/opentextbooks/subjects/information-systems), [BCcampus](https://collection.bccampus.ca) and OpenStax for new titles
- [ ] Archive the previous cohort's `submissions/` to a separate private repository
- [ ] Re-read `LICENSING.md` — third-party licence terms do change
