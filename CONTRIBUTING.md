# How to submit your work

All portfolio deliverables are submitted through this repository. The PR link
goes to Google Classroom, which holds the official timestamp.

If you have never used Git, that is expected — Week 2's lab walks through it, and
the same workflow repeats for every deliverable after that. Learning it is part
of the course (program outcome **f.2**).

---

## One-time setup

1. **Create a GitHub account** and send your username through Google Classroom.
2. **Fork this repository.** Click *Fork*, top right. You now have your own copy.
3. **Clone your fork** to your machine:

   ```bash
   git clone https://github.com/<your-username>/mit103-parsu.git
   cd mit103-parsu
   ```

4. **Add the class repository as `upstream`** so you can pull updates:

   ```bash
   git remote add upstream https://github.com/<instructor-username>/mit103-parsu.git
   ```

5. **Create your submission folder:** `submissions/<your-surname>/`

---

## Every submission

```bash
# 1. Get the latest course materials
git checkout main
git pull upstream main

# 2. Branch for this deliverable
git checkout -b surname/03-system-design

# 3. Do the work, then stage and commit
git add submissions/surname/03-system-design/
git commit -m "Week 7: DFD set for barangay records system"

# 4. Push to your fork
git push origin surname/03-system-design
```

Then open a pull request on GitHub, and **post the PR link to Google Classroom**.

## Branch naming

`<surname>/<deliverable-number>-<short-name>` — for example
`briones/04-database-design`.

## What to commit

**Commit the source, not only the export.**

| Artefact | Commit this | Also commit |
| --- | --- | --- |
| Diagrams | `.drawio`, `.puml`, `.bpmn` | PNG or SVG export |
| Database | `.dbm` (pgModeler), `.sql` DDL | ERD image |
| Prototypes | Penpot export | Screenshots of key screens |
| Documents | Markdown | PDF if formatting matters |

Source files diff cleanly, which means your history shows how your thinking
changed. That history is assessable evidence.

## What not to commit

- Files over 25 MB. Link to cloud storage instead and put the link in your README.
- Personal data. Anonymise interview transcripts and any real records before they
  go anywhere near a public repository. This is a Data Privacy Act obligation, not
  a style preference (PO3 c.3).
- Passwords, API keys, connection strings. If you commit one by accident, tell the
  instructor immediately and rotate the credential — deleting the file does not
  remove it from history.

## Commit messages

Say what changed and why:

- Good — `Week 8: normalise enrolment table to 3NF, split repeating group`
- Not useful — `update`, `final`, `final2`, `FINAL FINAL`

## Peer review

Some weeks ask you to review a classmate's work. Comment on their pull request.
Review the artefact, not the person, and name a specific line or element. "This
context diagram has two processes" is useful. "Looks good" is not.

## If something goes wrong

Git problems are not graded. Ask in the class group chat or during consultation
hours. Nobody loses marks for a merge conflict.
