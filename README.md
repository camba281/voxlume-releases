# Voxlume — releases

*Every voice, brought to light.*

Public release notes and version info for **Voxlume** (formerly Audio Transcriber), a desktop app that turns
recordings into speaker-labeled transcripts with AI summaries.

Installed copies of the app read [`latest.json`](latest.json) once a day to tell users when a new version is
available. See [Releases](../../releases) for what changed in each version.

## Publishing a new version

1. Bump `VERSION` in the app (`updates.py`).
2. Update `latest.json` here with the new `version`, `date` and short `notes`.
3. Create a GitHub Release with the same tag (for example `v2.3.0`) and fuller notes.
