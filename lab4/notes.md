# Lab 4 Notes

**Q1.** --global stores the setting in my user-level config (~/.gitconfig), so it applies to every repository on my computer. Without it, the setting would apply only to the current repository (stored in .git/config), and the command would fail outside a repo.

**Q2.** A hidden .git directory appeared. It is the repository itself: it holds the commit history, objects, branches, HEAD and the repo config. Deleting it removes all the history.

**Q3.** Git offered to track about 4 entries, almost all of them inside .venv/. I did not write those; they are the virtual environment's installed code, which should not be in the repo.

**Q4.** The whole .venv/ folder (and any __pycache__) disappeared from the untracked list. Only the files I actually wrote (README.md, week01/week02, lab2, lab3, .gitignore) remain.

**Q5.** It should be committed. It is part of the project's setup, so committing it means the ignore rules are versioned and shared with anyone who clones the repo.

**Q6.** README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved from the working directory to the staging area.

**Q7.** Git printed the branch, a short commit hash, my message, and a summary that said: 5 files changed. It also listed each created file.

**Q8.** It is the short (abbreviated) commit hash, e.g. 9d26234. It identifies that exact commit uniquely, so I can refer to it in commands like git show or git checkout.
