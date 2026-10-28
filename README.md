# YapYur website

Static website intended for GitHub Pages. No workflow YAML is required: enable Pages in the repository settings and select the `main` branch and `/(root)`.

## Platform downloads

Put release files in these folders:
- `android/` — APK
- `windows/` — installer EXE
- `mac/` — macOS package
- `linux/` — Linux package

The website queries the GitHub Contents API and links the latest-named downloadable file in each folder. README files are ignored. When a platform folder has no build yet, the button links to that folder so a file can be uploaded.

iOS opens the specified YapYur userscript raw gist URL directly.
