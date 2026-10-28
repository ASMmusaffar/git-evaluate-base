# 🧪 git-evaluate-base

**git-evaluate-base** is the base fixture used to **evaluate Git knowledge** — a tiny, controlled repository you can practice real-world Git workflows on: branching, committing, merging, conflict resolution, rebasing, and pull requests.

> Fork/reference of [Fidenz/git-evaluate-base](https://github.com/Fidenz/git-evaluate-base) — used as an assessment playground.

---

## 📖 The Exercise

The repository contains three intentionally identical files:

```
file1.txt    file2.txt    file3.txt
```

Each file contains **two sections**, and each section has identical lines:

```
File 1
Section 1
    Line 1
    Line 2
    Line 3
Section 2
    Line 1
    Line 2
    Line 3
```

Because every file starts from the same content, edits made in parallel branches touch the *same lines* — which is exactly what you want when practicing:

- 🌿 **Branching** — create feature branches per task
- ✍️ **Commits** — make small, meaningful commits
- 🔀 **Merging** — merge branches back (fast-forward vs. true merge)
- ⚡ **Conflicts** — intentionally resolve merge conflicts between sections
- ↩️ **Rebase** — replay commits on top of `main`
- 🚀 **Pull Requests** — open and complete PRs on GitHub

## 🚀 Suggested Practice Flow

1. Clone the repo.
2. Create `feature/file1-fix` and edit the **Section 1** lines in `file1.txt`.
3. In parallel, create `hotfix/file1-section2` and edit **Section 2** of the same file.
4. Merge branch 1, then branch 2 — resolve the conflict.
5. Rebase the remaining branch on `main`.
6. Push and practice opening a pull request.

## 📄 License

Open for learning/testing use — credit: [Fidenz/git-evaluate-base](https://github.com/Fidenz/git-evaluate-base).
