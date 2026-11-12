# Ankyra site repository

Before changing anything here, read CLAUDE.md in the private kit, steadyflowuk/cob-kit (attach it with push access).
It holds the shared rules for every chat on either of the owner's Claude accounts, STATUS.md (who is working now, the live
version) and LOG.md (what has been done). In short:

- One chat at a time; pull before every change, push straight after. No branches: push to `main` when checked.
- Never edit `assets/bible/`. `assets/notes/` is changed only by notes work (cob-kit WORKFLOW.md).
- A change to index.html, sw.js or other shell files bumps `VERSION` in sw.js and `APP_VERSION` in index.html together.
- At the end, add an entry to cob-kit LOG.md and update STATUS.md.
