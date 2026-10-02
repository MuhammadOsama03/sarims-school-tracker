# Contributing

Sarim's School Tracker is a dependency-free browser application. Keep changes small, understandable, and safe for locally stored student progress.

## Local review

Serve the repository through a local HTTP server:

```bash
python -m http.server 8000
```

Open `http://localhost:8000` and test attendance, study time, extra work, XP, streaks, achievements, and page reload persistence.

## Required checks

- Test at narrow mobile and desktop widths.
- Navigate every control with a keyboard and confirm visible focus.
- Verify progress remains correct after refresh.
- Test with an empty browser-storage state and with existing saved data.
- Avoid changing storage keys without a migration path.
- Do not add analytics or remote synchronization without updating `PRIVACY.md`.

## Commit quality

Use an imperative commit subject and keep unrelated changes separate. Explain visible changes and storage migrations clearly in the pull request.
