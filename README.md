# David + Michelle Strength — Shared-Workout Version

This version is designed for **one phone tracking David and Michelle simultaneously**.

## What's new
- No person selection before a workout.
- Every exercise shows David and Michelle together.
- Each set has separate Weight / Reps (or seconds) / RIR / Complete controls for each person.
- Previous performance and progression recommendation are shown separately for David and Michelle.
- Finishing the shared workout saves two individual histories behind the scenes, so Progress still works per person.
- Existing V1 workout history remains compatible because the same IndexedDB database is used.

## Update the already-published GitHub Pages app
1. Open your existing GitHub `strength-tracker` repository.
2. Replace/upload **all files in this folder** at the repository root.
3. Commit the changes to `main`.
4. GitHub Pages should redeploy automatically within a minute or two.
5. On the iPhone, open the app. If you still see the old version, close it completely and reopen it. If needed, open the GitHub Pages URL in Safari once and refresh.

## Data
Workout data stays on the iPhone. This is intentional for the current one-phone workflow.

Use **More → Export backup** periodically.

## October 2026 exercise update
- Face Pull → Standing High-Cable Rear-Delt Row (straight bar; no reverse pec deck or rope needed).
- Plank → Standing Pallof Press.
- Cable Crunch or Dead Bug → Standing Cable Crunch with straight bar only.
- Floor Push-Ups → Incline Push-Ups on a sturdy elevated bench or fixed bar (hands only; feet remain on the floor).
- No exercises require lying, sitting, kneeling, or placing hands on the gym floor.
- IndexedDB database name remains `dm-strength-v1` so existing workout history is retained when updating the **same GitHub Pages URL** on the same device/browser. Previous logs for removed exercises remain in the database, although they will no longer appear as choices for current-exercise progress charts.
- Before replacing files, open **More → Export backup** in the old app; do not uninstall or clear website data.

## October 15 equipment refinement
- Day 2 D1 now uses the straight-bar high-cable rear-delt row, 3 × 12–15.
- No reverse pec deck or rope attachment is required. Straight-bar guidance is included for standing cable crunches; the Pallof press requires a chest-height pulley.
