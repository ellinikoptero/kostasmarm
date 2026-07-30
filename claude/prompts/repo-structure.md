# Prompt: Personal life-hub repository structure

Reusable prompt — paste this into Claude to (re)create or extend this repository's structure.

---

Create a folder structure for my personal GitHub repository that organizes my whole life. Base it on my lifestyle with these top-level areas: **diet**, **training**, **travel**, **work**, **university**, **claude** (AI prompts & outputs), and **misc**.

For each area, propose subdirectories that help manage the workload:

- `diet/`: meal-plans, recipes, tracking (calories/weight), shopping-lists
- `training/`: programs, logs (one file per session, `YYYY-MM-DD.md`), progress (measurements/PRs), notes
- `travel/`: planning (wishlist, checklists), trips (one folder per trip, `YYYY-MM-destination/`), documents
- `work/`: projects (one folder each), cv-applications, admin (contracts/invoices), notes
- `university/`: courses (one folder per course), notes, assignments, exams, thesis
- `claude/`: prompts, skills, outputs, config
- `misc/`: ideas, finance, archive

Rules:
1. Put a `README.md` in each top-level folder describing what belongs in it.
2. Add `.gitkeep` files so empty subdirectories are tracked by git.
3. Use markdown for notes and `YYYY-MM-DD-topic.md` naming for dated files.
4. Move finished material to `misc/archive/` instead of deleting it.
5. Never commit sensitive documents (passports, IDs, contracts with personal data) if the repo is public.
