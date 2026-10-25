# School Fest Winner Poster Maker

Premium glassmorphism, mobile-first, browser-only poster generator with single-student and group-item modes, automatic photo cropping, custom grade/position, and high-resolution JPG/PNG downloads.

## Files
- `index.html` — complete self-contained application (poster background embedded)
- `poster-template.png` — separate copy of the poster background artwork

## Run locally
Extract the ZIP completely and open `index.html` in Chrome/Edge. The poster background is embedded inside the HTML to avoid local-file canvas export security errors.

## High-resolution export
Exports at 3072 × 4608 pixels (3× the logical 1024 × 1536 template size). JPG uses high quality; PNG is lossless.

## Deploy to Vercel
1. Extract this ZIP.
2. Upload `index.html` to the root of a GitHub repository. You may also upload `poster-template.png` to keep the separate artwork file.
3. In Vercel, choose **Add New → Project** and import the repository.
4. Framework preset: **Other**. Leave the build command blank and use `.` as the output directory.
5. Click **Deploy**.

## Privacy
The chosen photo is read and rendered locally in the user's browser. There is no database, login, analytics, or server-side photo upload.
