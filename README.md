# TaskBoard — Code Review Practice Project

A tiny in-memory "task board" library (no external dependencies) used as a
hands-on exercise for practicing code reviews.

The repo has two branches:

- **`main`** 
- **`dev`**

---

## How to use this repo

1. **Fork this repository** to your own GitHub account. When forking, remember to uncheck the **"Copy the main branch only"** checkbox so that you get all branches (including `dev`).
2. In your fork, open a **pull request from `dev` into `main`**.
   This PR is what you'll actually review — treat it exactly like a
   real PR a teammate opened and is waiting on you to look at.
3. **Read through the article on giving code reviews first** (shared
   separately in Notion) before you start. Keep the checklist from that
   article open while you work.
4. Go through the diff and **leave review comments directly on the PR**,
   the same way you would in a real review:
   - Point out anything you think is a bug, security issue, readability
     problem, or missing edge case.
   - Use `blocking:`, `nit:`, or `question:` prefixes on your comments
     so the severity is clear.
   - Explain *why* something is a problem, not just *what* is wrong.
   - Not everything in the diff is necessarily wrong - part of the
     exercise is recognizing when something doesn't need a comment at all.
5. When you're done, **share the PR link with a peer** and have them
   review it too - either by adding their own comments to your PR, or
   by opening their own PR from a fresh fork and comparing notes with
   you afterward.
6. Bring your reviewed PR to the group discussion. We'll compare
   everyone's comments, look at what was caught vs. missed, and rewrite
   a few comments together for tone and clarity.

You do **not** need to fix any of the issues you find - this exercise is
about practicing how you *communicate* a review, not about producing a
fix.
