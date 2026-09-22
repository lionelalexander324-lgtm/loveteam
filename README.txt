Team Up for Love H5

Upload index.html and the entire assets folder together to GitHub Pages / your campaign directory.

Performance notes:
- Hero and static assets are WebP.
- Reward videos are compressed to 540x540 H.264 and stripped of audio.
- Reward videos use lightweight poster images and only load/play when scrolled near them.
- Versioned asset filenames help avoid old-browser/CDN cache collisions after updates.
- All CSS/JS is inline in index.html, so there are no extra CSS/JS requests.
