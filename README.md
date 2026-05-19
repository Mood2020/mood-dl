# Mood DL

A GitHub Actions project to download videos **only when you have rights/permission** to download them.

## Features
- Manual workflow trigger with one or multiple video URLs
- Selectable max quality (360/480/720/1080)
- Automatic thumbnail download
- Splits large files into multi-part ZIP archives (`.z01`, `.z02`, ..., `.zip`)
- Outputs artifacts and optionally commits into `videos/`

## Usage
1. Go to **Actions** tab.
2. Run workflow: `Download Video (Permitted Content)`.
3. Enter URLs separated by spaces.
4. Choose quality and split size.
5. Download generated files from either:
   - Action artifacts, or
   - `videos/` folder (if `commit_to_repo=true`).

## Important
Use this repository only for legal, permitted content.
