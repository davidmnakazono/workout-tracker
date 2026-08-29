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
