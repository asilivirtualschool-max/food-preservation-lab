# Food Preservation Lab

An interactive **PYP 5 Science** lesson (Lesson 1 of 2) on **food preservation**, built in the GEMS "Learn Like a GEM" house style. It follows the teacher's PowerPoint slide‑by‑slide and uses the Info‑Cards flipped‑reading as a pre‑test.

**Differentiation:** students take a **10‑question pre‑test** (4 of them *select‑all*), see a recommended **Ready / Steady / Go** path on entry, and may choose any path. Options are shuffled so the longest answer isn't always correct.

**Teacher‑paced:** the teacher opens a class with a code + PIN, watches a **live map** of where each student is, and **releases** stages one at a time — students wait at a pause screen until the next stage is released. A **Present** mode projects each stage for the class.

Lesson flow (from the PPT): Pre‑test → Recall → Food Spoilage → Outcome 1 → Apple check → Outcome 2 → Hook → **Station inquiry (We Do)** → Progress check → What's in common → **Explain the Science (You Do)**.

## Files
- `index.html` — page shell + styles + Firebase SDK
- `app.js` — the whole app (lesson, pre‑test, dashboard, pacing, Firestore)
- `firestore.rules` — security rules (same as the Compare Characters project)

## Setup
Reuses the existing **compare-characters-lab** Firebase project (class data is namespaced by class code, so the two lessons don't collide). To host:
1. Upload `index.html`, `app.js` (and this README) to the repo.
2. **Settings → Pages → Build from branch → `main` / root → Save.**
3. Live at `https://asilivirtualschool-max.github.io/food-preservation-lab/`.

## Using it
- **Teacher:** open the link → *Open a class* → set a PIN → share the 5‑letter code → turn on **teacher‑paced** and release stage by stage → **Class view** to project the map or present the lesson.
- **Students:** open the link → *Join a class* → code + name → take the pre‑test → pick a path → work through as the teacher releases each stage.
