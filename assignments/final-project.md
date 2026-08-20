# Final Project — Capstone

**Due:** Saturday, August 22, 2026 — 12:00 PM (Africa/Mogadishu / EAT)

**Goal:** Ship a real project on GitHub that proves you can run the **full Git & GitHub workflow end to end** — init, `.gitignore`, branching, remote push, issues, pull requests, code review, and a working GitHub Actions check — combining everything from Lessons 0–9.

---

## The project

Pick anything — a personal site, notes, a script, plain text files, whatever you like. Same rule as Assignment 1 and 2: the **content doesn't matter**, any file type is fine (`.md`, `.txt`, `.html`, `.py`, images, whatever). **We are not grading what you build. We are grading how you use Git and GitHub** — commit quality, branching, PRs, issues, review, and automation, done the way real teams do it.

---

## What you are submitting

Before you submit, confirm your capstone repo has:

**Setup & history**
- [ ] A **new** repository created locally with `git init` and pushed to GitHub
- [ ] A **`README.md`** that describes the project (what it is, how to run it)
- [ ] A **`.gitignore`** file in the repo root, matching your project type
- [ ] At least **5 commits**, each a **real, meaningful step** — clear messages (numbered, descriptive, or [conventional](../bonus/01-conventional-commits.md) — see [Lesson 2](../lessons/02-git-basics.md)), not one giant dump commit
- [ ] Every commit shows **your** name and email from Lesson 1

**Branching & merging**
- [ ] At least **2 feature branches** besides `main`, named for what they do (e.g. `feature/readme`, `fix/typo`) — see [Lesson 3](../lessons/03-branching.md)
- [ ] Each merged via a **Pull Request** — no direct commits/pushes to `main` for feature work
- [ ] Each PR has a description explaining **what** changed and **why** — see [Lesson 6](../lessons/06-pull-requests-and-code-reviews.md)

**Issues & review**
- [ ] At least **1 Issue** opened describing a bug or feature, before the work that fixes it
- [ ] At least **1 PR that closes that issue** (use `Fixes #1` or `Closes #1` in the PR description) — see [Lesson 8](../lessons/08-open-source-workflows.md)
- [ ] At least **1 review comment** on one of your own PRs before merging (approve or request changes, then merge) — see [Lesson 6](../lessons/06-pull-requests-and-code-reviews.md)

**Automation**
- [ ] A **GitHub Actions workflow** (`.github/workflows/`) that runs on push and shows a **successful run** (green ✅) in the **Actions** tab — see [Lesson 9](../lessons/09-github-actions-introduction.md)

Grading looks at **how** you did each of these (message quality, branch names, PR descriptions, real issue → PR linking) — not the project's subject matter.

---

## How to submit

Follow the [submissions guide](../submissions/README.md):

1. **Fork** this bootcamp repository to your GitHub account.
2. Create the folder `submissions/<your-github-username>/final-project/` (username must match exactly — case-sensitive).
3. Add a `submission.md` file with your repository URL and confirmation (see template below).
4. **Commit and push** your changes to your fork.
5. Open a **Pull Request** to this repository.
   - PR title: `Final Project Submission - <Your GitHub Username>` (for example, `Final Project Submission - sharafdin`)

### `submission.md` template

Create `submissions/your-username/final-project/submission.md`:

```md
# Final Project — Capstone

- **Name:** Your Full Name
- **GitHub username:** your-username
- **Repository URL:** https://github.com/your-username/your-project

## Confirmation

- [ ] New repository with README.md and .gitignore
- [ ] At least 5 commits with clear messages, showing my name and email
- [ ] At least 2 feature branches merged via Pull Request
- [ ] At least 1 Issue opened and closed by a PR (`Fixes #1`)
- [ ] At least 1 review comment before merging
- [ ] GitHub Actions workflow with a successful (green) run
```

Replace the placeholders with your real details before opening your PR.

---

## Evaluation criteria

| **Criterion** | **What we check** — not the project's content |
| ------------- | ----------------- |
| Separate repo | A new capstone project, not a reused practice repo |
| Commit quality | At least **5**, each a real step (not one dump commit), clear messages, correct author identity |
| Branch practice | At least **2** feature branches with sensible names, each merged via PR — no direct pushes to `main` |
| Issue → PR link | At least **1** Issue opened first, then closed by a PR (`Fixes #`/`Closes #`) |
| Review practice | At least **1** review comment before merge |
| Automation | GitHub Actions workflow with a **successful run** |
| README | Present and describes the project |
| `.gitignore` | Present and matches the project's file types |
| Submission | PR includes `submissions/<username>/final-project/submission.md` with valid URLs |

---

## Common mistakes

| **Mistake** | **Fix** |
| ----------- | ------- |
| Reusing an old assignment repo | Create a **new** repo for this capstone |
| Overcomplicating the project | Content doesn't matter — a few text or Markdown files are enough. Focus effort on the Git/GitHub workflow |
| One giant commit with everything | Break work into **real steps**, each its own commit with a clear message |
| PR not merged | Merge each feature branch via Pull Request on GitHub |
| Issue never linked to a PR | Reference it in the PR description with `Fixes #<number>` |
| No successful Actions run | Push again and check the **Actions** tab until you see ✅ |
| Missing README or `.gitignore` | Add both before submitting |
| Local `main` out of date after merge | Run `git switch main` and `git pull` after merging a PR |
| Submission folder name wrong | Your folder must exactly match your GitHub username (case-sensitive) |
| Changing or modifying others' work | Only edit files inside **your own** folder under `submissions/<your-username>/`. Do not touch anyone else's submission |

---

*Final Project — Git & GitHub Bootcamp*
