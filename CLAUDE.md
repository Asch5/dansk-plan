# CLAUDE.md — agent rules for `Asch5/dansk-plan`

1. **Source of truth = Google Drive**, `Main_drive/language-learning/dansk/self-study/` (via the PC
   bridge). Before any work read there: `README.md` §0, `process_log.md`, `CLAUDE.md`, then
   `tools/docs/README.md` (developer docs) and `tools/docs/RELEASE.md`.
2. **Never hand-edit** `index.html`, `data/`, `audio/`, `video/` here. Change Drive, rebuild with
   `tools/build_site.py`, publish the output.
3. **Publishing:** branch (`feature/…`, `fix/…`) → for site changes first `archive/site-<date of the
   last change on main>` → PR via REST (`gh api repos/Asch5/dansk-plan/pulls`) → merge commit.
   Show Anton the exact file list; push / merge **only after his explicit "да"**.
4. Docs are not copied here (decision 19.11.2026: one copy, next to the code on Drive). Only this file
   and `README.md` live in the repo; keep them short pointers.
5. The site is public: no personal data in any file.
