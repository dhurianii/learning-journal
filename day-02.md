# Day 02 — Git Branching, .gitignore & Live Deployment

## What I Did Today
- Learned Git branching workflow used in real companies
- Set up .gitignore to protect sensitive files
- Built a professional HTML portfolio landing page
- Deployed it live on GitHub Pages

## Concepts Learned

### Git Branching
A branch is a separate version of your code.
Main = final working version.
Feature branch = where you safely do your work.

### Commands Used
| Command | What It Does |
|---------|-------------|
| `git branch <name>` | Create a new branch |
| `git checkout <name>` | Switch to a branch |
| `git checkout -b <name>` | Create + switch in one step |
| `git merge <branch>` | Merge branch into main |
| `git push -u origin <branch>` | Push new branch to GitHub |

### .gitignore
Tells Git which files to NEVER push to GitHub.
Critical for protecting API keys and passwords.

Files protected:
- `.env` — API keys and secrets
- `node_modules/` — dependencies folder
- `dist/` and `build/` — compiled output
- `secrets.js` — sensitive config files

### GitHub Pages
Free hosting by GitHub.
Any repo with `index.html` on main = live website.
Enable: Settings → Pages → Branch: main → Save

## What I Built
- `day2-practice` branch — branching practice
- `.gitignore` — security file
- `index.html` — portfolio landing page

## Live Output
🌐 https://dhurianii.github.io/learning-journal

## Errors & Fixes
| Error | Fix |
|-------|-----|
| Wrong name on live site | Edited index.html, committed, pushed |
| Branch had no upstream | Used `git push --set-upstream origin <branch>` |

## Key Takeaway
Every real company uses branching daily.
Nobody pushes directly to main.
Today I worked exactly like a professional developer.

---
*Day 2 of 60 complete ✅*