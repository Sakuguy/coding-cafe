# Lab 4 Notes

**Q1.** --global stores the setting in my user-level config (~/.gitconfig), so it applies to every repository on my computer. Without it, the setting would apply only to the current repository (stored in .git/config), and the command would fail outside a repo.

**Q2.** A hidden .git directory appeared. It is the repository itself: it holds the commit history, objects, branches, HEAD and the repo config. Deleting it removes all the history.

**Q3.** Git offered to track about 6 entries, almost all of them inside .venv/. I did not write those; they are the virtual environment's installed code, which should not be in the repo.

**Q4.** The whole .venv/ folder (and any __pycache__) disappeared from the untracked list. Only the files I actually wrote (README.md, week01/week02, lab2, lab3, .gitignore) remain.

**Q5.** It should be committed. It is part of the project's setup, so committing it means the ignore rules are versioned and shared with anyone who clones the repo.

**Q6.** README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved from the working directory to the staging area.

**Q7.** Git printed the branch, a short commit hash, my message, and a summary that said: 6 files changed. It also listed each created file.

**Q8.** It is the short (abbreviated) commit hash, e.g. 7cdee52. It identifies that exact commit uniquely, so I can refer to it in commands like git show or git checkout.

**Q9.** The loop is: edit files, check with git status, stage with git add, then commit with git commit (and check the result with git log).

**Q10.** README.md is a convention. GitHub looks for it in the repo root and shows it as the front page, so it works as the project's introduction for visitors.

**Q11.** It logged me in to GitHub through the browser and stored an access token. Because I answered yes to authenticating Git, Git now uses that saved token when I push over HTTPS, so no password is needed.

**Q12.** The front page shows the README.md contents, rendered as formatted text. GitHub always displays the README at the repo root as the landing page.

**Q13.** No. Pushing only copies my commits to GitHub. My local history is the same, except Git now also tracks where origin/main is.

**Q14.** A private repo exists on GitHub, but only I and people I invite can see it. A repo that doesn't exist online has no off-site backup and nothing to share, and nobody can be invited to it.
