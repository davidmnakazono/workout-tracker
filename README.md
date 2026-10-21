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
- Plank → Standing Cable Crunch (fixed high pulley and straight bar).
- Cable Crunch or Dead Bug → Standing Cable Crunch with straight bar only.
- Floor Push-Ups → Incline Push-Ups on a sturdy elevated bench or fixed bar (hands only; feet remain on the floor).
- No exercises require lying, sitting, kneeling, or placing hands on the gym floor.
- IndexedDB database name remains `dm-strength-v1` so existing workout history is retained when updating the **same GitHub Pages URL** on the same device/browser. Previous logs for removed exercises remain in the database, although they will no longer appear as choices for current-exercise progress charts.
- Before replacing files, open **More → Export backup** in the old app; do not uninstall or clear website data.

## October 15 equipment refinement
- Day 2 D1 now uses the straight-bar high-cable rear-delt row, 3 × 12–15.
- No reverse pec deck or rope attachment is required. Straight-bar guidance is included for standing cable crunches; the fixed high pulley does not support the Pallof press, which is replaced with standing cable crunches.

## October 15 progressive overload update (v5)
- Day 3 C2 incline push-ups → **Straight-Bar Triceps Pressdown**, 3 × 10–15.
- Day 2 A1 unloaded single-leg RDL → **Machine Hamstring Curl**, 3 × 10–15 on convertible leg-extension/curl machine.
- Day 2 C2 calf raises → **Single-Leg Calf Raise (Slow Tempo)**, 3 × 10–15/leg; 3-second lower, 2-second bottom hold, 2-second top hold.
- Separate progression prompts remain for David and Michelle. At the top of a machine exercise rep range for every set, increase resistance in the next session; on calf raises prioritize strict tempo and then safe additional load.
- The existing `dm-strength-v1` IndexedDB store and history are untouched; previous exercise history remains saved. Export backup before installing.

## October 21 fixed-high-pulley update (v6)
- Day 1 D2 Standing Pallof Press → **Standing Cable Crunch**, 3 × 12–15, using the fixed high pulley and straight bar.
- Day 2 D2 standing cable crunch standardized to 3 × 12–15.
- Removed unavailable Pallof press setup instructions.
- Service worker cache bumped to v6 for easier updates.
- Keep the same app URL to retain existing local workout logs; export a backup before updating.
